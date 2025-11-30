# TextMagic::CreateEmailCampaignResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Unique campaign ID. |  |
| **status** | **String** | Current campaign status. |  |
| **email_sender_id** | **Integer** | Email sender ID used for this campaign. | [optional] |
| **start_at** | **Time** | Campaign start timestamp. |  |
| **created_by** | [**UserPersonalInfo**](UserPersonalInfo.md) |  |  |
| **from_name** | **String** | Sender name displayed in recipient&#39;s inbox. | [optional] |
| **from_email** | **String** | Sender email address. |  |
| **reply_to_email** | **String** | Reply-to email address. |  |
| **subject** | **String** | Email subject line. |  |
| **html** | **String** | HTML email content. |  |
| **cost** | **Float** | Total campaign cost. |  |
| **totals** | [**EmailCampaignStatisticTotals**](EmailCampaignStatisticTotals.md) |  |  |
| **outbound_email** | [**OutboundEmailResponse**](OutboundEmailResponse.md) |  | [optional] |
| **failed_reason** | **String** | Reason for campaign failure if applicable. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::CreateEmailCampaignResponse.new(
  id: 12345,
  status: in_progress,
  email_sender_id: 123,
  start_at: 2023-12-01T10:00Z,
  created_by: null,
  from_name: John Smith,
  from_email: noreply@example.com,
  reply_to_email: support@example.com,
  subject: Special Offer - 50% Off Today Only!,
  html: &lt;html&gt;&lt;body&gt;&lt;h1&gt;Special Offer!&lt;/h1&gt;&lt;p&gt;Get 50% off all products today only!&lt;/p&gt;&lt;/body&gt;&lt;/html&gt;,
  cost: 15.75,
  totals: null,
  outbound_email: null,
  failed_reason: lowBalance
)
```

