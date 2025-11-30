# TextMagic::GetBalanceNotificationSettingsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **low_balance_notification** | **Boolean** | Should user receive low balance notification. |  |
| **alert_balance** | **Float** | If balance is below this value, user receive low balance notification. |  |
| **alert_phone** | **String** | Low balance notification phone number. |  |
| **alert_email1** | **String** | Low balance notification email 1. |  |
| **alert_email2** | **String** | Low balance notification email 2. |  |
| **alert_email3** | **String** | Low balance notification email 3. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetBalanceNotificationSettingsResponse.new(
  low_balance_notification: true,
  alert_balance: 50.0,
  alert_phone: 447860021130,
  alert_email1: test@test.com,
  alert_email2: test@test.com,
  alert_email3: test@test.com
)
```

