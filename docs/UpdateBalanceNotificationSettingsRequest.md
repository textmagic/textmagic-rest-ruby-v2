# TextMagic::UpdateBalanceNotificationSettingsRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **low_balance_notification** | **Boolean** | Should user receive low balance notification. | [optional] |
| **alert_balance** | **String** | If balance is below this value, user receive low balance notification. | [optional] |
| **alert_phone** | **String** | Low balance notification phone number. | [optional] |
| **alert_email1** | **String** | Low balance notification email 1. | [optional] |
| **alert_email2** | **String** | Low balance notification email 2. | [optional] |
| **alert_email3** | **String** | Low balance notification email 3. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UpdateBalanceNotificationSettingsRequest.new(
  low_balance_notification: true,
  alert_balance: 50,
  alert_phone: 15417543010,
  alert_email1: test@test.com,
  alert_email2: test@test.com,
  alert_email3: test@test.com
)
```

