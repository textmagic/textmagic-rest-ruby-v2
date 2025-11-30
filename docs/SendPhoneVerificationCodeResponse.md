# TextMagic::SendPhoneVerificationCodeResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **verify_id** | **String** | The ID of a verification request. This is required to finish the verification request in the next step. |  |
| **price** | **Float** | An amount of credit which will be deducted from your account balance when this verification is successfully completed. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::SendPhoneVerificationCodeResponse.new(
  verify_id: 123e4567-e89b-12d3-a456-426655440000,
  price: 0.05
)
```

