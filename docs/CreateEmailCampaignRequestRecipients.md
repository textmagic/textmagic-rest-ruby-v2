# TextMagic::CreateEmailCampaignRequestRecipients

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **contact_ids** | **Array&lt;Integer&gt;** | Array of contact IDs to send to. |  |
| **emails** | **Array&lt;String&gt;** | Array of email addresses to send to. |  |
| **group_ids** | **Array&lt;Integer&gt;** | Array of group IDs to send to. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::CreateEmailCampaignRequestRecipients.new(
  contact_ids: [1, 2, 3],
  emails: [user1@example.com, user2@example.com],
  group_ids: [10, 20]
)
```

