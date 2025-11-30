# TextMagic::GetCallbackSettingsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **out_url** | **String** | This URL is used to push message delivery status updates to your application. |  |
| **in_url** | **String** | This URL is used to push incoming SMS to your application. |  |
| **format** | **String** | Desired callback data format. m - multipart/form-data, u - application/x-www-form-urlencoded, j - application/json. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetCallbackSettingsResponse.new(
  out_url: http://www.mysite.com/delivery-callback.php,
  in_url: http://www.mysite.com/incoming-sms-callback.php,
  format: null
)
```

