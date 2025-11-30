# TextMagic::UpdateSenderSettingRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **value** | **String** | Available phone number in international E.164 format or senderid. | [optional] |
| **country** | **String** | Country for which the setting will be set. | [optional] |
| **chat_id** | **Integer** | Set sender setting for specified chat only. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UpdateSenderSettingRequest.new(
  value: 447624800500,
  country: AF,
  chat_id: 344
)
```

