# TextMagic::MessagePayload

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | Payload type. |  |
| **media_preview** | **String** | Media preview link. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MessagePayload.new(
  type: story_reply,
  media_preview: https://example.com/preview.jpg
)
```

