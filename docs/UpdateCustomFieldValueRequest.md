# TextMagic::UpdateCustomFieldValueRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **contact_id** | **Integer** | Contact ID. See [Contact](https://docs.textmagic.com/#tag/Contacts).  | [optional] |
| **value** | **String** | Custom field value. Note that this value is not parsed in any way; it is stored and used in dynamic fields exactly as you send it. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UpdateCustomFieldValueRequest.new(
  contact_id: 50315,
  value: 1983-08-31T00:00:00.000Z
)
```

