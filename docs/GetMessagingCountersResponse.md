# TextMagic::GetMessagingCountersResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **contacts** | **Integer** | Total contacts amount. |  |
| **sent** | **Integer** | Total sent messages amount. |  |
| **received** | **Integer** | Total received messages amount. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetMessagingCountersResponse.new(
  contacts: 10,
  sent: 10,
  received: 10
)
```

