# TextMagic::DeleteChatMessagesBulkInputObject

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inbound_ids** | **String** | Inbound message IDs to delete. Require when \&quot;all\&quot; is equal to 0 (false). | [optional] 
**sent_ids** | **String** | Sent message IDs to delete. Require when \&quot;all\&quot; is equal to 0 (false). | [optional] 
**calls_ids** | **String** | Calls IDs to delete. Require when \&quot;all\&quot; is equal to 0 (false). | [optional] 
**all** | **BOOLEAN** | Default is 0 (false). If set to 1, all the entities will be removed. | [optional] 


