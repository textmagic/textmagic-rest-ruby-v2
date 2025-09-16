# TextMagic::CreateEmailCampaignResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Unique campaign ID. | 
**status** | **String** | Current campaign status. | 
**email_sender_id** | **Integer** | Email sender ID used for this campaign. | [optional] 
**start_at** | **DateTime** | Campaign start timestamp. | 
**created_by** | [**UserPersonalInfo**](UserPersonalInfo.md) |  | 
**from_name** | **String** | Sender name displayed in recipient&#39;s inbox. | [optional] 
**from_email** | **String** | Sender email address. | 
**reply_to_email** | **String** | Reply-to email address. | 
**subject** | **String** | Email subject line. | 
**html** | **String** | HTML email content. | 
**cost** | **Float** | Total campaign cost. | 
**totals** | [**EmailCampaignStatisticTotals**](EmailCampaignStatisticTotals.md) |  | 
**outbound_email** | [**OutboundEmailResponse**](OutboundEmailResponse.md) |  | [optional] 
**failed_reason** | **String** | Reason for campaign failure if applicable. | [optional] 


