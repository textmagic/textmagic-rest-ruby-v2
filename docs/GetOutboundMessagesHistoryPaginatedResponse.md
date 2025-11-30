# TextMagic::GetOutboundMessagesHistoryPaginatedResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **last_id** | **Integer** |  |  |
| **next_last_id** | **Integer** |  |  |
| **limit** | **Integer** | The number of results per page. |  |
| **resources** | [**Array&lt;MessageOut&gt;**](MessageOut.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetOutboundMessagesHistoryPaginatedResponse.new(
  last_id: 1,
  next_last_id: 1,
  limit: 10,
  resources: null
)
```

