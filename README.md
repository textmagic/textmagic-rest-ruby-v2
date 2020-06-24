[comment]: <> (HEAD)
# TextMagic Ruby SDK
This library provides you with an easy way of sending SMS and receiving replies by integrating the TextMagic SMS Gateway into your Ruby application.

## What Is TextMagic?
TextMagic’s application programming interface (API) provides the communication link between your application and TextMagic’s SMS Gateway, allowing you to send and receive text messages and to check the delivery status of text messages you’ve already sent.


[comment]: <> (/HEAD)
## Installation

Add these lines into your Gemfile
```ruby
gem 'textmagic_rest_client', :git => 'https://github.com/textmagic/textmagic-rest-ruby-v2.git', :tag => 'v2.0.1530'
```

Run the bundler install command
``` shell
bundle install
```

## Usage Example

Create the test file `test.rb` and put the following code:
```ruby
 # Load the gem
require 'textmagic_rest_client'

 # Setup authorization
TextMagic.configure do |config|
    # put your Username and API Key from https://my.textmagic.com/online/api/rest-api/keys page.
    config.username = 'YOUR_USERNAME'
    config.password = 'YOUR_API_KEY'
end

api_instance = TextMagic::TextMagicApi.new

 # Simple ping request example
begin
    result = api_instance.ping
    puts result.ping
rescue TextMagic::ApiError => e
    puts "Exception when calling TextMagicApi->ping: #{e}"
end

 # Send a new message request example
send_message_input_object = TextMagic::SendMessageInputObject.new
send_message_input_object.text = 'I love TextMagic!'
send_message_input_object.phones = '+19998887766'

begin
    result = api_instance.send_message(send_message_input_object)
    puts result.id
rescue TextMagic::ApiError => e
    puts "Exception when calling TextMagicApi->send_message: #{e}"
end

 # Get all outgoing messages request example
begin
    result = api_instance.get_all_outbound_messages(page: 1, limit: 10)
    puts result.resources[0].text
rescue TextMagic::ApiError => e
    puts "Exception when calling TextMagicApi->get_all_outbound_messages: #{e}"
end

 # Upload new avatar for contacts list (group) with Id 3223 example
file = File.open('test.png', 'r')
begin
    result = api_instance.upload_list_avatar(file, 3223)
    puts result.id
rescue TextMagic::ApiError => e
    puts "Exception when calling TextMagicApi->upload_list_avatar: #{e}"
end
```

Run the script:
```
bundle exec ruby test.rb
```

[comment]: <> (FOOTER)
## License
The library is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

[comment]: <> (/FOOTER)
