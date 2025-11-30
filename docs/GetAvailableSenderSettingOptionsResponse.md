# TextMagic::GetAvailableSenderSettingOptionsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **dedicated** | **Array&lt;String&gt;** | Array of dedicated number strings. |  |
| **user** | **Array&lt;String&gt;** | Array of verified account phone numbers (currently only one). |  |
| **shared** | **Array&lt;String&gt;** | Array of shared number strings. |  |
| **sender_ids** | **Array&lt;String&gt;** | Array of alphanumeric sender IDs. |  |
| **user_carrier_twilio** | **Array&lt;String&gt;** | Array of alphanumeric sender IDs. |  |
| **user_carrier_vonage** | **Array&lt;String&gt;** | Array of alphanumeric sender IDs. |  |
| **user_carrier_sinch** | **Array&lt;String&gt;** | Array of alphanumeric sender IDs. |  |
| **u_carrier_bandwidth** | **Array&lt;String&gt;** | Array of alphanumeric sender IDs. | [optional] |
| **uc_twilio_sender_id** | **Array&lt;String&gt;** | Array of alphanumeric sender IDs. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::GetAvailableSenderSettingOptionsResponse.new(
  dedicated: [447860021136, 447860021137],
  user: [447860021134, 447860021135],
  shared: [447860021130, 447860021131],
  sender_ids: [447860021132, 447860021133],
  user_carrier_twilio: [447860021136, 447860021137],
  user_carrier_vonage: [447860021138, 447860021139],
  user_carrier_sinch: [447860021140, 447860021141],
  u_carrier_bandwidth: [447860021142, 447860021143],
  uc_twilio_sender_id: [TestSender1, TestSender2]
)
```

