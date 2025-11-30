# TextMagic::ScheduleEmailCampaignRequestScheduleParams

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **start_date_time** | **Time** | When to start sending the campaign (ISO 8601 format). |  |
| **timezone** | **String** | Timezone for the schedule (e.g., \&quot;America/New_York\&quot;). |  |
| **rrule** | **String** | RFC 5545 recurrence rule for recurring campaigns. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::ScheduleEmailCampaignRequestScheduleParams.new(
  start_date_time: 2023-12-04T09:00Z,
  timezone: America/New_York,
  rrule: FREQ&#x3D;WEEKLY;BYDAY&#x3D;MO
)
```

