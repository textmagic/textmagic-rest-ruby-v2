# TextMagic::UpdateInboundMessagesNotificationSettingsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **inbound_message_notification** | **Boolean** | Should user receive notification about new incoming messages. | [optional] |
| **include_sms_history** | **Boolean** | Include SMS history into notification Email. | [optional] |
| **send_in_html_format** | **Boolean** | Send Email notification in HTML format. | [optional] |
| **alert_email1** | **String** | New message notification email 2. | [optional] |
| **alert_email2** | **String** | New message notification email 2. | [optional] |
| **alert_email3** | **String** | New message notification email 3. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UpdateInboundMessagesNotificationSettingsRequest.new(
  inbound_message_notification: true,
  include_sms_history: true,
  send_in_html_format: true,
  alert_email1: test@test.com,
  alert_email2: test@test.com,
  alert_email3: test@test.com
)
```

