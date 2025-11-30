# TextMagic::DoAuthResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  |  |
| **token** | **String** |  |  |
| **expires** | **Time** |  |  |
| **min_versions** | [**DoAuthResponseMinVersions**](DoAuthResponseMinVersions.md) |  |  |
| **disallowed_rules** | **Array&lt;String&gt;** |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::DoAuthResponse.new(
  username: test,
  token: fPTUUKQ4Dvaq9l9ZQQgsLO1HfSR0K4,
  expires: null,
  min_versions: null,
  disallowed_rules: [SEND_MESSAGES, MAKE_CALLS, EMAIL_LOOKUP]
)
```

