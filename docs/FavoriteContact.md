# TextMagic::FavoriteContact

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **entity_id** | **Integer** | List or Contact ID. |  |
| **entity_type** | **String** | Entity type which should be marked as **favorite**. |  |
| **primary_label** | **String** | Contact first name/last name if entityType is **contact**; List name if entity type is **list**. |  |
| **secondary_label** | **String** | Phone number if entityType is **contact**; List contacts number if entity type is **list**. |  |
| **tertiary_label** | **String** | Contact country if entityType is **contact**; else, null. |  |
| **avatar** | **String** |  |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::FavoriteContact.new(
  entity_id: 629,
  entity_type: contact,
  primary_label: Favorite contact name.,
  secondary_label: 45,
  tertiary_label: Australia,
  avatar: avatars/dummy_avatar.png
)
```

