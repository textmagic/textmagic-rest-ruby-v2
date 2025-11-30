# TextMagic::PingResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | Current user Id. |  |
| **ping** | **String** | Pong. |  |
| **utc_date_time** | **String** | Current date and time. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::PingResponse.new(
  user_id: 123,
  ping: pong,
  utc_date_time: 2019-01-01T00:00:00.000Z
)
```

