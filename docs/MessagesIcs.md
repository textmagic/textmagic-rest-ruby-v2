# TextMagic::MessagesIcs

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Schedule ID. |  |
| **next_send** | **Time** | The next send date in [ISO 8601](https://en.wikipedia.org/?title&#x3D;ISO_8601) format.  |  |
| **rrule** | **String** | [iCal RRULE](http://www.kanzaki.com/docs/ical/rrule.html) string.  |  |
| **session** | [**MessageSession**](MessageSession.md) |  |  |
| **last_sent** | **Time** | The date and time when the last message was sent. |  |
| **contact_name** | **String** | Aggregated contact information. If the message was scheduled to be sent to a single contact, a full name will be returned here. Otherwise, a total amount of contacts will be returned. |  |
| **parameters** | [**MessagesIcsParameters**](MessagesIcsParameters.md) |  |  |
| **type** | **String** |  |  |
| **summary** | **String** | A human-readable summary of the sending schedule. |  |
| **text_parameters** | [**MessagesIcsTextParameters**](MessagesIcsTextParameters.md) |  |  |
| **first_occurrence** | **Time** | First occurence date. |  |
| **last_occurrence** | **Time** | Last occurence date (could be &#x60;null&#x60; if the schedule is endless). |  |
| **recipients_count** | **Integer** | Amount of actual recipients. |  |
| **timezone** | **String** | User-friendly timezone name (with spaces replaced by underscores). |  |
| **completed** | **Boolean** | Indicates that scheduling has been completed. |  |
| **avatar** | **String** | A relative link to the contact avatar. |  |
| **created_at** | **Time** | Scheduling creation time. |  |

## Example

```ruby
require 'textmagic_rest_client'

instance = TextMagic::MessagesIcs.new(
  id: 562,
  next_send: null,
  rrule: FREQ&#x3D;DAILY;INTERVAL&#x3D;2;COUNT&#x3D;5;,
  session: null,
  last_sent: null,
  contact_name: 15 recipients,
  parameters: null,
  type: once,
  summary: Every 2 weeks on Monday, Tuesday, Thursday at 10:30 (UTC+03:00),
  text_parameters: null,
  first_occurrence: null,
  last_occurrence: null,
  recipients_count: 2,
  timezone: Europe/Tallinn,
  completed: true,
  avatar: avatars/dummy_avatar.png,
  created_at: null
)
```

