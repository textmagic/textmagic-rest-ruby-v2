# TextMagic::DeleteChatsBulkRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ids** | **String** | Entity ID(s), separated by comma. | [optional] |
| **all** | **Boolean** | Entity ID(s), separated by comma. | [optional] |
| **status** | **String** | Default is an empty string. If set, all entities with specified status will be affected. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::DeleteChatsBulkRequest.new(
  ids: 1,2,3,
  all: false,
  status: a
)
```

