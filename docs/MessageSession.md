# TextMagic::MessageSession

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Session ID. | 
**start_time** | **String** | Session creation time. | 
**text** | **String** | Session text. If a template was used for the session text (see [Messages: Send](http://docs.textmagictesting.com/#tag/Outbound-Messages) for details), it may contain template tags.  | 
**source** | **String** | *   **O** for TextMagic Online *   **A** for API *   **M** for TextMagic Messenger *   **E** for [Email to SMS](http://docs.textmagictesting.com/#tag/Send-Email-to-SMS) *   **X** for [Distribution lists](http://docs.textmagictesting.com/#tag/Distribution-Lists)  | 
**reference_id** | **String** | Custom reference ID (see [Messages: Send](http://docs.textmagictesting.com/#tag/Send-Email-to-SMS) for details).  | 
**price** | **Float** | Session cost (in account currency). | 
**numbers_count** | **Integer** | Session recipient count. | 
**destination** | **String** | Destination type of a Message Session: * **t** - text SMS * **s** - text to speech * **v** - voice broadcast  | 


