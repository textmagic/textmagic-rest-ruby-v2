# TextMagic::GetMessagePriceResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total** | **Float** | Total price of the message. |  |
| **parts** | **Integer** | Message parts (multiples of 160 characters) count. |  |
| **countries** | [**Array&lt;GetMessagePriceResponseCountriesItem&gt;**](GetMessagePriceResponseCountriesItem.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetMessagePriceResponse.new(
  total: 0.08,
  parts: 6,
  countries: null
)
```

