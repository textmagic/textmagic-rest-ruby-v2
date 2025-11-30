# TextMagic::MessageOutSession

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  | [optional] |
| **start_time** | **String** |  | [optional] |
| **text** | **String** |  | [optional] |
| **price** | **Float** |  | [optional] |
| **numbers_count** | **Integer** |  | [optional] |
| **destination** | **String** |  | [optional] |
| **source** | **String** |  | [optional] |
| **reference_id** | **String** |  | [optional] |
| **initiator_id** | **Integer** |  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MessageOutSession.new(
  id: null,
  start_time: null,
  text: null,
  price: null,
  numbers_count: null,
  destination: null,
  source: null,
  reference_id: null,
  initiator_id: null
)
```

