# TextMagic::MessagesIcsParameters

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **text** | **String** | Scheduled message text. |  |
| **recipients** | [**MessagesIcsParametersRecipients**](MessagesIcsParametersRecipients.md) |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MessagesIcsParameters.new(
  text: I Love Textmagic!,
  recipients: null
)
```

