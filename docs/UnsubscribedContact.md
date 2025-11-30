# TextMagic::UnsubscribedContact

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Unsubscribed contact ID. |  |
| **phone** | **String** | Phone number in [E.164 format](https://en.wikipedia.org/wiki/E.164). |  |
| **unsubscribe_time** | **Time** | Time when contact was opted-out. |  |
| **first_name** | **String** | Unsubscribed contact first name. |  |
| **last_name** | **String** | Unsubscribed contact last name. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UnsubscribedContact.new(
  id: 27074,
  phone: 447860021130,
  unsubscribe_time: null,
  first_name: Charles,
  last_name: Conway
)
```

