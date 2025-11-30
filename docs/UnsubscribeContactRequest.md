# TextMagic::UnsubscribeContactRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **phone** | **String** | Contact phone number. | [optional] |
| **block_incoming** | **Integer** | If set to 1, incoming messages from this number will be blocked. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UnsubscribeContactRequest.new(
  phone: 447860021130,
  block_incoming: 0
)
```

