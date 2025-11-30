# TextMagic::SurveySenderCountries

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **country_name** | **String** |  |  |
| **from_number** | **String** |  |  |
| **allow_dedicated** | **Boolean** | Is allowed to use a dedicated number? |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::SurveySenderCountries.new(
  id: 1,
  country_name: GB,
  from_number: 447860021130,
  allow_dedicated: true
)
```

