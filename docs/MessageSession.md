# TextMagic::MessageSession

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Session ID. |  |
| **start_time** | **String** | Session creation time. |  |
| **text** | **String** | Session text. If a template was used for the session text (see [Messages: Send](https://docs.textmagic.com/#tag/Outbound-Messages) for details), it may contain template tags.  |  |
| **source** | **String** | *   **O** – for Textmagic Online; *   **A** – for API; *   **M** – for Textmagic Messenger; *   **E** – for [Email to SMS](https://docs.textmagic.com/#tag/Send-Email-to-SMS); *   **X** – for [Distribution Lists](https://docs.textmagic.com/#tag/Distribution-Lists).  |  |
| **reference_id** | **String** | Custom reference ID (see [Messages: Send](https://docs.textmagic.com/#tag/Send-Email-to-SMS) for details).  |  |
| **price** | **Float** | Session cost (in account currency). |  |
| **numbers_count** | **Integer** | Session recipient count. |  |
| **destination** | **String** | Destination type of a Message Session: * **t** – text SMS; * **s** – text-to-speech; * **v** – voice broadcast.  |  |
| **initiator_id** | **Integer** | Initiator ID. |  |
| **title** | **String** |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MessageSession.new(
  id: 4991,
  start_time: 2015-06-19T09:48:24+0000,
  text: Hello {First name}!,
  source: O,
  reference_id: my_reference_id_4991,
  price: 3.45,
  numbers_count: 18,
  destination: t,
  initiator_id: 305,
  title: null
)
```

