# TextMagic::CreateContactInputObject

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_name** | **String** | Contact first name. | [optional] 
**last_name** | **String** | Contact last name. | [optional] 
**phone** | **String** | Phone number in [E.164 format](https://en.wikipedia.org/wiki/E.164). | [optional] 
**email** | **String** | Contact email address. | [optional] 
**company_name** | **String** | Company name. | [optional] 
**lists** | **String** | Contact [list](https://docs.textmagic.com/#tag/Lists) ID. Each contact must be assigned to at least one list. | [optional] 
**favorited** | **BOOLEAN** | Is the contact marked as favorite? | [optional] 
**blocked** | **BOOLEAN** | Is the contact blocked for outgoing and incoming messaging? | [optional] 
**type** | **Integer** | Force type of phone. Possible values: 0 is landline; 1 is mobile; default is -1 (auto-detection). | [optional] 
**custom_field_values** | [**Array&lt;CustomFieldListItem&gt;**](CustomFieldListItem.md) |  | [optional] 
**local** | **Integer** | Treat phone numbers passed in the request body as local. | [optional] 
**country** | **String** | The 2-letter ISO country code for local phone numbers, used when local is  set to true. Default is the account country. | [optional] 


