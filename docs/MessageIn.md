# TextMagic::MessageIn

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the inbound message. |  |
| **sender** | **String** | The sender’s phone number. |  |
| **receiver** | **String** | The receiver’s phone number (i.e. your dedicated or shared reply number). |  |
| **message_time** | **Time** | The time when the message reached the Textmagic API endpoint. |  |
| **text** | **String** | The text from the received message. |  |
| **contact_id** | **Integer** | Sender contact ID. | [optional] |
| **first_name** | **String** | Sender contact first name. | [optional] |
| **last_name** | **String** | Sender contact last name. | [optional] |
| **avatar** | **String** |  |  |
| **email** | **String** | Sender email. | [optional] |
| **contact_user_id** | **Integer** |  | [optional] |
| **user_id** | **Integer** |  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MessageIn.new(
  id: 1782832,
  sender: 447860021130,
  receiver: 447624800500,
  message_time: null,
  text: I Love Textmagic!,
  contact_id: 1,
  first_name: Charles,
  last_name: Conway,
  avatar: avatars/dummy_avatar.png,
  email: charles@example.com,
  contact_user_id: null,
  user_id: null
)
```

