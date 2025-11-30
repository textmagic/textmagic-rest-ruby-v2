# TextMagic::SearchScheduledMessagesPaginatedResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** |  |  |
| **page_count** | **Integer** | The total number of pages. |  |
| **limit** | **Integer** | The number of results per page. |  |
| **resources** | [**Array&lt;MessagesIcs&gt;**](MessagesIcs.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::SearchScheduledMessagesPaginatedResponse.new(
  page: 1,
  page_count: 10,
  limit: 10,
  resources: null
)
```

