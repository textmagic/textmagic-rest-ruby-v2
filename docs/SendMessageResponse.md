# TextMagic::SendMessageResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Message ID. | 
**href** | **String** | URI of message session. | 
**type** | **String** | Message response type: * **message** when message sent to a single recipient * **session** when message sent to multiple recipients * **schedule** when message has been scheduled for sending * **bulk** when message sent to multiple recipient and the number of recipients requires asynchronous processiong See [Sending more than 1,000 messages in one session](http://docs.textmagictesting.com/#section/Tutorials/Sending-more-than-1000-messages-in-one-session).  | 
**session_id** | **Integer** | Message session ID. | 
**bulk_id** | **Integer** | Bulk Session ID. See [Sending more than 1,000 messages in one session](http://docs.textmagictesting.com/#section/Tutorials/Sending-more-than-1000-messages-in-one-session). | 
**message_id** | **Integer** | Message ID. | 
**schedule_id** | **Integer** | Message Schedule ID. | 
**chat_id** | **Integer** | Message Chat ID. | 


