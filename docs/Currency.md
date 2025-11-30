# TextMagic::Currency

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | The 3-letter ISO currency ID. |  |
| **unicode_symbol** | **String** | Unicode-compatible currency symbol. |  |
| **html_symbol** | **String** | HTML-compatible currency symbol. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::Currency.new(
  id: GBP,
  unicode_symbol: £,
  html_symbol: &amp;pound;
)
```

