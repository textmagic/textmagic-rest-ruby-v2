# TextMagic::OutboundEmailResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Outbound email ID. | 
**send_time** | **DateTime** | Email send timestamp. | 
**from_name** | **String** | Sender name. | [optional] 
**from_email** | **String** | Sender email address. | 
**reply_to_email** | **String** | Reply-to email address. | 
**recipient_full_name** | **String** | Recipient&#39;s full name. | [optional] 
**recipient_email** | **String** | Recipient&#39;s email address. | [optional] 
**email_subject** | **String** | Email subject line. | 
**email_content** | **String** | HTML email content. | 
**source** | **String** | Source of the outbound email. | 
**status** | **String** | Current email status. | 
**cost** | **Float** | Cost of sending this email. | 
**status_reason** | **String** | Detailed status reason. | [optional] 
**contact_id** | **Integer** | Associated contact ID. | [optional] 
**initiator_id** | **Integer** | ID of user who initiated the email. | 


