# TextMagic::RequestNewSubaccountTokenRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | Sub-account ID. | [optional] |
| **password** | **String** | Your account password. | [optional] |
| **app_name** | **String** | Application name. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::RequestNewSubaccountTokenRequest.new(
  user_id: 1,
  password: strongPassword,
  app_name: sample app
)
```

