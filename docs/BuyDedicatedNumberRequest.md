# TextMagic::BuyDedicatedNumberRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **phone** | **String** | Dedicated phone number. | [optional] |
| **country** | **String** | Country code phone number. | [optional] |
| **user_id** | **Integer** | Assigned dedicated number. This number will be available for this account only. You cannot transfer numbers between sub-accounts.  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::BuyDedicatedNumberRequest.new(
  phone: 447860021130,
  country: AU,
  user_id: 5501
)
```

