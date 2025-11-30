# TextMagic::UserCustomField

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Custom field ID. |  |
| **name** | **String** | Custom field name. |  |
| **created_at** | **Time** | Custom field creation time. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UserCustomField.new(
  id: 23,
  name: DOB,
  created_at: null
)
```

