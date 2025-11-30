# TextMagic::ScheduleEmailCampaignRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **email_sender_id** | **Integer** | Email sender ID from your configured senders. | [optional] |
| **subject** | **String** | Email subject line. | [optional] |
| **message** | **String** | HTML email content. | [optional] |
| **from_name** | **String** | Optional custom sender name. | [optional] |
| **reply_to_email** | **String** | Optional custom reply-to email address. | [optional] |
| **recipients** | [**ScheduleEmailCampaignRequestRecipients**](ScheduleEmailCampaignRequestRecipients.md) |  | [optional] |
| **schedule_params** | [**ScheduleEmailCampaignRequestScheduleParams**](ScheduleEmailCampaignRequestScheduleParams.md) |  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::ScheduleEmailCampaignRequest.new(
  email_sender_id: 123,
  subject: Weekly Newsletter - Week of December 4th,
  message: &lt;html&gt;&lt;body&gt;&lt;h1&gt;This Week&#39;s Updates&lt;/h1&gt;&lt;p&gt;Here are the latest news and updates...&lt;/p&gt;&lt;/body&gt;&lt;/html&gt;,
  from_name: Newsletter Team,
  reply_to_email: newsletter@company.com,
  recipients: null,
  schedule_params: null
)
```

