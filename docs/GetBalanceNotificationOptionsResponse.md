# TextMagic::GetBalanceNotificationOptionsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **_1** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_2** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_3** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_5** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_10** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_20** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_30** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_50** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_100** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_500** | **String** | Contains sign of currency in Unicode hex code. |  |
| **_1000** | **String** | Contains sign of currency in Unicode hex code. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetBalanceNotificationOptionsResponse.new(
  _1: £1.00,
  _2: £2.00,
  _3: £3.00,
  _5: £5.00,
  _10: £10.00,
  _20: £20.00,
  _30: £30.00,
  _50: £50.00,
  _100: £100.00,
  _500: £500.00,
  _1000: £1,000.00
)
```

