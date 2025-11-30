# TextMagic::SetChatStatusRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Chat ID. | [optional] |
| **status** | **String** | Chat status:   * **a** - Active;   * **c** - Closed;   * **d** - Deleted.  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::SetChatStatusRequest.new(
  id: 543,
  status: null
)
```

