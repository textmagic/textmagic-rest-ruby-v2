# TextMagic::MessageOut

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Message ID. | 
**sender** | **String** | Message sender (phone number or alphanumeric Sender ID). | [optional] 
**receiver** | **String** | Recipient&#x60;s phone number. | [optional] 
**text** | **String** |  | 
**status** | **String** | Delivery status of the message. See [message delivery statuses](http://docs.textmagictesting.com/#section/Delivery-status-codes) for details.  | 
**contact_id** | **Integer** | Recipient contact ID. | 
**session_id** | **Integer** | Message Session ID of a message. | 
**message_time** | **DateTime** | Sending time. | 
**avatar** | **String** |  | 
**deleted** | **BOOLEAN** | Indicates that the message has been deleted. | [optional] 
**charset** | **String** | Message charset. Could be: *   **ISO-8859-1** for plaintext SMS; *   **UTF-16BE** for Unicode SMS.  | 
**charset_label** | **String** | Human-readable message charset label. Could be: *   **ISO-8859-1** for plaintext SMS; *   **UTF-16BE** for Unicode SMS; *   **Voice** for voice services (Text-to-Speech or Voice Broadcast) messages.  | 
**first_name** | **String** | Contact first name. Could be substituted from your [Contacts](http://docs.textmagictesting.com/#tag/Contacts) (even if you submitted the phone number instead of the contact ID).  | 
**last_name** | **String** | Contact last name. | 
**country** | **String** | The 2-letter ISO country code of the recipient&#39;s phone number.  | 
**phone** | **String** | Receipent&#x60;s phone number. | [optional] 
**price** | **Float** | Message price. | [optional] 
**parts_count** | **Integer** | Message parts (multiples of 160 characters) count. | 
**from_email** | **String** | The user email which this message came from. For Email2SMS and Distribution Lists the messages, it is an original email address - in other cases, it is an account email address. | [optional] 
**from_number** | **String** | The Phone number used to send the SMS. | [optional] 


