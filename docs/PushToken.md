# TextMagic::PushToken

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | type of the token: * **GCM** — Google Cloud Messaging * **APN** — Apple Push Notification * **FCM** — Firebase Cloud Messaging  |  |
| **token** | **String** | Push token value. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::PushToken.new(
  type: a,
  token: 03df25c845d460bcdad7802d2vf6fc1dfde97283bf75cc993eb6dca835ea2e2
)
```

