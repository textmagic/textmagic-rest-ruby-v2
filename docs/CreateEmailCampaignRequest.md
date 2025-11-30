# TextMagic::CreateEmailCampaignRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **email_sender_id** | **Integer** | Email sender ID from your configured senders. | [optional] |
| **subject** | **String** | Email subject line. | [optional] |
| **message** | **String** | HTML email content. | [optional] |
| **from_name** | **String** | Optional custom sender name. | [optional] |
| **reply_to_email** | **String** | Optional custom reply-to email address. | [optional] |
| **recipients** | [**CreateEmailCampaignRequestRecipients**](CreateEmailCampaignRequestRecipients.md) |  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::CreateEmailCampaignRequest.new(
  email_sender_id: 123,
  subject: Special Offer - 50% Off Today Only!,
  message: &lt;html&gt;&lt;body&gt;&lt;h1&gt;Special Offer!&lt;/h1&gt;&lt;p&gt;Get 50% off all products today only!&lt;/p&gt;&lt;/body&gt;&lt;/html&gt;,
  from_name: John Smith,
  reply_to_email: support@example.com,
  recipients: null
)
```

