# TextMagic::Conversation

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** |  | 
**direction** | **String** | Message type: inbound or outbound.  | 
**sender** | **String** | Sender phone number. | 
**message_time** | **DateTime** | Time when message arrived at TextMagic. | 
**text** | **String** | Message text. | 
**receiver** | **String** | Receiver phone number. | 
**status** | **String** | Message status (for chats outbound only). See [message delivery statuses](http://docs.textmagictesting.com/#section/Delivery-status-codes) for details. | 
**first_name** | **String** | Contact first name. | 
**last_name** | **String** | Contact last name. | 
**session_id** | **Integer** | Session ID of a message. See [message sessions](http://docs.textmagictesting.com/#tag/Outbound-Message-Sessions) for details. | 


