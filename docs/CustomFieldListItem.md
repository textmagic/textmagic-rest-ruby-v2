# TextMagic::CustomFieldListItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Custom Field ID. |  |
| **user_custom_field_id** | **Integer** | Old property custom Field ID. |  |
| **name** | **String** | Custom Field name. |  |
| **value** | **String** | Custom Field value. |  |
| **created_at** | **Time** | Custom field creation time. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::CustomFieldListItem.new(
  id: 515,
  user_custom_field_id: 515,
  name: Custom name,
  value: Custom value,
  created_at: null
)
```

