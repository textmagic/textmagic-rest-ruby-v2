# TextMagic::ClearAndAssignContactsToListRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **contacts** | **String** | Contact ID(s), separated by a comma or \&quot;all\&quot; to add all contacts belonging to the current user. | [optional] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::ClearAndAssignContactsToListRequest.new(
  contacts: 1,2
)
```

