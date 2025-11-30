# TextMagic::SenderId

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Numeric sender ID. |  |
| **display_time_format** | **String** | Format for representation of time. | [optional] |
| **sender_id** | **String** | Alphanumeric ID. |  |
| **user** | [**User**](User.md) |  |  |
| **status** | **String** | *   **P** for Pending - this Sender ID is being reviewed by our support team; *   **R** for Rejected - our support team rejected your application for this Sender ID; *   **A** for Active.  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::SenderId.new(
  id: 37,
  display_time_format: 24h,
  sender_id: HotRod,
  user: null,
  status: A
)
```

