# TextMagic::DeleteChatMessagesRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **inbound_ids** | **String** | Inbound message IDs to delete. Require when \&quot;all\&quot; is equal to 0 (false). | [optional] |
| **sent_ids** | **String** | Sent message IDs to delete. Require when \&quot;all\&quot; is equal to 0 (false). | [optional] |
| **calls_ids** | **String** | Calls IDs to delete. Require when \&quot;all\&quot; is equal to 0 (false). | [optional] |
| **all** | **Boolean** | Default is 0 (false). If set to 1, all the entities will be removed. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::DeleteChatMessagesRequest.new(
  inbound_ids: 1,2,3,4,
  sent_ids: 1,2,3,4,
  calls_ids: 1,2,3,4,
  all: false
)
```

