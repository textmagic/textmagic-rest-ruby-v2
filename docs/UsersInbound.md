# TextMagic::UsersInbound

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Dedicated number ID. | 
**display_time_format** | **String** | Format for representation of time | [optional] 
**phone** | **String** | Dedicated phone number. | [optional] 
**user** | [**User**](User.md) |  | 
**purchased_at** | **DateTime** | Time when the dedicated number was purchased. | 
**expire_at** | **DateTime** | Dedicated number subscription expiration time. | 
**status** | **String** | Number status: *   **U** for Unused. No messages have been sent from (or received to) this number. *   **A** for Active.  | 
**country** | [**Country**](Country.md) |  | 


