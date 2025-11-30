# TextMagic::MessagePriceItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Country name. |  |
| **price** | **String** | Price to send message to desired country. |  |
| **country** | **String** | The 2-letter ISO country code of the recipient&#39;s phone number. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MessagePriceItem.new(
  name: United Kingdom,
  price: 0.049,
  country: UK
)
```

