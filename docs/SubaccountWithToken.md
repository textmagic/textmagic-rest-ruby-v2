# TextMagic::SubaccountWithToken

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Sub-account ID. | 
**username** | **String** | Username. | 
**first_name** | **String** | Account first name. | 
**last_name** | **String** | Account last name. | 
**email** | **String** | Account Email address. | 
**status** | **String** | Current account status: * **A** for Active * **T** for Trial.  | 
**balance** | **Float** | Account balance (in account currency). | 
**phone** | **String** | Contact phone number. | 
**company** | **String** | Account company name. | 
**currency** | [**Currency**](Currency.md) |  | 
**country** | [**Country**](Country.md) |  | 
**timezone** | [**Timezone**](Timezone.md) |  | 
**subaccount_type** | **String** | Type of account: *   **A** for Administrator sub-account *   **U** for Regular User  | 
**email_accepted** | **BOOLEAN** | Is account has confirmed Email. | 
**phone_accepted** | **BOOLEAN** | Is account has confirmed Phone number. | 
**avatar** | [**UserImage**](UserImage.md) |  | 
**token** | **String** | Access token of account. | 


