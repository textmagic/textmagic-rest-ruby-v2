# TextMagic::GetContactsAutocompleteResponseItem

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**entity_id** | **Integer** | Id of entity. 0 if object is a Reply | 
**entity_type** | **String** | Entry type: * **contact** if it is related to a contact * **list** if it is related to a contact list * **reply** if it is related to an incoming message  | 
**value** | **String** | Id of contact/list if entityType is contact/list OR phone number if entityType is reply. | 
**label** | **String** | Name of the contact/list if entityType is contact/list OR phone number if entityType is reply. | 
**shared_by** | **String** | If contact or list was shared by another sub-account then name if this user will be shown. | 
**avatar** | **String** | Contact avatar URI. | 
**favorited** | **BOOLEAN** | If contact has been marked as favorite. | 
**user_id** | **Integer** | Owner id of the contact/list (if it was shared). | 
**country_name** | **String** |  | 
**qposition** | **Integer** |  | 
**rposition** | **Integer** |  | 


