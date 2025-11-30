# TextMagic::GetMessageSessionStatResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **failed** | **Integer** | Amount of failed messages. |  |
| **delivered** | **Integer** | Amount of delivered messages. |  |
| **accepted** | **Integer** | Amount of accepted messages. |  |
| **rejected** | **Integer** | Amount of rejected messages. |  |
| **scheduled** | **Integer** | Amount of scheduled messages. |  |
| **all** | **Integer** | Total amount of messages. |  |
| **sent** | **Integer** | Amount of sent but not yet delivered messages. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetMessageSessionStatResponse.new(
  failed: 12,
  delivered: 99,
  accepted: 75,
  rejected: 12,
  scheduled: 0,
  all: 1,
  sent: 1
)
```

