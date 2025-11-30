# TextMagic::OutboundEmailResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Outbound email ID. |  |
| **send_time** | **Time** | Email send timestamp. |  |
| **from_name** | **String** | Sender name. | [optional] |
| **from_email** | **String** | Sender email address. |  |
| **reply_to_email** | **String** | Reply-to email address. |  |
| **recipient_full_name** | **String** | Recipient&#39;s full name. | [optional] |
| **recipient_email** | **String** | Recipient&#39;s email address. | [optional] |
| **email_subject** | **String** | Email subject line. |  |
| **email_content** | **String** | HTML email content. |  |
| **source** | **String** | Source of the outbound email. |  |
| **status** | **String** | Current email status. |  |
| **cost** | **Float** | Cost of sending this email. |  |
| **status_reason** | **String** | Detailed status reason. | [optional] |
| **contact_id** | **Integer** | Associated contact ID. | [optional] |
| **initiator_id** | **Integer** | ID of user who initiated the email. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::OutboundEmailResponse.new(
  id: 78901,
  send_time: 2023-12-01T10:05Z,
  from_name: John Smith,
  from_email: noreply@example.com,
  reply_to_email: support@example.com,
  recipient_full_name: Jane Doe,
  recipient_email: jane.doe@example.com,
  email_subject: Special Offer - 50% Off Today Only!,
  email_content: &lt;html&gt;&lt;body&gt;&lt;h1&gt;Special Offer!&lt;/h1&gt;&lt;p&gt;Get 50% off all products today only!&lt;/p&gt;&lt;/body&gt;&lt;/html&gt;,
  source: emailCampaign,
  status: delivered,
  cost: 0.012,
  status_reason: Successfully delivered,
  contact_id: 123,
  initiator_id: 456
)
```

