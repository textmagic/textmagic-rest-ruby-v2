# TextMagic::Timezone

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Internal timezone ID. |  |
| **area** | **String** | Timezone area. |  |
| **dst** | **Integer** | Is daylight saving time used in this timezone? |  |
| **offset** | **Integer** | Offset from UTC time in seconds. In this example, it is 21600/60/60&#x3D;6 hours. |  |
| **timezone** | **String** | User-friendly timezone name (with spaces replaced by underscores). |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::Timezone.new(
  id: 55,
  area: Europe,
  dst: 1,
  offset: 10800,
  timezone: Europe\/Tallinn
)
```

