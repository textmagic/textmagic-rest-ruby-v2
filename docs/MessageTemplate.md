# TextMagic::MessageTemplate

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Template ID. |  |
| **name** | **String** | Template name. |  |
| **content** | **String** | Template text. May contain dynamic fields inside braces. See the [Custom fields list](https://docs.textmagic.com/#tag/Templates/Custom-fields-list-(Merge-dynamic-fields)). |  |
| **last_modified** | **Time** | Time when the template was last modified. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MessageTemplate.new(
  id: 519,
  name: Appointment reminder,
  content: Hello {First name}!,
  last_modified: null
)
```

