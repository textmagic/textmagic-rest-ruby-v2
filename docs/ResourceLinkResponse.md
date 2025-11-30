# TextMagic::ResourceLinkResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Resource ID. |  |
| **href** | **String** | A link to this resource. If you want to fetch it, just **GET** this address. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::ResourceLinkResponse.new(
  id: 515,
  href: /api/v2/entity_name/1
)
```

