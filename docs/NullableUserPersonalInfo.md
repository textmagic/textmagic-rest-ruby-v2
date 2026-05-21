# TextMagic::NullableUserPersonalInfo

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | User ID. | [optional] |
| **first_name** | **String** | User&#39;s first name. | [optional] |
| **last_name** | **String** | User&#39;s last name. | [optional] |
| **avatar_url** | **String** | URL to user&#39;s avatar image. | [optional] |
| **email** | **String** | User&#39;s email address. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::NullableUserPersonalInfo.new(
  id: 456,
  first_name: John,
  last_name: Smith,
  avatar_url: https://example.com/avatar.jpg,
  email: john.smith@example.com
)
```

