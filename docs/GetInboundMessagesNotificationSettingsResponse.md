# TextMagic::GetInboundMessagesNotificationSettingsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **inbound_message_notification** | **Boolean** | Should user receive notification about new incoming messages. |  |
| **forwarded_call_notification** | **Boolean** | Should user receive notification about new forwarded calls. |  |
| **include_sms_history** | **Boolean** | Include SMS history into notification Email. |  |
| **send_in_html_format** | **Boolean** | Send Email notification in HTML format. |  |
| **alert_email1** | **String** | New message notification email 1. |  |
| **alert_email2** | **String** | New message notification email 2. |  |
| **alert_email3** | **String** | New message notification email 3. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetInboundMessagesNotificationSettingsResponse.new(
  inbound_message_notification: true,
  forwarded_call_notification: true,
  include_sms_history: true,
  send_in_html_format: true,
  alert_email1: test@test.com,
  alert_email2: test@test.com,
  alert_email3: test@test.com
)
```

