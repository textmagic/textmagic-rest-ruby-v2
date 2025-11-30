# TextMagic::EmailSenderItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Unique email sender identifier. |  |
| **domain_id** | **Integer** | ID of the associated domain. |  |
| **email** | **String** | Email address of the sender. |  |
| **created_at** | **Time** | When the email sender was created. |  |
| **domain_status** | **String** | Current verification status of the associated domain. |  |
| **from_name** | **String** | Display name for the sender. | [optional] |
| **reply_to** | **String** | Reply-to email address. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::EmailSenderItem.new(
  id: 456,
  domain_id: 123,
  email: noreply@company.com,
  created_at: 2023-12-01T10:00Z,
  domain_status: verified,
  from_name: Company Newsletter,
  reply_to: support@company.com
)
```

