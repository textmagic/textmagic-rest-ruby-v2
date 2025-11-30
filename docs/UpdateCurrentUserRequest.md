# TextMagic::UpdateCurrentUserRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **username** | **String** |  | [optional] |
| **first_name** | **String** | Account first name. | [optional] |
| **last_name** | **String** | Account last name. | [optional] |
| **email** | **String** |  | [optional] |
| **phone** | **String** |  | [optional] |
| **company** | **String** | Account company name. | [optional] |
| **timezone** | **Integer** | The timezome internal ID. See [Get timezones](https://docs.textmagic.com/#operation/getTimezones). | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UpdateCurrentUserRequest.new(
  username: Test,
  first_name: Charles,
  last_name: Conway,
  email: charles@example.com,
  phone: 447860021130,
  company: Example Ltd.,
  timezone: 2
)
```

