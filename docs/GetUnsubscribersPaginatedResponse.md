# TextMagic::GetUnsubscribersPaginatedResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** |  |  |
| **page_count** | **Integer** | The total number of pages. |  |
| **limit** | **Integer** | The number of results per page. |  |
| **resources** | [**Array&lt;UnsubscribedContact&gt;**](UnsubscribedContact.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetUnsubscribersPaginatedResponse.new(
  page: 1,
  page_count: 10,
  limit: 10,
  resources: null
)
```

