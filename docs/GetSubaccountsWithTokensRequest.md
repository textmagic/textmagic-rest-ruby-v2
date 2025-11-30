# TextMagic::GetSubaccountsWithTokensRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **app_name** | **String** | Application name. | [optional] |
| **password** | **String** | Your account password. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetSubaccountsWithTokensRequest.new(
  app_name: sample app,
  password: strongPassword
)
```

