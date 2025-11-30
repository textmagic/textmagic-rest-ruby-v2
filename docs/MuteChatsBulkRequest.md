# TextMagic::MuteChatsBulkRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ids** | **String** | Entity ID(s), separated by comma. | [optional] |
| **all** | **Boolean** | Entity ID(s), separated by comma | [optional] |
| **_for** | **Integer** | Mute for N hours. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MuteChatsBulkRequest.new(
  ids: 1,2,3,
  all: false,
  _for: 1
)
```

