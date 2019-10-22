# TextMagic::List

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | List ID. | 
**name** | **String** | List name. | 
**description** | **String** | Description of the list. | 
**favorited** | **BOOLEAN** | Is the List favourite? [Custom fields list](http://docs.textmagictesting.com/#operation/getFavourites). | 
**members_count** | **Integer** | List members count. | 
**user** | [**User**](User.md) |  | 
**service** | **BOOLEAN** | Internal service field. | 
**shared** | **BOOLEAN** | Is the list **shared** among all sub-accounts? | 
**avatar** | [**ListImage**](ListImage.md) |  | 
**is_default** | **BOOLEAN** | Indicates that List is used as a default. All new contacts that added via Web-app will be added in this List by default. | 


