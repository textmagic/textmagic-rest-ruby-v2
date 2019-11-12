# TextMagic::Chat

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Chat ID. | 
**original_id** | **Integer** |  | 
**phone** | **String** | Chat partner&#39;s phone number. | 
**contact** | [**Contact**](Contact.md) |  | 
**unsubscribed_contact_id** | **Integer** | If this field has a value, it means that the chat phone number has been unsubscribed from you and this value is an ID of an Unsubscribed contact entity. See [Get all unsubscribed contacts](https://docs.textmagic.com/#operation/getUnsubscribers). | 
**unread** | **Integer** | Total unread incoming messages. | 
**updated_at** | **DateTime** | Time when the last incoming message arrived at this chat. | 
**status** | **String** | Chat status:   * **a** - Active;   * **c** - Closed;   * **d** - Deleted.  | 
**mute** | **Integer** | Indicates when the chat is muted. | 
**last_message** | **String** | The last message content of a chat. | 
**direction** | **String** | Last message type: * **ci** - incoming call; * **co** - outgoing call; * **i** - incoming message; * **o** - outgoing message.  | 
**from** | **String** | If filled, the value will be used as a sender number for all outgoing messages of a chat. | 
**muted_until** | **DateTime** | Date and time until the chat will be muted. | 
**time_left_mute** | **Integer** | Time left untill the chat will be unmuted (seconds). | 
**country** | [**Country**](Country.md) |  | 


