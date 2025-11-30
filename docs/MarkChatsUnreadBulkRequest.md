# TextMagic::MarkChatsUnreadBulkRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ids** | **String** | Entity ID(s), separated by comma. | [optional] |
| **all** | **Boolean** | Entity ID(s), separated by comma. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MarkChatsUnreadBulkRequest.new(
  ids: 1,2,3,
  all: false
)
```

