# TextMagic::UpdateChatDesktopNotificationSettingsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **play_sound** | **Boolean** | Enable notification sound? | [optional] |
| **show_notifications** | **Boolean** | Show desktop notifications about new messages. | [optional] |
| **show_text** | **Boolean** | Incoming message text will be displayed in desktop notifications. | [optional] |
| **sound_id** | **Integer** | Sound Id of a notification. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UpdateChatDesktopNotificationSettingsRequest.new(
  play_sound: false,
  show_notifications: false,
  show_text: true,
  sound_id: 23
)
```

