# TextMagic::BulkSession

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Bulk Session ID. | 
**status** | **String** | * **n** - bulk session is just created * **w** - work in progress * **f** - failed * **c** - completed with success * **s** - suspended  | 
**items_processed** | **Integer** | Amount of messages which is already processed. | 
**items_total** | **Integer** | Total amount of messages to be processed. | 
**created_at** | **DateTime** | Creation date and time of a Bulk Session. | 
**session** | [**MessageSession**](MessageSession.md) |  | 
**text** | **String** | Message text of a Bulk Session. | 


