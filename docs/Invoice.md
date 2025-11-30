# TextMagic::Invoice

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The invoice ID. |  |
| **bundle** | **Integer** | Top-up amount. |  |
| **currency** | **String** | Top-up currency. |  |
| **vat** | **Float** | VAT charged (if any). |  |
| **payment_method** | **String** | Payment method description. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::Invoice.new(
  id: 1099,
  bundle: 200,
  currency: USD,
  vat: 2.0,
  payment_method: MasterCard ending in 1234
)
```

