# TextMagic::CreateListRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | List name. | [optional] |
| **shared** | **Boolean** | Should the new list be **shared** among all the sub-accounts? | [optional][default to false] |
| **favorited** | **Boolean** | Is the list favorited? Default is false. | [optional][default to false] |
| **is_default** | **Boolean** | Is the list default for new contacts (web only)? | [optional][default to false] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::CreateListRequest.new(
  name: Private list,
  shared: false,
  favorited: false,
  is_default: false
)
```

