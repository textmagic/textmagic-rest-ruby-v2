# TextMagic::RequestSenderIdRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **sender_id** | **String** | The Sender ID that you are applying for. *   11 characters maximum; *   Only Latin based characters and digits are allowed; *   Should contain at least 1 letter.  | [optional] |
| **explanation** | **String** | Explanation of why you need this Sender ID. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::RequestSenderIdRequest.new(
  sender_id: HotRod,
  explanation: Because it equals to my company name.
)
```

