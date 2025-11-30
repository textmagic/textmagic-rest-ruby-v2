# TextMagic::UpdateListRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | List name. | [optional] |
| **shared** | **Boolean** | Make this list shared or not? | [optional][default to false] |
| **favorited** | **Boolean** | Is list favorited. | [optional][default to false] |
| **is_default** | **Boolean** | Is list default for new contacts (web only). | [optional][default to false] |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::UpdateListRequest.new(
  name: Private list,
  shared: true,
  favorited: true,
  is_default: true
)
```

