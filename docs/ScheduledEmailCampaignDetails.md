# TextMagic::ScheduledEmailCampaignDetails

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Unique scheduled campaign ID. |  |
| **status** | **String** | Current scheduled campaign status. |  |
| **email_sender_id** | **Integer** | Email sender ID used for this campaign. | [optional] |
| **start_at** | **Time** | Scheduled start timestamp (UTC). |  |
| **end_at** | **Time** | End timestamp for recurring campaigns (UTC). | [optional] |
| **next_send_at** | **Time** | Next scheduled send timestamp (UTC). | [optional] |
| **created_by** | [**UserPersonalInfo**](UserPersonalInfo.md) |  |  |
| **created_at** | **Time** | Campaign creation timestamp. |  |
| **updated_at** | **Time** | Last update timestamp. |  |
| **type** | **String** | Campaign recurrence type. |  |
| **from_name** | **String** | Sender name displayed in recipient&#39;s inbox. | [optional] |
| **from_email** | **String** | Sender email address. |  |
| **reply_to_email** | **String** | Reply-to email address. |  |
| **subject** | **String** | Email subject line. |  |
| **html** | **String** | HTML email content. |  |
| **recipients_count** | **Integer** | Number of recipients for this campaign. |  |
| **sending_timezone** | **String** | Timezone for sending the campaign. |  |
| **rrule** | **String** | RFC 5545 recurrence rule for recurring campaigns. | [optional] |
| **occurrence_summary** | **String** | Human-readable schedule description. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::ScheduledEmailCampaignDetails.new(
  id: 12345,
  status: scheduled,
  email_sender_id: 123,
  start_at: 2023-12-04T14:00Z,
  end_at: 2024-12-04T14:00Z,
  next_send_at: 2023-12-04T14:00Z,
  created_by: null,
  created_at: 2023-12-01T10:30Z,
  updated_at: 2023-12-01T10:30Z,
  type: weekly,
  from_name: Newsletter Team,
  from_email: noreply@company.com,
  reply_to_email: newsletter@company.com,
  subject: Weekly Newsletter - Week of December 4th,
  html: &lt;html&gt;&lt;body&gt;&lt;h1&gt;This Week&#39;s Updates&lt;/h1&gt;&lt;p&gt;Here are the latest news and updates...&lt;/p&gt;&lt;/body&gt;&lt;/html&gt;,
  recipients_count: 1250,
  sending_timezone: America/New_York,
  rrule: FREQ&#x3D;WEEKLY;BYDAY&#x3D;MO,
  occurrence_summary: Weekly on Monday
)
```

