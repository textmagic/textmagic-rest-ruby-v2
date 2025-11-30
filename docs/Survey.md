# TextMagic::Survey

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **name** | **String** |  |  |
| **status** | **String** |  |  |
| **created_at** | **Time** |  |  |
| **updated_at** | **Time** |  |  |
| **receipents** | [**Array&lt;SurveyRecipient&gt;**](SurveyRecipient.md) |  | [optional] |
| **countries** | [**Array&lt;SurveySenderCountries&gt;**](SurveySenderCountries.md) |  | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::Survey.new(
  id: 1,
  name: My test survey,
  status: null,
  created_at: null,
  updated_at: null,
  receipents: null,
  countries: null
)
```

