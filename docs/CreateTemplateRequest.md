# TextMagic::CreateTemplateRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Template name. | [optional] |
| **content** | **String** | Template text. May contain dynamic fields inside braces. See [Custom fields list](https://docs.textmagic.com/#tag/Templates/Custom-fields-list-(Merge-dynamic-fields)). | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::CreateTemplateRequest.new(
  name: New template name,
  content: New template content
)
```

