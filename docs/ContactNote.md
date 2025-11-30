# TextMagic::ContactNote

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Contact note ID. |  |
| **created_at** | **Time** | Contact note creation time. |  |
| **note** | **String** | Contact note text. |  |
| **user** | [**User**](User.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::ContactNote.new(
  id: 5,
  created_at: null,
  note: Test note,
  user: null
)
```

