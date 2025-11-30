# TextMagic::GetMessagePriceResponseCountriesItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **country** | **String** | The 2-letter ISO country code. |  |
| **country_name** | **String** | Country name. |  |
| **allow_dedicated** | **Boolean** | Is allowed to use a dedicated number? |  |
| **count** | **Float** | Parts count to send. |  |
| **max** | **Float** | Maximum parts to send. |  |
| **sum** | **String** | Total price to send. |  |
| **landline** | **Float** | Is this a landline number? |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetMessagePriceResponseCountriesItem.new(
  country: US,
  country_name: United State,
  allow_dedicated: true,
  count: 1.0,
  max: 6.0,
  sum: 1,
  landline: 0.0
)
```

