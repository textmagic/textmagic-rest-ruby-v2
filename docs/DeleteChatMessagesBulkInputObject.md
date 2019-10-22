# TextMagic::DeleteChatMessagesBulkInputObject

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inbound_ids** | **String** | Inbound messages ID(s) to delete. Require when \&quot;all\&quot; equal to 0 (false). | [optional] 
**sent_ids** | **String** | Sent messages ID(s) to delete. Require when \&quot;all\&quot; equal to 0 (false). | [optional] 
**calls_ids** | **String** | Calls ID(s) to delete. Require when \&quot;all\&quot; equal to 0 (false). | [optional] 
**all** | **BOOLEAN** | Default is 0 (false). If set to 1 all the entities will be removed. | [optional] 


