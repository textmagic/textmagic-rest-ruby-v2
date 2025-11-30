# TextMagic::InviteSubaccountRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **email** | **String** | The invitation email will be sent to this email address. | [optional] |
| **role** | **String** | Type of account: *   **A** for Administrator sub-account; *   **U** for Regular User.  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::InviteSubaccountRequest.new(
  email: john@example.com,
  role: U
)
```

