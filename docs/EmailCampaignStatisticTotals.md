# TextMagic::EmailCampaignStatisticTotals

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **recipients** | **Integer** | Total number of recipients. |  |
| **delivered** | **Integer** | Number of emails delivered. |  |
| **rejected** | **Integer** | Number of emails rejected. |  |
| **failed** | **Integer** | Number of emails failed to send. |  |
| **opened** | **Integer** | Number of emails opened. |  |
| **clicked** | **Integer** | Number of emails with clicks. |  |
| **spam_reports** | **Integer** | Number of spam reports. |  |
| **unsubscribed** | **Integer** | Number of unsubscribes. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::EmailCampaignStatisticTotals.new(
  recipients: 1250,
  delivered: 1180,
  rejected: 20,
  failed: 50,
  opened: 590,
  clicked: 118,
  spam_reports: 2,
  unsubscribed: 5
)
```

