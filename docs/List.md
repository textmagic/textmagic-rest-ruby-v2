# TextMagic::List

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | List ID. |  |
| **name** | **String** | List name. |  |
| **description** | **String** | Description of the list. |  |
| **favorited** | **Boolean** | Is the List favorited? See [Favorites list](https://docs.textmagic.com/#operation/getFavourites). |  |
| **members_count** | **Integer** | List members count. |  |
| **user** | [**User**](User.md) |  |  |
| **service** | **Boolean** | Internal service field. |  |
| **shared** | **Boolean** | Is the list **shared** among all sub-accounts? |  |
| **avatar** | [**ListImage**](ListImage.md) |  |  |
| **is_default** | **Boolean** | Indicates that List is used as a default. All new contacts added via the Web-app will be added in this List by default. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::List.new(
  id: 715,
  name: Private list,
  description: Private contacts of C. R. Conway,
  favorited: false,
  members_count: 332,
  user: null,
  service: null,
  shared: false,
  avatar: null,
  is_default: null
)
```

