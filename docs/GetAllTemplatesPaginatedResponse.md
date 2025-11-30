# TextMagic::GetAllTemplatesPaginatedResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** |  |  |
| **page_count** | **Integer** | The total number of pages. |  |
| **limit** | **Integer** | The number of results per page. |  |
| **resources** | [**Array&lt;MessageTemplate&gt;**](MessageTemplate.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetAllTemplatesPaginatedResponse.new(
  page: 1,
  page_count: 10,
  limit: 10,
  resources: null
)
```

