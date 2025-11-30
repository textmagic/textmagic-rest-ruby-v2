# TextMagic::Conversation

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **direction** | **String** | Message type: inbound or outbound.  |  |
| **sender** | **String** | Sender phone number. |  |
| **message_time** | **Time** | Time when  the message arrived at Textmagic. |  |
| **text** | **String** | Message text. |  |
| **receiver** | **String** | Receiver&#39;s phone number. |  |
| **status** | **String** | Message status (for chats outbound only). See [message delivery statuses](https://docs.textmagic.com/#section/Delivery-status-codes) for details. |  |
| **first_name** | **String** | Contact first name. |  |
| **last_name** | **String** | Contact last name. |  |
| **session_id** | **Integer** | Session ID of a message. See [message sessions](https://docs.textmagic.com/#tag/Outbound-Message-Sessions) for details. |  |
| **initiator_id** | **Integer** | Initiator ID of a message. See [message sessions](https://docs.textmagic.com/#tag/Outbound-Message-Sessions) for details. | [optional] |
| **message_file_id** | **Integer** | Message file id. | [optional] |
| **type** | **String** | Message type. | [optional] |
| **chat_type** | **String** | Chat type. | [optional] |
| **chat_id** | **Integer** | Chat id. | [optional] |
| **is_edited** | **Boolean** |  | [optional] |
| **error_code** | **String** | Error code. | [optional] |
| **files** | **Array&lt;File&gt;** |  | [optional] |
| **payload** | [**MessagePayload**](MessagePayload.md) |  | [optional] |
| **avatar** | **String** |  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::Conversation.new(
  id: 1,
  direction: in,
  sender: 447860021130,
  message_time: null,
  text: This is a sample message,
  receiver: 447624800500,
  status: d,
  first_name: Charles,
  last_name: Conway,
  session_id: null,
  initiator_id: null,
  message_file_id: null,
  type: text,
  chat_type: text,
  chat_id: null,
  is_edited: false,
  error_code: test_error_code,
  files: null,
  payload: null,
  avatar: avatars/dummy_avatar.png
)
```

