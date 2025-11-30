# TextMagic::SenderSettingsItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **country** | **String** | The 2-letter ISO country code of the recipient&#39;s phone number.  |  |
| **phone** | **String** | Phone enabled for sending to a specified country. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::SenderSettingsItem.new(
  country: US,
  phone: +447937946700
)
```

