# TextMagic::ScheduleEmailCampaignResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **campaign** | [**ScheduledEmailCampaignDetails**](ScheduledEmailCampaignDetails.md) |  |  |
| **cost** | **Float** | Estimated cost for sending this campaign. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::ScheduleEmailCampaignResponse.new(
  campaign: null,
  cost: 12.5
)
```

