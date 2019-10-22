# TextMagic::UpdateContactInputObject

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_name** | **String** | Contact first name | [optional] 
**last_name** | **String** | Contact last name | [optional] 
**phone** | **String** | Phone number in [E.164 format](https://en.wikipedia.org/wiki/E.164). | 
**email** | **String** | Contact email address. | [optional] 
**company_name** | **String** | Contact company name | [optional] 
**lists** | **String** | Comma-separated [list](http://docs.textmagictesting.com/#section/Lists) ID. Each contact must be assigned to at least one list. | 
**favorited** | **BOOLEAN** | Is contact marked as favorite. | [optional] 
**blocked** | **BOOLEAN** | Is contact blocked for outgoing and incoming messaging. | [optional] 
**type** | **Integer** | Force type of phone. Possible values: 0 - landline, 1 - mobile. Default is -1 (auto detection). | [optional] 
**custom_field_values** | [**Array&lt;CustomFieldListItem&gt;**](CustomFieldListItem.md) |  | [optional] 
**local** | **Integer** | Treat phone number passed in request body as **local**. | [optional] 
**country** | **String** | 2-letter ISO country code for local phone numbers, used when **local** is set to true. | [optional] 


