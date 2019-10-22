# TextMagic::MessagesIcs

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **Integer** | Schedule ID. | 
**next_send** | **DateTime** | Next send date in [ISO 8601](https://en.wikipedia.org/?title&#x3D;ISO_8601) format.  | 
**rrule** | **String** | [iCal RRULE](http://www.kanzaki.com/docs/ical/rrule.html) string.  | 
**session** | [**MessageSession**](MessageSession.md) |  | 
**last_sent** | **DateTime** | Date and time when last message has been sent. | 
**contact_name** | **String** | Aggregated contact information. If the message scheduled to be sent to a single contact, a full name will be returned here. Otherwise, a total amount contacts will be returned. | 
**parameters** | [**MessagesIcsParameters**](MessagesIcsParameters.md) |  | 
**type** | **String** |  | 
**summary** | **String** | A human-readable summary of the sending schedule. | 
**text_parameters** | [**MessagesIcsTextParameters**](MessagesIcsTextParameters.md) |  | 
**first_occurrence** | **DateTime** | First occurence date. | 
**last_occurrence** | **DateTime** | Last occurence date (could be &#x60;null&#x60; if the schedule is endless). | 
**recipients_count** | **Integer** | Amount of actual recipients. | 
**timezone** | **String** | User-friendly timezone name (with spaces replaced by underscores). | 
**completed** | **BOOLEAN** | Indicates that schedling has been completed. | 
**avatar** | **String** | A relative link to the contact avatar. | 
**created_at** | **DateTime** | Scheduling creation time. | 


