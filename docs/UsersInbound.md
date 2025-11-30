# TextMagic::UsersInbound

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Dedicated number ID. |  |
| **display_time_format** | **String** | Format for representation of time. | [optional] |
| **phone** | **String** | Dedicated phone number. | [optional] |
| **user** | [**User**](User.md) |  |  |
| **purchased_at** | **Time** | Time when the dedicated number was purchased. |  |
| **expire_at** | **Time** | Dedicated number subscription expiration time. |  |
| **status** | **String** | Number status: *   **U** for Unused. No messages have been sent from (or received to) this number; *   **A** for Active.  |  |
| **country** | [**Country**](Country.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UsersInbound.new(
  id: 305,
  display_time_format: 24h,
  phone: 447860021130,
  user: null,
  purchased_at: null,
  expire_at: null,
  status: U,
  country: null
)
```

