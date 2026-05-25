[comment]: <> (HEAD)
# TextMagic Ruby SDK

[![Gem Version](https://badge.fury.io/rb/textmagic_rest_client.svg)](https://badge.fury.io/rb/textmagic_rest_client)
[![Ruby](https://img.shields.io/badge/ruby-%3E%3D%202.7-ruby.svg)](https://www.ruby-lang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This library provides you with an easy way of sending SMS and receiving replies by integrating the TextMagic SMS Gateway into your Ruby application.

## What Is TextMagic?

TextMagic's application programming interface (API) provides the communication link between your application and TextMagic's SMS Gateway, allowing you to send and receive text messages and to check the delivery status of text messages you've already sent.


[comment]: <> (/HEAD)

## Requirements

- **Ruby 2.7+** (Ruby 2.6 and earlier are no longer supported)
  - Tested on Ruby 2.7, 3.0, 3.1, 3.2, 3.3
- **Bundler** for dependency management

### Dependencies

- **Typhoeus** ~> 1.0 (HTTP client library)
- **RSpec** ~> 3.6 (for development/testing)

## Installation

### Via RubyGems (Recommended)

```bash
gem install textmagic_rest_client
```

### Via Gemfile

Add this line to your `Gemfile`:

```ruby
gem 'textmagic_rest_client', '~> 3.0.50052'
```

Then run:

```bash
bundle install
```

### From GitHub

Add this line to your `Gemfile`:

```ruby
gem 'textmagic_rest_client', git: 'https://github.com/textmagic/textmagic-rest-ruby-v2.git', tag: 'v3.0.50052'
```

Then run:

```bash
bundle install
```

### Updating the Gem

```bash
# Update to latest version
bundle update textmagic_rest_client

# Or via gem command
gem update textmagic_rest_client
```

## Quick Start

### Basic Usage

```ruby
require 'textmagic_rest_client'

# Configure API credentials
# Get your credentials from https://app.textmagic.com/settings/api
TextMagic.configure do |config|
  config.username = 'YOUR_USERNAME'
  config.password = 'YOUR_API_KEY'
end

# Create API instance
api = TextMagic::TextMagicApi.new

# Test connection
begin
  result = api.ping
  puts "✅ Connected! Server time: #{result.ping}"
rescue TextMagic::ApiError => e
  puts "❌ Error: #{e}"
end
```

### Sending Messages

```ruby
require 'textmagic_rest_client'

TextMagic.configure do |config|
  config.username = 'YOUR_USERNAME'
  config.password = 'YOUR_API_KEY'
end

api = TextMagic::TextMagicApi.new

# Send SMS to a single number
begin
  message = TextMagic::SendMessageInputObject.new(
    text: 'Hello from TextMagic Ruby SDK!',
    phones: '+1234567890'
  )
  result = api.send_message(message)
  puts "✅ Message sent! ID: #{result.id}"
  puts "   Session ID: #{result.session_id}"
rescue TextMagic::ApiError => e
  puts "❌ Error sending message: #{e}"
end

# Send SMS to multiple numbers
begin
  message = TextMagic::SendMessageInputObject.new(
    text: 'Bulk message',
    phones: '+1234567890,+0987654321'  # Comma-separated
  )
  result = api.send_message(message)
  puts "✅ Bulk message sent! Session ID: #{result.session_id}"
rescue TextMagic::ApiError => e
  puts "❌ Error: #{e}"
end
```

### Getting Outgoing Messages

```ruby
require 'textmagic_rest_client'

TextMagic.configure do |config|
  config.username = 'YOUR_USERNAME'
  config.password = 'YOUR_API_KEY'
end

api = TextMagic::TextMagicApi.new

begin
  # Get recent outgoing messages
  result = api.get_all_outbound_messages(page: 1, limit: 10)

  puts "Total messages: #{result.page.total}"
  result.resources.each do |message|
    puts "- [#{message.id}] #{message.text[0..50]}... → #{message.receiver}"
    puts "  Status: #{message.status}, Sent: #{message.created_at}"
  end
rescue TextMagic::ApiError => e
  puts "❌ Error: #{e}"
end
```

### Uploading Files

```ruby
require 'textmagic_rest_client'

TextMagic.configure do |config|
  config.username = 'YOUR_USERNAME'
  config.password = 'YOUR_API_KEY'
end

api = TextMagic::TextMagicApi.new

# Upload list avatar
begin
  file = File.open('path/to/avatar.png', 'r')
  result = api.upload_list_avatar(file, 12345)  # 12345 is List ID
  puts "✅ Avatar uploaded! Resource ID: #{result.id}"
rescue TextMagic::ApiError => e
  puts "❌ Error: #{e}"
ensure
  file.close if file
end
```

### Error Handling

```ruby
require 'textmagic_rest_client'

TextMagic.configure do |config|
  config.username = 'YOUR_USERNAME'
  config.password = 'YOUR_API_KEY'
end

api = TextMagic::TextMagicApi.new

begin
  message = TextMagic::SendMessageInputObject.new(
    text: 'Test message',
    phones: '+1234567890'
  )
  result = api.send_message(message)
  puts "✅ Success: #{result.id}"
rescue TextMagic::ApiError => e
  puts "❌ API Exception:"
  puts "   Code: #{e.code}"
  puts "   Message: #{e.message}"
  puts "   Response body: #{e.response_body}"
rescue StandardError => e
  puts "❌ Unexpected error: #{e}"
end
```

## API Documentation

For detailed API documentation, including all available methods and parameters, please visit:

- **REST API Documentation:** https://docs.textmagic.com/

### Available Methods

The SDK provides access to all TextMagic API endpoints, including:

- **Messages:** Send, receive, and manage SMS messages
- **Contacts:** Manage your contact lists
- **Templates:** Create and use message templates
- **Chats:** Manage conversations
- **Bulk Messaging:** Send messages to multiple recipients
- **Sender IDs:** Manage sender names
- **Account:** Check balance and account information
- **Statistics:** Get messaging statistics and reports

## Migration Guide

### Migrating from v2.x to v3.x

#### Breaking Changes

1. **Ruby Version Requirements:**
   - v2.x: Ruby 2.4+
   - v3.x: Ruby 2.7+ only

2. **HTTP Library:**
   - v2.x: Various libraries
   - v3.x: Typhoeus (modern, thread-safe)

3. **Object Initialization:**
   ```ruby
   # v2.x
   message = TextMagic::SendMessageInputObject.new
   message.text = 'Hello'
   message.phones = '+1234567890'

   # v3.x (supports both styles, but keyword arguments preferred)
   message = TextMagic::SendMessageInputObject.new(
     text: 'Hello',
     phones: '+1234567890'
   )
   ```

#### What Stays the Same

- ✅ Module name: `TextMagic` (unchanged)
- ✅ Gem name: `textmagic_rest_client` (unchanged)
- ✅ Configuration method: `TextMagic.configure` (unchanged)
- ✅ API method names and signatures
- ✅ Response objects structure
- ✅ Authentication mechanism
- ✅ Error handling with `TextMagic::ApiError`

#### Upgrade Steps

1. **Update Ruby version** (if needed):
   ```bash
   # Check current Ruby version
   ruby -v

   # Install Ruby 2.7+ using rbenv or rvm
   rbenv install 3.3.0
   rbenv global 3.3.0
   ```

2. **Update Gemfile**:
   ```ruby
   # Update version constraint
   gem 'textmagic_rest_client', '~> 3.0'
   ```

3. **Install new version**:
   ```bash
   bundle update textmagic_rest_client
   ```

4. **Update code** (if using old initialization style):
   ```ruby
   # Old style still works, but prefer keyword arguments
   message = TextMagic::SendMessageInputObject.new(
     text: 'Hello',
     phones: '+1234567890'
   )
   ```

5. **Test your application**:
   ```bash
   bundle exec rspec
   # or your test command
   ```

## Development

### Running Tests

```bash
# Install development dependencies
bundle install

# Run tests
bundle exec rspec

# Run tests with coverage
bundle exec rspec --format documentation
```

### Building the Gem

```bash
# Build gem file
gem build textmagic_rest_client.gemspec

# Install locally
gem install ./textmagic_rest_client-3.0.50052.gem
```

## Need Help?

- **Documentation:** https://docs.textmagic.com/
- **Support:** https://www.textmagic.com/support/
- **GitHub Issues:** https://github.com/textmagic/textmagic-rest-ruby-v2/issues

[comment]: <> (FOOTER)
## License
The library is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

[comment]: <> (/FOOTER)
