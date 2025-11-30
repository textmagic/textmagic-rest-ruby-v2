# TextMagic::UpdateSurveyCountryItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **country** | **String** | The 2-letter ISO country code. |  |
| **user_inbound_id** | **Integer** | User inbound phone ID. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UpdateSurveyCountryItem.new(
  country: US,
  user_inbound_id: 10
)
```

