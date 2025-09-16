# TextMagic::ScheduledEmailCampaignDetails

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Unique scheduled campaign ID. | 
**status** | **String** | Current scheduled campaign status. | 
**email_sender_id** | **Integer** | Email sender ID used for this campaign. | [optional] 
**start_at** | **DateTime** | Scheduled start timestamp (UTC). | 
**end_at** | **DateTime** | End timestamp for recurring campaigns (UTC). | [optional] 
**next_send_at** | **DateTime** | Next scheduled send timestamp (UTC). | [optional] 
**created_by** | [**UserPersonalInfo**](UserPersonalInfo.md) |  | 
**created_at** | **DateTime** | Campaign creation timestamp. | 
**updated_at** | **DateTime** | Last update timestamp. | 
**type** | **String** | Campaign recurrence type. | 
**from_name** | **String** | Sender name displayed in recipient&#39;s inbox. | [optional] 
**from_email** | **String** | Sender email address. | 
**reply_to_email** | **String** | Reply-to email address. | 
**subject** | **String** | Email subject line. | 
**html** | **String** | HTML email content. | 
**recipients_count** | **Integer** | Number of recipients for this campaign. | 
**sending_timezone** | **String** | Timezone for sending the campaign. | 
**rrule** | **String** | RFC 5545 recurrence rule for recurring campaigns. | [optional] 
**occurrence_summary** | **String** | Human-readable schedule description. | [optional] 


