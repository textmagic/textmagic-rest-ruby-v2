# TextMagic::SendMessageResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Message ID. | 
**href** | **String** | URI of the message session. | 
**type** | **String** | Message response type: * **message** – when the message is sent to a single recipient. * **session** – when the message is sent is to multiple recipients. * **schedule** - when the message is scheduled for sending. * **bulk** - when the message is sent to multiple recipients and the number of recipients requires asynchronous processing See [Sending more than 1,000 messages in one session](https://docs.textmagic.com/#section/Tutorials/Sending-more-than-1000-messages-in-one-session).  | 
**session_id** | **Integer** | Message session ID. | 
**bulk_id** | **Integer** | Bulk Session ID. See [Sending more than 1,000 messages in one session](https://docs.textmagic.com/#section/Tutorials/Sending-more-than-1000-messages-in-one-session). | 
**message_id** | **Integer** | Message ID. | 
**schedule_id** | **Integer** | Message Schedule ID. | 
**chat_id** | **Integer** | Message Chat ID. | 


