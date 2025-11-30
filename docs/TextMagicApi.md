# TextMagic::TextMagicApi

All URIs are relative to *https://rest.textmagic.com*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**assign_contacts_to_list**](TextMagicApi.md#assign_contacts_to_list) | **PUT** /api/v2/lists/{id}/contacts | Assign contacts to a list |
| [**block_contact**](TextMagicApi.md#block_contact) | **POST** /api/v2/contacts/block | Block a contact by phone number |
| [**buy_dedicated_number**](TextMagicApi.md#buy_dedicated_number) | **POST** /api/v2/numbers | Buy a dedicated number |
| [**clear_and_assign_contacts_to_list**](TextMagicApi.md#clear_and_assign_contacts_to_list) | **POST** /api/v2/lists/{id}/contacts | Reset list members to the specified contacts |
| [**close_chats_bulk**](TextMagicApi.md#close_chats_bulk) | **POST** /api/v2/chats/close/bulk | Close chats (bulk) |
| [**close_read_chats**](TextMagicApi.md#close_read_chats) | **POST** /api/v2/chats/close/read | Close read chats |
| [**create_contact**](TextMagicApi.md#create_contact) | **POST** /api/v2/contacts/normalized | Add a new contact |
| [**create_contact_note**](TextMagicApi.md#create_contact_note) | **POST** /api/v2/contacts/{id}/notes | Create a new contact note |
| [**create_custom_field**](TextMagicApi.md#create_custom_field) | **POST** /api/v2/customfields | Add a new custom field |
| [**create_email_campaign**](TextMagicApi.md#create_email_campaign) | **POST** /api/v2/email-campaigns | Send email campaign |
| [**create_list**](TextMagicApi.md#create_list) | **POST** /api/v2/lists | Create a new list |
| [**create_tag**](TextMagicApi.md#create_tag) | **POST** /api/v2/tags | Create tag |
| [**create_template**](TextMagicApi.md#create_template) | **POST** /api/v2/templates | Create a template |
| [**delete_all_contacts**](TextMagicApi.md#delete_all_contacts) | **DELETE** /api/v2/contact/all | Delete contacts (bulk) |
| [**delete_all_outbound_messages**](TextMagicApi.md#delete_all_outbound_messages) | **DELETE** /api/v2/message/all | Delete all messages |
| [**delete_avatar**](TextMagicApi.md#delete_avatar) | **DELETE** /api/v2/user/avatar | Delete an avatar |
| [**delete_chat_messages**](TextMagicApi.md#delete_chat_messages) | **POST** /api/v2/chats/{id}/messages/delete | Delete chat messages by ID(s) |
| [**delete_chats_bulk**](TextMagicApi.md#delete_chats_bulk) | **POST** /api/v2/chats/delete | Delete chats (bulk) |
| [**delete_contact**](TextMagicApi.md#delete_contact) | **DELETE** /api/v2/contacts/{id} | Delete a contact |
| [**delete_contact_avatar**](TextMagicApi.md#delete_contact_avatar) | **DELETE** /api/v2/contacts/{id}/avatar | Delete an avatar |
| [**delete_contact_note**](TextMagicApi.md#delete_contact_note) | **DELETE** /api/v2/notes/{id} | Delete a contact note |
| [**delete_contact_notes_bulk**](TextMagicApi.md#delete_contact_notes_bulk) | **POST** /api/v2/contacts/{id}/notes/delete | Delete contact notes (bulk) |
| [**delete_contacts_by_ids**](TextMagicApi.md#delete_contacts_by_ids) | **POST** /api/v2/contacts/delete | Delete contacts by IDs (bulk) |
| [**delete_contacts_from_list**](TextMagicApi.md#delete_contacts_from_list) | **DELETE** /api/v2/lists/{id}/contacts | Unassign contacts from a list |
| [**delete_custom_field**](TextMagicApi.md#delete_custom_field) | **DELETE** /api/v2/customfields/{id} | Delete a custom field |
| [**delete_dedicated_number**](TextMagicApi.md#delete_dedicated_number) | **DELETE** /api/v2/numbers/{id} | Cancel a dedicated number subscription |
| [**delete_inbound_message**](TextMagicApi.md#delete_inbound_message) | **DELETE** /api/v2/replies/{id} | Delete a single inbound message |
| [**delete_inbound_messages_bulk**](TextMagicApi.md#delete_inbound_messages_bulk) | **POST** /api/v2/replies/delete | Delete inbound messages (bulk) |
| [**delete_list**](TextMagicApi.md#delete_list) | **DELETE** /api/v2/lists/{id} | Delete a list |
| [**delete_list_avatar**](TextMagicApi.md#delete_list_avatar) | **DELETE** /api/v2/lists/{id}/avatar | Delete an avatar for a list |
| [**delete_list_contacts_bulk**](TextMagicApi.md#delete_list_contacts_bulk) | **POST** /api/v2/lists/{id}/contacts/delete | Delete contacts from a list (bulk) |
| [**delete_lists_bulk**](TextMagicApi.md#delete_lists_bulk) | **POST** /api/v2/lists/delete | Delete lists (bulk) |
| [**delete_message_session**](TextMagicApi.md#delete_message_session) | **DELETE** /api/v2/sessions/{id} | Delete a session |
| [**delete_message_sessions_bulk**](TextMagicApi.md#delete_message_sessions_bulk) | **POST** /api/v2/sessions/delete | Delete sessions (bulk) |
| [**delete_outbound_message**](TextMagicApi.md#delete_outbound_message) | **DELETE** /api/v2/messages/{id} | Delete message |
| [**delete_outbound_messages_bulk**](TextMagicApi.md#delete_outbound_messages_bulk) | **POST** /api/v2/messages/delete | Delete messages (bulk) |
| [**delete_scheduled_message**](TextMagicApi.md#delete_scheduled_message) | **DELETE** /api/v2/schedules/{id} | Delete a single scheduled message |
| [**delete_scheduled_messages_bulk**](TextMagicApi.md#delete_scheduled_messages_bulk) | **POST** /api/v2/schedules/delete | Delete scheduled messages (bulk) |
| [**delete_sender_id**](TextMagicApi.md#delete_sender_id) | **DELETE** /api/v2/senderids/{id} | Delete a Sender ID |
| [**delete_template**](TextMagicApi.md#delete_template) | **DELETE** /api/v2/templates/{id} | Delete a template |
| [**delete_templates_bulk**](TextMagicApi.md#delete_templates_bulk) | **POST** /api/v2/templates/delete | Delete templates (bulk) |
| [**do_carrier_lookup**](TextMagicApi.md#do_carrier_lookup) | **GET** /api/v2/lookups/{phone} | Carrier Lookup |
| [**do_email_lookup**](TextMagicApi.md#do_email_lookup) | **GET** /api/v2/email-lookups/{email} | Email Lookup |
| [**get_all_bulk_sessions**](TextMagicApi.md#get_all_bulk_sessions) | **GET** /api/v2/bulks | Get all bulk sessions |
| [**get_all_chats**](TextMagicApi.md#get_all_chats) | **GET** /api/v2/chats | Get all chats |
| [**get_all_inbound_messages**](TextMagicApi.md#get_all_inbound_messages) | **GET** /api/v2/replies | Get all inbound messages |
| [**get_all_message_sessions**](TextMagicApi.md#get_all_message_sessions) | **GET** /api/v2/sessions | Get all sessions |
| [**get_all_outbound_messages**](TextMagicApi.md#get_all_outbound_messages) | **GET** /api/v2/messages | Get all messages |
| [**get_all_scheduled_messages**](TextMagicApi.md#get_all_scheduled_messages) | **GET** /api/v2/schedules | Get all scheduled messages |
| [**get_all_templates**](TextMagicApi.md#get_all_templates) | **GET** /api/v2/templates | Get all templates |
| [**get_available_dedicated_numbers**](TextMagicApi.md#get_available_dedicated_numbers) | **GET** /api/v2/numbers/available | Find dedicated numbers available for purchase |
| [**get_available_sender_setting_options**](TextMagicApi.md#get_available_sender_setting_options) | **GET** /api/v2/sources | Get available sender settings |
| [**get_balance_notification_options**](TextMagicApi.md#get_balance_notification_options) | **GET** /api/v2/user/notification/balance/bundles | Returns the list of available balance options which can be used as a bound to determine when to send email to user with low balance notification. See https://my.textmagic.com/online/account/notifications/balance |
| [**get_balance_notification_settings**](TextMagicApi.md#get_balance_notification_settings) | **GET** /api/v2/user/notification/balance | Get balance notification settings |
| [**get_blocked_contacts**](TextMagicApi.md#get_blocked_contacts) | **GET** /api/v2/contacts/block/list | Get blocked contacts |
| [**get_bulk_session**](TextMagicApi.md#get_bulk_session) | **GET** /api/v2/bulks/{id} | Get bulk session status |
| [**get_callback_settings**](TextMagicApi.md#get_callback_settings) | **GET** /api/v2/callback/settings | Fetch callback URL settings |
| [**get_chat**](TextMagicApi.md#get_chat) | **GET** /api/v2/chats/{id} | Get a single chat |
| [**get_chat_by_phone**](TextMagicApi.md#get_chat_by_phone) | **GET** /api/v2/chats/{phone}/by/phone | Find chats by phone |
| [**get_chat_messages**](TextMagicApi.md#get_chat_messages) | **GET** /api/v2/chats/{id}/message | Get chat messages |
| [**get_contact**](TextMagicApi.md#get_contact) | **GET** /api/v2/contacts/{id} | Get the details of a specific contact |
| [**get_contact_by_phone**](TextMagicApi.md#get_contact_by_phone) | **GET** /api/v2/contacts/phone/{phone} | Get the details of a specific contact by phone number |
| [**get_contact_if_blocked**](TextMagicApi.md#get_contact_if_blocked) | **GET** /api/v2/contacts/block/phone | Check if a phone number is blocked |
| [**get_contact_import_session_progress**](TextMagicApi.md#get_contact_import_session_progress) | **GET** /api/v2/contacts/import/progress/{id} | Check import progress |
| [**get_contact_note**](TextMagicApi.md#get_contact_note) | **GET** /api/v2/notes/{id} | Get a contact note |
| [**get_contact_notes**](TextMagicApi.md#get_contact_notes) | **GET** /api/v2/contacts/{id}/notes | Fetch notes assigned to a given contact |
| [**get_contacts**](TextMagicApi.md#get_contacts) | **GET** /api/v2/contacts | Get all contacts |
| [**get_contacts_autocomplete**](TextMagicApi.md#get_contacts_autocomplete) | **GET** /api/v2/contacts/autocomplete | Get contacts autocomplete suggestions |
| [**get_contacts_by_list_id**](TextMagicApi.md#get_contacts_by_list_id) | **GET** /api/v2/lists/{id}/contacts | Get all contacts in a list |
| [**get_countries**](TextMagicApi.md#get_countries) | **GET** /api/v2/countries | Get countries |
| [**get_current_user**](TextMagicApi.md#get_current_user) | **GET** /api/v2/user | Get current account information |
| [**get_custom_field**](TextMagicApi.md#get_custom_field) | **GET** /api/v2/customfields/{id} | Get the details of a specific custom field |
| [**get_custom_fields**](TextMagicApi.md#get_custom_fields) | **GET** /api/v2/customfields | Get all custom fields |
| [**get_dedicated_number**](TextMagicApi.md#get_dedicated_number) | **GET** /api/v2/numbers/{id} | Get the details of a specific dedicated number |
| [**get_email_senders**](TextMagicApi.md#get_email_senders) | **GET** /api/v2/email-campaigns/email-senders | Get list of email senders |
| [**get_favorites**](TextMagicApi.md#get_favorites) | **GET** /api/v2/contacts/favorite | Get favorite contacts and lists |
| [**get_inbound_message**](TextMagicApi.md#get_inbound_message) | **GET** /api/v2/replies/{id} | Get a single inbound message |
| [**get_inbound_messages_notification_settings**](TextMagicApi.md#get_inbound_messages_notification_settings) | **GET** /api/v2/user/notification/inbound | Get inbound messages notification settings |
| [**get_invoices**](TextMagicApi.md#get_invoices) | **GET** /api/v2/invoices | Get all invoices |
| [**get_list**](TextMagicApi.md#get_list) | **GET** /api/v2/lists/{id} | Get the details of a specific list |
| [**get_list_contacts_ids**](TextMagicApi.md#get_list_contacts_ids) | **GET** /api/v2/lists/{id}/contacts/ids | Get all contact IDs in a list |
| [**get_lists**](TextMagicApi.md#get_lists) | **GET** /api/v2/lists | Get all lists |
| [**get_lists_of_contact**](TextMagicApi.md#get_lists_of_contact) | **GET** /api/v2/contacts/{id}/lists | Get a contact&#39;s lists |
| [**get_message_preview**](TextMagicApi.md#get_message_preview) | **GET** /api/v2/messages/preview | Preview message |
| [**get_message_price**](TextMagicApi.md#get_message_price) | **GET** /api/v2/messages/price/normalized | Check message price |
| [**get_message_session**](TextMagicApi.md#get_message_session) | **GET** /api/v2/sessions/{id} | Get a session&#x60;s details |
| [**get_message_session_stat**](TextMagicApi.md#get_message_session_stat) | **GET** /api/v2/sessions/{id}/stat | Get a session&#x60;s statistics |
| [**get_messages_by_session_id**](TextMagicApi.md#get_messages_by_session_id) | **GET** /api/v2/sessions/{id}/messages | Get a session&#x60;s messages |
| [**get_messaging_counters**](TextMagicApi.md#get_messaging_counters) | **GET** /api/v2/stats/messaging/data | Get sent/received messages counters values |
| [**get_messaging_stat**](TextMagicApi.md#get_messaging_stat) | **GET** /api/v2/stats/messaging | Get messaging statistics |
| [**get_outbound_message**](TextMagicApi.md#get_outbound_message) | **GET** /api/v2/messages/{id} | Get a single message |
| [**get_outbound_messages_history**](TextMagicApi.md#get_outbound_messages_history) | **GET** /api/v2/history | Get history |
| [**get_scheduled_message**](TextMagicApi.md#get_scheduled_message) | **GET** /api/v2/schedules/{id} | Get a single scheduled message |
| [**get_sender_id**](TextMagicApi.md#get_sender_id) | **GET** /api/v2/senderids/{id} | Get the details of a specific Sender ID |
| [**get_sender_ids**](TextMagicApi.md#get_sender_ids) | **GET** /api/v2/senderids | Get all your approved Sender IDs |
| [**get_sender_settings**](TextMagicApi.md#get_sender_settings) | **GET** /api/v2/sender/settings/normalized | Get current sender settings |
| [**get_spending_stat**](TextMagicApi.md#get_spending_stat) | **GET** /api/v2/stats/spending | Get spending statistics |
| [**get_template**](TextMagicApi.md#get_template) | **GET** /api/v2/templates/{id} | Get a template&#x60;s details |
| [**get_timezones**](TextMagicApi.md#get_timezones) | **GET** /api/v2/timezones | Get timezones |
| [**get_unread_messages_total**](TextMagicApi.md#get_unread_messages_total) | **GET** /api/v2/chats/unread/count | Get unread messages number |
| [**get_unsubscribed_contact**](TextMagicApi.md#get_unsubscribed_contact) | **GET** /api/v2/unsubscribers/{id} | Get the details of a specific unsubscribed contact |
| [**get_unsubscribers**](TextMagicApi.md#get_unsubscribers) | **GET** /api/v2/unsubscribers | Get all unsubscribed contacts |
| [**get_user_dedicated_numbers**](TextMagicApi.md#get_user_dedicated_numbers) | **GET** /api/v2/numbers | Get all your dedicated numbers |
| [**import_contacts**](TextMagicApi.md#import_contacts) | **POST** /api/v2/contacts/import/normalized | Import contacts |
| [**mark_chats_read_bulk**](TextMagicApi.md#mark_chats_read_bulk) | **POST** /api/v2/chats/read/bulk | Mark chats as read (bulk) |
| [**mark_chats_unread_bulk**](TextMagicApi.md#mark_chats_unread_bulk) | **POST** /api/v2/chats/unread/bulk | Mark chats as unread (bulk) |
| [**mute_chat**](TextMagicApi.md#mute_chat) | **POST** /api/v2/chats/mute | Mute chat sounds |
| [**mute_chats_bulk**](TextMagicApi.md#mute_chats_bulk) | **POST** /api/v2/chats/mute/bulk | Mute chats (bulk) |
| [**ping**](TextMagicApi.md#ping) | **GET** /api/v2/ping | Ping |
| [**reopen_chats_bulk**](TextMagicApi.md#reopen_chats_bulk) | **POST** /api/v2/chats/reopen/bulk | Reopen chats (bulk) |
| [**request_sender_id**](TextMagicApi.md#request_sender_id) | **POST** /api/v2/senderids | Apply for a new Sender ID |
| [**schedule_email_campaign**](TextMagicApi.md#schedule_email_campaign) | **POST** /api/v2/email-campaigns/schedule | Schedule new email campaign |
| [**search_chats**](TextMagicApi.md#search_chats) | **GET** /api/v2/chats/search | Find chats by message text |
| [**search_chats_by_ids**](TextMagicApi.md#search_chats_by_ids) | **GET** /api/v2/chats/search/ids | Find chats (bulk) |
| [**search_chats_by_receipent**](TextMagicApi.md#search_chats_by_receipent) | **GET** /api/v2/chats/search/recipients | Find chats by recipient |
| [**search_contacts**](TextMagicApi.md#search_contacts) | **GET** /api/v2/contacts/search | Find contacts by given criteria |
| [**search_inbound_messages**](TextMagicApi.md#search_inbound_messages) | **GET** /api/v2/replies/search | Find inbound messages |
| [**search_lists**](TextMagicApi.md#search_lists) | **GET** /api/v2/lists/search | Find lists by given criteria |
| [**search_outbound_messages**](TextMagicApi.md#search_outbound_messages) | **GET** /api/v2/messages/search | Find messages |
| [**search_scheduled_messages**](TextMagicApi.md#search_scheduled_messages) | **GET** /api/v2/schedules/search | Find scheduled messages |
| [**search_templates**](TextMagicApi.md#search_templates) | **GET** /api/v2/templates/search | Find templates by criteria |
| [**send_message**](TextMagicApi.md#send_message) | **POST** /api/v2/messages | Send message |
| [**set_chat_status**](TextMagicApi.md#set_chat_status) | **POST** /api/v2/chats/status | Change chat status |
| [**unblock_contact**](TextMagicApi.md#unblock_contact) | **POST** /api/v2/contacts/unblock | Unblock a contact by phone number |
| [**unblock_contacts_bulk**](TextMagicApi.md#unblock_contacts_bulk) | **POST** /api/v2/contacts/unblock/bulk | Unblock contacts (bulk) |
| [**unmute_chats_bulk**](TextMagicApi.md#unmute_chats_bulk) | **POST** /api/v2/chats/unmute/bulk | Unmute chats (bulk) |
| [**unsubscribe_contact**](TextMagicApi.md#unsubscribe_contact) | **POST** /api/v2/unsubscribers | Manually unsubscribe a contact |
| [**update_balance_notification_settings**](TextMagicApi.md#update_balance_notification_settings) | **PUT** /api/v2/user/notification/balance | Update balance notification settings |
| [**update_callback_settings**](TextMagicApi.md#update_callback_settings) | **PUT** /api/v2/callback/settings | Update callback URL settings |
| [**update_chat_desktop_notification_settings**](TextMagicApi.md#update_chat_desktop_notification_settings) | **PUT** /api/v2/user/desktop/notification | Update chat desktop notification settings |
| [**update_contact**](TextMagicApi.md#update_contact) | **PUT** /api/v2/contacts/{id}/normalized | Edit a contact |
| [**update_contact_note**](TextMagicApi.md#update_contact_note) | **PUT** /api/v2/notes/{id} | Update a contact note |
| [**update_current_user**](TextMagicApi.md#update_current_user) | **PUT** /api/v2/user | Edit current account info |
| [**update_custom_field**](TextMagicApi.md#update_custom_field) | **PUT** /api/v2/customfields/{id} | Edit a custom field |
| [**update_custom_field_value**](TextMagicApi.md#update_custom_field_value) | **PUT** /api/v2/customfields/{id}/update | Edit the custom field value of a specified contact |
| [**update_inbound_messages_notification_settings**](TextMagicApi.md#update_inbound_messages_notification_settings) | **PUT** /api/v2/user/notification/inbound | Update inbound messages notification settings |
| [**update_list**](TextMagicApi.md#update_list) | **PUT** /api/v2/lists/{id} | Edit a list |
| [**update_sender_setting**](TextMagicApi.md#update_sender_setting) | **PUT** /api/v2/sender/settings | Change sender settings |
| [**update_template**](TextMagicApi.md#update_template) | **PUT** /api/v2/templates/{id} | Update a template |
| [**upload_avatar**](TextMagicApi.md#upload_avatar) | **POST** /api/v2/user/avatar | Upload an avatar |
| [**upload_contact_avatar**](TextMagicApi.md#upload_contact_avatar) | **POST** /api/v2/contacts/{id}/avatar | Upload an avatar |
| [**upload_list_avatar**](TextMagicApi.md#upload_list_avatar) | **POST** /api/v2/lists/{id}/avatar | Add an avatar for a list |
| [**upload_message_attachment**](TextMagicApi.md#upload_message_attachment) | **POST** /api/v2/messages/attachment | Upload message attachment |
| [**upload_message_mms_attachment**](TextMagicApi.md#upload_message_mms_attachment) | **POST** /api/v2/messages/mms/attachment | Upload message mms attachment |


## assign_contacts_to_list

> <ResourceLinkResponse> assign_contacts_to_list(id, assign_contacts_to_list_input_object)

Assign contacts to a list

> Unlike all other PUT requests, this command does not need old contact IDs to be submitted. For example, if you have a list with contacts 150, 151 and 152 and you want to add contact ID 153, you only need to submit 153 as a parameter of PUT /api/v2/lists/{id}/contacts. 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
assign_contacts_to_list_input_object = TextMagic::AssignContactsToListRequest.new # AssignContactsToListRequest | 

begin
  # Assign contacts to a list
  result = api_instance.assign_contacts_to_list(id, assign_contacts_to_list_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->assign_contacts_to_list: #{e}"
end
```

#### Using the assign_contacts_to_list_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> assign_contacts_to_list_with_http_info(id, assign_contacts_to_list_input_object)

```ruby
begin
  # Assign contacts to a list
  data, status_code, headers = api_instance.assign_contacts_to_list_with_http_info(id, assign_contacts_to_list_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->assign_contacts_to_list_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **assign_contacts_to_list_input_object** | [**AssignContactsToListRequest**](AssignContactsToListRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## block_contact

> <ResourceLinkResponse> block_contact(block_contact_input_object)

Block a contact by phone number

Block a contact from inbound and outbound communication by phone number.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
block_contact_input_object = TextMagic::BlockContactRequest.new # BlockContactRequest | 

begin
  # Block a contact by phone number
  result = api_instance.block_contact(block_contact_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->block_contact: #{e}"
end
```

#### Using the block_contact_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> block_contact_with_http_info(block_contact_input_object)

```ruby
begin
  # Block a contact by phone number
  data, status_code, headers = api_instance.block_contact_with_http_info(block_contact_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->block_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **block_contact_input_object** | [**BlockContactRequest**](BlockContactRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## buy_dedicated_number

> buy_dedicated_number(buy_dedicated_number_input_object)

Buy a dedicated number

To buy a dedicated number, you first need to find an available number matching your criteria using the `/api/v2/numbers/available` command described above.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
buy_dedicated_number_input_object = TextMagic::BuyDedicatedNumberRequest.new # BuyDedicatedNumberRequest | 

begin
  # Buy a dedicated number
  api_instance.buy_dedicated_number(buy_dedicated_number_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->buy_dedicated_number: #{e}"
end
```

#### Using the buy_dedicated_number_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> buy_dedicated_number_with_http_info(buy_dedicated_number_input_object)

```ruby
begin
  # Buy a dedicated number
  data, status_code, headers = api_instance.buy_dedicated_number_with_http_info(buy_dedicated_number_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->buy_dedicated_number_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **buy_dedicated_number_input_object** | [**BuyDedicatedNumberRequest**](BuyDedicatedNumberRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## clear_and_assign_contacts_to_list

> <ResourceLinkResponse> clear_and_assign_contacts_to_list(id, clear_and_assign_contacts_to_list_input_object)

Reset list members to the specified contacts

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
clear_and_assign_contacts_to_list_input_object = TextMagic::ClearAndAssignContactsToListRequest.new # ClearAndAssignContactsToListRequest | 

begin
  # Reset list members to the specified contacts
  result = api_instance.clear_and_assign_contacts_to_list(id, clear_and_assign_contacts_to_list_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->clear_and_assign_contacts_to_list: #{e}"
end
```

#### Using the clear_and_assign_contacts_to_list_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> clear_and_assign_contacts_to_list_with_http_info(id, clear_and_assign_contacts_to_list_input_object)

```ruby
begin
  # Reset list members to the specified contacts
  data, status_code, headers = api_instance.clear_and_assign_contacts_to_list_with_http_info(id, clear_and_assign_contacts_to_list_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->clear_and_assign_contacts_to_list_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **clear_and_assign_contacts_to_list_input_object** | [**ClearAndAssignContactsToListRequest**](ClearAndAssignContactsToListRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## close_chats_bulk

> close_chats_bulk(close_chats_bulk_input_object)

Close chats (bulk)

Close chats by chat IDs or close all chats

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
close_chats_bulk_input_object = TextMagic::MarkChatsUnreadBulkRequest.new # MarkChatsUnreadBulkRequest | 

begin
  # Close chats (bulk)
  api_instance.close_chats_bulk(close_chats_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->close_chats_bulk: #{e}"
end
```

#### Using the close_chats_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> close_chats_bulk_with_http_info(close_chats_bulk_input_object)

```ruby
begin
  # Close chats (bulk)
  data, status_code, headers = api_instance.close_chats_bulk_with_http_info(close_chats_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->close_chats_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **close_chats_bulk_input_object** | [**MarkChatsUnreadBulkRequest**](MarkChatsUnreadBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## close_read_chats

> close_read_chats

Close read chats

Close all chats that have no unread messages.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Close read chats
  api_instance.close_read_chats
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->close_read_chats: #{e}"
end
```

#### Using the close_read_chats_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> close_read_chats_with_http_info

```ruby
begin
  # Close read chats
  data, status_code, headers = api_instance.close_read_chats_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->close_read_chats_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## create_contact

> <ResourceLinkResponse> create_contact(create_contact_input_object)

Add a new contact

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
create_contact_input_object = TextMagic::CreateContactRequest.new # CreateContactRequest | 

begin
  # Add a new contact
  result = api_instance.create_contact(create_contact_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_contact: #{e}"
end
```

#### Using the create_contact_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> create_contact_with_http_info(create_contact_input_object)

```ruby
begin
  # Add a new contact
  data, status_code, headers = api_instance.create_contact_with_http_info(create_contact_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **create_contact_input_object** | [**CreateContactRequest**](CreateContactRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_contact_note

> <ResourceLinkResponse> create_contact_note(id, create_contact_note_input_object)

Create a new contact note

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
create_contact_note_input_object = TextMagic::CreateContactNoteRequest.new # CreateContactNoteRequest | 

begin
  # Create a new contact note
  result = api_instance.create_contact_note(id, create_contact_note_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_contact_note: #{e}"
end
```

#### Using the create_contact_note_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> create_contact_note_with_http_info(id, create_contact_note_input_object)

```ruby
begin
  # Create a new contact note
  data, status_code, headers = api_instance.create_contact_note_with_http_info(id, create_contact_note_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_contact_note_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **create_contact_note_input_object** | [**CreateContactNoteRequest**](CreateContactNoteRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_custom_field

> <ResourceLinkResponse> create_custom_field(create_custom_field_input_object)

Add a new custom field

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
create_custom_field_input_object = TextMagic::CreateCustomFieldRequest.new # CreateCustomFieldRequest | 

begin
  # Add a new custom field
  result = api_instance.create_custom_field(create_custom_field_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_custom_field: #{e}"
end
```

#### Using the create_custom_field_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> create_custom_field_with_http_info(create_custom_field_input_object)

```ruby
begin
  # Add a new custom field
  data, status_code, headers = api_instance.create_custom_field_with_http_info(create_custom_field_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_custom_field_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **create_custom_field_input_object** | [**CreateCustomFieldRequest**](CreateCustomFieldRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_email_campaign

> <CreateEmailCampaignResponse> create_email_campaign(create_email_campaign_input_object)

Send email campaign

Creates a new email campaign and sends it to the specified recipients.  This endpoint allows you to create and immediately send an email marketing campaign to your contacts, groups, or direct email addresses. The campaign will be processed asynchronously, and you'll receive a campaign object with tracking information.  ## Request Requirements  - **Email Sender ID**: Must be a valid, configured email sender from your account - **Recipients**: At least one recipient type must be specified (contacts, groups, or emails) - **Content**: Subject and HTML message content are required - **Balance**: Sufficient account balance for the estimated campaign cost  ## Recipient Types  You can target multiple recipient types in a single campaign:  - **Contact IDs**: Send to specific contacts from your contact list - **Group IDs**: Send to all contacts within specified groups   - **Direct Emails**: Send to email addresses not in your contact list  ## Content Guidelines  - **Subject**: Maximum 998 characters, should be engaging and relevant - **Message**: HTML content supported, including images, links, and formatting - **From Name**: Optional custom sender name (max 500 characters) - **Reply-To**: Optional custom reply-to email address  ## Cost and Balance  The API automatically calculates campaign costs based on: - Total number of unique recipients across all specified groups, contacts, and emails - Your account's email pricing tier - Any additional features or premium content  If your account balance is insufficient, the request will be rejected with a low balance error.  ## Response Information  Successful campaigns return: - Campaign ID for tracking and analytics - Current campaign status and progress - Cost breakdown and recipient counts - Sender information and content preview - Statistical totals and engagement metrics  ## Error Scenarios  Common error conditions include: - **Validation Errors**: Invalid email addresses, missing required fields, or content that exceeds limits - **Insufficient Balance**: Account balance too low for campaign cost - **Invalid Recipients**: Non-existent contact/group IDs or invalid email formats - **Sender Configuration**: Invalid or unconfigured email sender ID - **No Recipients**: All recipient arrays are empty or invalid 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
create_email_campaign_input_object = TextMagic::CreateEmailCampaignRequest.new # CreateEmailCampaignRequest | 

begin
  # Send email campaign
  result = api_instance.create_email_campaign(create_email_campaign_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_email_campaign: #{e}"
end
```

#### Using the create_email_campaign_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CreateEmailCampaignResponse>, Integer, Hash)> create_email_campaign_with_http_info(create_email_campaign_input_object)

```ruby
begin
  # Send email campaign
  data, status_code, headers = api_instance.create_email_campaign_with_http_info(create_email_campaign_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CreateEmailCampaignResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_email_campaign_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **create_email_campaign_input_object** | [**CreateEmailCampaignRequest**](CreateEmailCampaignRequest.md) |  |  |

### Return type

[**CreateEmailCampaignResponse**](CreateEmailCampaignResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_list

> <ResourceLinkResponse> create_list(create_list_input_object)

Create a new list

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
create_list_input_object = TextMagic::CreateListRequest.new # CreateListRequest | 

begin
  # Create a new list
  result = api_instance.create_list(create_list_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_list: #{e}"
end
```

#### Using the create_list_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> create_list_with_http_info(create_list_input_object)

```ruby
begin
  # Create a new list
  data, status_code, headers = api_instance.create_list_with_http_info(create_list_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_list_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **create_list_input_object** | [**CreateListRequest**](CreateListRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_tag

> <CreateTagResponse> create_tag(create_tag_input_object)

Create tag

Creates a new tag for organizing and categorizing contacts.  This endpoint allows you to create a custom tag that can be used to segment and organize your contact database. Tags provide a flexible way to categorize contacts for better contact management.  ## Request Requirements  - **Title**: Required field, must be between 1 and 50 characters - **Uniqueness**: Tag titles must be unique within your account - **Authentication**: Valid API credentials required  ## Common Use Cases  Create tags for various organizational purposes:  - **Customer Types**: \"VIP Customer\", \"New Lead\", \"Active Subscriber\" - **Geographic Segments**: \"North Region\", \"Europe\", \"Local Customers\" - **Engagement Levels**: \"Highly Engaged\", \"Inactive\", \"Recent Purchase\" - **Campaign Categories**: \"Summer Promotion\", \"Newsletter Subscriber\", \"Event Attendee\" - **Custom Segments**: Any custom categorization that fits your business needs  ## Response Information  Successful tag creation returns: - **Tag ID**: Unique identifier for the newly created tag - **Title**: The tag name as provided in the request  Use the returned tag ID to assign this tag to contacts or reference it in other API operations.  ## Error Scenarios  Common error conditions include: - **Validation Errors**: Title exceeds 50 characters or is empty - **Duplicate Tag**: A tag with the same title already exists in your account - **Authentication Errors**: Invalid or missing API credentials  ## Next Steps  After creating a tag: 1. Use the tag ID to assign it to contacts via contact management endpoints 2. Reference the tag when filtering contacts 3. Manage and update tags through other Tags API endpoints 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
create_tag_input_object = TextMagic::CreateTagRequest.new # CreateTagRequest | 

begin
  # Create tag
  result = api_instance.create_tag(create_tag_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_tag: #{e}"
end
```

#### Using the create_tag_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CreateTagResponse>, Integer, Hash)> create_tag_with_http_info(create_tag_input_object)

```ruby
begin
  # Create tag
  data, status_code, headers = api_instance.create_tag_with_http_info(create_tag_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CreateTagResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_tag_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **create_tag_input_object** | [**CreateTagRequest**](CreateTagRequest.md) |  |  |

### Return type

[**CreateTagResponse**](CreateTagResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_template

> <ResourceLinkResponse> create_template(create_template_input_object)

Create a template

There are times when creating a new template makes sense (such as when targeting specific clients or improving your business strategies).  You can create new SMS templates for marketing purposes or SMS templates for business campaigns. 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
create_template_input_object = TextMagic::CreateTemplateRequest.new # CreateTemplateRequest | 

begin
  # Create a template
  result = api_instance.create_template(create_template_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_template: #{e}"
end
```

#### Using the create_template_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> create_template_with_http_info(create_template_input_object)

```ruby
begin
  # Create a template
  data, status_code, headers = api_instance.create_template_with_http_info(create_template_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->create_template_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **create_template_input_object** | [**CreateTemplateRequest**](CreateTemplateRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## delete_all_contacts

> delete_all_contacts

Delete contacts (bulk)

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Delete contacts (bulk)
  api_instance.delete_all_contacts
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_all_contacts: #{e}"
end
```

#### Using the delete_all_contacts_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_all_contacts_with_http_info

```ruby
begin
  # Delete contacts (bulk)
  data, status_code, headers = api_instance.delete_all_contacts_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_all_contacts_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## delete_all_outbound_messages

> delete_all_outbound_messages

Delete all messages

Delete all messages.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Delete all messages
  api_instance.delete_all_outbound_messages
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_all_outbound_messages: #{e}"
end
```

#### Using the delete_all_outbound_messages_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_all_outbound_messages_with_http_info

```ruby
begin
  # Delete all messages
  data, status_code, headers = api_instance.delete_all_outbound_messages_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_all_outbound_messages_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_avatar

> delete_avatar

Delete an avatar

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Delete an avatar
  api_instance.delete_avatar
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_avatar: #{e}"
end
```

#### Using the delete_avatar_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_avatar_with_http_info

```ruby
begin
  # Delete an avatar
  data, status_code, headers = api_instance.delete_avatar_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_avatar_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_chat_messages

> delete_chat_messages(id, delete_chat_messages_bulk_input_object)

Delete chat messages by ID(s)

Delete messages from chat by given message IDs.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
delete_chat_messages_bulk_input_object = TextMagic::DeleteChatMessagesRequest.new # DeleteChatMessagesRequest | 

begin
  # Delete chat messages by ID(s)
  api_instance.delete_chat_messages(id, delete_chat_messages_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_chat_messages: #{e}"
end
```

#### Using the delete_chat_messages_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_chat_messages_with_http_info(id, delete_chat_messages_bulk_input_object)

```ruby
begin
  # Delete chat messages by ID(s)
  data, status_code, headers = api_instance.delete_chat_messages_with_http_info(id, delete_chat_messages_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_chat_messages_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **delete_chat_messages_bulk_input_object** | [**DeleteChatMessagesRequest**](DeleteChatMessagesRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_chats_bulk

> delete_chats_bulk(delete_chats_bulk_input_object)

Delete chats (bulk)

Delete chats by given IDs or delete all chats.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
delete_chats_bulk_input_object = TextMagic::DeleteChatsBulkRequest.new # DeleteChatsBulkRequest | 

begin
  # Delete chats (bulk)
  api_instance.delete_chats_bulk(delete_chats_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_chats_bulk: #{e}"
end
```

#### Using the delete_chats_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_chats_bulk_with_http_info(delete_chats_bulk_input_object)

```ruby
begin
  # Delete chats (bulk)
  data, status_code, headers = api_instance.delete_chats_bulk_with_http_info(delete_chats_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_chats_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_chats_bulk_input_object** | [**DeleteChatsBulkRequest**](DeleteChatsBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_contact

> delete_contact(id)

Delete a contact

> This command removes your contact completely. If it was assigned or saved to a shared list, it will disappear from there too. If you only need to remove a contact from selected lists, use the Contact assignment command in the Lists section instead, rather than deleting the contact. 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete a contact
  api_instance.delete_contact(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contact: #{e}"
end
```

#### Using the delete_contact_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_contact_with_http_info(id)

```ruby
begin
  # Delete a contact
  data, status_code, headers = api_instance.delete_contact_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_contact_avatar

> delete_contact_avatar(id)

Delete an avatar

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete an avatar
  api_instance.delete_contact_avatar(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contact_avatar: #{e}"
end
```

#### Using the delete_contact_avatar_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_contact_avatar_with_http_info(id)

```ruby
begin
  # Delete an avatar
  data, status_code, headers = api_instance.delete_contact_avatar_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contact_avatar_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## delete_contact_note

> delete_contact_note(id)

Delete a contact note

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete a contact note
  api_instance.delete_contact_note(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contact_note: #{e}"
end
```

#### Using the delete_contact_note_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_contact_note_with_http_info(id)

```ruby
begin
  # Delete a contact note
  data, status_code, headers = api_instance.delete_contact_note_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contact_note_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_contact_notes_bulk

> delete_contact_notes_bulk(id, delete_contact_notes_bulk_input_object)

Delete contact notes (bulk)

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
delete_contact_notes_bulk_input_object = TextMagic::DeleteContactNotesBulkRequest.new # DeleteContactNotesBulkRequest | 

begin
  # Delete contact notes (bulk)
  api_instance.delete_contact_notes_bulk(id, delete_contact_notes_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contact_notes_bulk: #{e}"
end
```

#### Using the delete_contact_notes_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_contact_notes_bulk_with_http_info(id, delete_contact_notes_bulk_input_object)

```ruby
begin
  # Delete contact notes (bulk)
  data, status_code, headers = api_instance.delete_contact_notes_bulk_with_http_info(id, delete_contact_notes_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contact_notes_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **delete_contact_notes_bulk_input_object** | [**DeleteContactNotesBulkRequest**](DeleteContactNotesBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_contacts_by_ids

> delete_contacts_by_ids(delete_contacts_by_ids_input_object)

Delete contacts by IDs (bulk)

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
delete_contacts_by_ids_input_object = TextMagic::DeleteContactsByIdsRequest.new # DeleteContactsByIdsRequest | 

begin
  # Delete contacts by IDs (bulk)
  api_instance.delete_contacts_by_ids(delete_contacts_by_ids_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contacts_by_ids: #{e}"
end
```

#### Using the delete_contacts_by_ids_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_contacts_by_ids_with_http_info(delete_contacts_by_ids_input_object)

```ruby
begin
  # Delete contacts by IDs (bulk)
  data, status_code, headers = api_instance.delete_contacts_by_ids_with_http_info(delete_contacts_by_ids_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contacts_by_ids_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_contacts_by_ids_input_object** | [**DeleteContactsByIdsRequest**](DeleteContactsByIdsRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_contacts_from_list

> delete_contacts_from_list(id, delete_contacs_from_list_object)

Unassign contacts from a list

> When you remove contacts from a specific list, they will be deleted permanently, unless they are first saved in another list. 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
delete_contacs_from_list_object = TextMagic::DeleteContactsFromListRequest.new # DeleteContactsFromListRequest | 

begin
  # Unassign contacts from a list
  api_instance.delete_contacts_from_list(id, delete_contacs_from_list_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contacts_from_list: #{e}"
end
```

#### Using the delete_contacts_from_list_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_contacts_from_list_with_http_info(id, delete_contacs_from_list_object)

```ruby
begin
  # Unassign contacts from a list
  data, status_code, headers = api_instance.delete_contacts_from_list_with_http_info(id, delete_contacs_from_list_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_contacts_from_list_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **delete_contacs_from_list_object** | [**DeleteContactsFromListRequest**](DeleteContactsFromListRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_custom_field

> delete_custom_field(id)

Delete a custom field

> When a custom field is deleted, all the information that was added to contacts under this custom field will also be lost. 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete a custom field
  api_instance.delete_custom_field(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_custom_field: #{e}"
end
```

#### Using the delete_custom_field_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_custom_field_with_http_info(id)

```ruby
begin
  # Delete a custom field
  data, status_code, headers = api_instance.delete_custom_field_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_custom_field_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_dedicated_number

> delete_dedicated_number(id)

Cancel a dedicated number subscription

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Cancel a dedicated number subscription
  api_instance.delete_dedicated_number(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_dedicated_number: #{e}"
end
```

#### Using the delete_dedicated_number_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_dedicated_number_with_http_info(id)

```ruby
begin
  # Cancel a dedicated number subscription
  data, status_code, headers = api_instance.delete_dedicated_number_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_dedicated_number_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_inbound_message

> delete_inbound_message(id)

Delete a single inbound message

> Note: deleted inbound messages will disappear from TextMagic Online, chats, and any other place they are referenced.  So, be careful! 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | The unique numeric ID for the inbound message.

begin
  # Delete a single inbound message
  api_instance.delete_inbound_message(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_inbound_message: #{e}"
end
```

#### Using the delete_inbound_message_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_inbound_message_with_http_info(id)

```ruby
begin
  # Delete a single inbound message
  data, status_code, headers = api_instance.delete_inbound_message_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_inbound_message_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The unique numeric ID for the inbound message. |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_inbound_messages_bulk

> delete_inbound_messages_bulk(delete_inbound_messages_bulk_input_object)

Delete inbound messages (bulk)

> Note: deleted inbound messages will disappear from TextMagic Online, chats, and any other place they are referenced.  So, be careful! 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
delete_inbound_messages_bulk_input_object = TextMagic::DeleteListsBulkRequest.new # DeleteListsBulkRequest | 

begin
  # Delete inbound messages (bulk)
  api_instance.delete_inbound_messages_bulk(delete_inbound_messages_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_inbound_messages_bulk: #{e}"
end
```

#### Using the delete_inbound_messages_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_inbound_messages_bulk_with_http_info(delete_inbound_messages_bulk_input_object)

```ruby
begin
  # Delete inbound messages (bulk)
  data, status_code, headers = api_instance.delete_inbound_messages_bulk_with_http_info(delete_inbound_messages_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_inbound_messages_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_inbound_messages_bulk_input_object** | [**DeleteListsBulkRequest**](DeleteListsBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_list

> delete_list(id)

Delete a list

This command has no parameters. If successful, this command will return the standard delete response (204 No Content); otherwise, a standard error response will be returned.  When you delete a list, the contacts in it are deleted as well, unless they were saved in another list.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete a list
  api_instance.delete_list(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_list: #{e}"
end
```

#### Using the delete_list_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_list_with_http_info(id)

```ruby
begin
  # Delete a list
  data, status_code, headers = api_instance.delete_list_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_list_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_list_avatar

> delete_list_avatar(id)

Delete an avatar for a list

Delete an avatar for a list

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete an avatar for a list
  api_instance.delete_list_avatar(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_list_avatar: #{e}"
end
```

#### Using the delete_list_avatar_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_list_avatar_with_http_info(id)

```ruby
begin
  # Delete an avatar for a list
  data, status_code, headers = api_instance.delete_list_avatar_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_list_avatar_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## delete_list_contacts_bulk

> delete_list_contacts_bulk(id, delete_list_contacts_bulk_input_object)

Delete contacts from a list (bulk)

Delete contacts from a list (bulk)

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
delete_list_contacts_bulk_input_object = TextMagic::UnblockContactsBulkRequest.new # UnblockContactsBulkRequest | 

begin
  # Delete contacts from a list (bulk)
  api_instance.delete_list_contacts_bulk(id, delete_list_contacts_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_list_contacts_bulk: #{e}"
end
```

#### Using the delete_list_contacts_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_list_contacts_bulk_with_http_info(id, delete_list_contacts_bulk_input_object)

```ruby
begin
  # Delete contacts from a list (bulk)
  data, status_code, headers = api_instance.delete_list_contacts_bulk_with_http_info(id, delete_list_contacts_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_list_contacts_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **delete_list_contacts_bulk_input_object** | [**UnblockContactsBulkRequest**](UnblockContactsBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_lists_bulk

> delete_lists_bulk(delete_lists_bulk_input_object)

Delete lists (bulk)

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
delete_lists_bulk_input_object = TextMagic::DeleteListsBulkRequest.new # DeleteListsBulkRequest | 

begin
  # Delete lists (bulk)
  api_instance.delete_lists_bulk(delete_lists_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_lists_bulk: #{e}"
end
```

#### Using the delete_lists_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_lists_bulk_with_http_info(delete_lists_bulk_input_object)

```ruby
begin
  # Delete lists (bulk)
  data, status_code, headers = api_instance.delete_lists_bulk_with_http_info(delete_lists_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_lists_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_lists_bulk_input_object** | [**DeleteListsBulkRequest**](DeleteListsBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_message_session

> delete_message_session(id)

Delete a session

Delete a message session, together with all nested messages. > You will not be refunded for any deleted sent sessions. 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete a session
  api_instance.delete_message_session(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_message_session: #{e}"
end
```

#### Using the delete_message_session_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_message_session_with_http_info(id)

```ruby
begin
  # Delete a session
  data, status_code, headers = api_instance.delete_message_session_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_message_session_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_message_sessions_bulk

> delete_message_sessions_bulk(delete_message_sessions_bulk_input_object)

Delete sessions (bulk)

Delete message sessions, together with all nested messages, by given ID(s) or delete all message sessions.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
delete_message_sessions_bulk_input_object = TextMagic::DeleteListsBulkRequest.new # DeleteListsBulkRequest | 

begin
  # Delete sessions (bulk)
  api_instance.delete_message_sessions_bulk(delete_message_sessions_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_message_sessions_bulk: #{e}"
end
```

#### Using the delete_message_sessions_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_message_sessions_bulk_with_http_info(delete_message_sessions_bulk_input_object)

```ruby
begin
  # Delete sessions (bulk)
  data, status_code, headers = api_instance.delete_message_sessions_bulk_with_http_info(delete_message_sessions_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_message_sessions_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_message_sessions_bulk_input_object** | [**DeleteListsBulkRequest**](DeleteListsBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_outbound_message

> delete_outbound_message(id)

Delete message

Delete a single message.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete message
  api_instance.delete_outbound_message(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_outbound_message: #{e}"
end
```

#### Using the delete_outbound_message_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_outbound_message_with_http_info(id)

```ruby
begin
  # Delete message
  data, status_code, headers = api_instance.delete_outbound_message_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_outbound_message_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_outbound_messages_bulk

> delete_outbound_messages_bulk(delete_outbound_messages_bulk_input_object)

Delete messages (bulk)

Delete outbound messages by the given ID(s) or delete all outbound messages.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
delete_outbound_messages_bulk_input_object = TextMagic::DeleteOutboundMessagesBulkRequest.new # DeleteOutboundMessagesBulkRequest | 

begin
  # Delete messages (bulk)
  api_instance.delete_outbound_messages_bulk(delete_outbound_messages_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_outbound_messages_bulk: #{e}"
end
```

#### Using the delete_outbound_messages_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_outbound_messages_bulk_with_http_info(delete_outbound_messages_bulk_input_object)

```ruby
begin
  # Delete messages (bulk)
  data, status_code, headers = api_instance.delete_outbound_messages_bulk_with_http_info(delete_outbound_messages_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_outbound_messages_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_outbound_messages_bulk_input_object** | [**DeleteOutboundMessagesBulkRequest**](DeleteOutboundMessagesBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_scheduled_message

> delete_scheduled_message(id)

Delete a single scheduled message

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete a single scheduled message
  api_instance.delete_scheduled_message(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_scheduled_message: #{e}"
end
```

#### Using the delete_scheduled_message_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_scheduled_message_with_http_info(id)

```ruby
begin
  # Delete a single scheduled message
  data, status_code, headers = api_instance.delete_scheduled_message_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_scheduled_message_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_scheduled_messages_bulk

> delete_scheduled_messages_bulk(delete_scheduled_messages_bulk_input_object)

Delete scheduled messages (bulk)

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
delete_scheduled_messages_bulk_input_object = TextMagic::DeleteScheduledMessagesBulkRequest.new # DeleteScheduledMessagesBulkRequest | 

begin
  # Delete scheduled messages (bulk)
  api_instance.delete_scheduled_messages_bulk(delete_scheduled_messages_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_scheduled_messages_bulk: #{e}"
end
```

#### Using the delete_scheduled_messages_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_scheduled_messages_bulk_with_http_info(delete_scheduled_messages_bulk_input_object)

```ruby
begin
  # Delete scheduled messages (bulk)
  data, status_code, headers = api_instance.delete_scheduled_messages_bulk_with_http_info(delete_scheduled_messages_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_scheduled_messages_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_scheduled_messages_bulk_input_object** | [**DeleteScheduledMessagesBulkRequest**](DeleteScheduledMessagesBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## delete_sender_id

> delete_sender_id(id)

Delete a Sender ID

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete a Sender ID
  api_instance.delete_sender_id(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_sender_id: #{e}"
end
```

#### Using the delete_sender_id_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_sender_id_with_http_info(id)

```ruby
begin
  # Delete a Sender ID
  data, status_code, headers = api_instance.delete_sender_id_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_sender_id_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_template

> delete_template(id)

Delete a template

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Delete a template
  api_instance.delete_template(id)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_template: #{e}"
end
```

#### Using the delete_template_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_template_with_http_info(id)

```ruby
begin
  # Delete a template
  data, status_code, headers = api_instance.delete_template_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_template_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*


## delete_templates_bulk

> delete_templates_bulk(delete_templates_bulk_input_object)

Delete templates (bulk)

Delete templates by given IDs or delete all templates.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
delete_templates_bulk_input_object = TextMagic::DeleteContactNotesBulkRequest.new # DeleteContactNotesBulkRequest | 

begin
  # Delete templates (bulk)
  api_instance.delete_templates_bulk(delete_templates_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_templates_bulk: #{e}"
end
```

#### Using the delete_templates_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_templates_bulk_with_http_info(delete_templates_bulk_input_object)

```ruby
begin
  # Delete templates (bulk)
  data, status_code, headers = api_instance.delete_templates_bulk_with_http_info(delete_templates_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->delete_templates_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_templates_bulk_input_object** | [**DeleteContactNotesBulkRequest**](DeleteContactNotesBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## do_carrier_lookup

> <DoCarrierLookupResponse> do_carrier_lookup(phone, opts)

Carrier Lookup

This API call allows you to retrieve additional information about a phone number: region-specific phone number formatting, carrier, phone type (landline/mobile) and country information.  > Numbers must be checked one by one. You cannot check multiple numbers in one request.   

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
phone = '447860021130' # String | Phone number in [E.164 format](https://en.wikipedia.org/wiki/E.164) or in [National format](https://en.wikipedia.org/wiki/National_conventions_for_writing_telephone_numbers). 
opts = {
  country: 'GB' # String | This option must be specified only if the phone number is in a **[National format](https://en.wikipedia.org/wiki/National_conventions_for_writing_telephone_numbers)**. 
}

begin
  # Carrier Lookup
  result = api_instance.do_carrier_lookup(phone, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->do_carrier_lookup: #{e}"
end
```

#### Using the do_carrier_lookup_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<DoCarrierLookupResponse>, Integer, Hash)> do_carrier_lookup_with_http_info(phone, opts)

```ruby
begin
  # Carrier Lookup
  data, status_code, headers = api_instance.do_carrier_lookup_with_http_info(phone, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <DoCarrierLookupResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->do_carrier_lookup_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **phone** | **String** | Phone number in [E.164 format](https://en.wikipedia.org/wiki/E.164) or in [National format](https://en.wikipedia.org/wiki/National_conventions_for_writing_telephone_numbers).  |  |
| **country** | **String** | This option must be specified only if the phone number is in a **[National format](https://en.wikipedia.org/wiki/National_conventions_for_writing_telephone_numbers)**.  | [optional] |

### Return type

[**DoCarrierLookupResponse**](DoCarrierLookupResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## do_email_lookup

> <DoEmailLookupResponse> do_email_lookup(email)

Email Lookup

To get more details about an email address or to check whether it is a valid email or not, you can use the Email Lookup command. To upload and check emails in bulk, please use our [Web app](https://my.textmagic.com/online/email-lookup/).  This API call allows you to retrieve additional information about an email address, such as mailbox detection, syntax checks, DNS validation, deliverability status, and many more helpful values (see the table below).  > Emails must be checked one by one. You cannot check multiple emails in one request. To upload and check emails in bulk, please use our [Web app](https://my.textmagic.com/online/email-lookup/).

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
email = 'john@sample.com' # String | Email address.

begin
  # Email Lookup
  result = api_instance.do_email_lookup(email)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->do_email_lookup: #{e}"
end
```

#### Using the do_email_lookup_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<DoEmailLookupResponse>, Integer, Hash)> do_email_lookup_with_http_info(email)

```ruby
begin
  # Email Lookup
  data, status_code, headers = api_instance.do_email_lookup_with_http_info(email)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <DoEmailLookupResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->do_email_lookup_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **email** | **String** | Email address. |  |

### Return type

[**DoEmailLookupResponse**](DoEmailLookupResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_all_bulk_sessions

> <GetAllBulkSessionsPaginatedResponse> get_all_bulk_sessions(opts)

Get all bulk sessions

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56 # Integer | The number of results per page.
}

begin
  # Get all bulk sessions
  result = api_instance.get_all_bulk_sessions(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_bulk_sessions: #{e}"
end
```

#### Using the get_all_bulk_sessions_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAllBulkSessionsPaginatedResponse>, Integer, Hash)> get_all_bulk_sessions_with_http_info(opts)

```ruby
begin
  # Get all bulk sessions
  data, status_code, headers = api_instance.get_all_bulk_sessions_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAllBulkSessionsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_bulk_sessions_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |

### Return type

[**GetAllBulkSessionsPaginatedResponse**](GetAllBulkSessionsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_all_chats

> <GetAllChatsPaginatedResponse> get_all_chats(opts)

Get all chats

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  status: 'a', # String | Fetch only (a)ctive, (c)losed or (d)eleted chats.
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  order_by: 'id', # String | Order results by some field. Default is id.
  voice: 0, # Integer | Fetch results with voice calls.
  flat: 0 # Integer | Should additional contact info be included?
}

begin
  # Get all chats
  result = api_instance.get_all_chats(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_chats: #{e}"
end
```

#### Using the get_all_chats_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAllChatsPaginatedResponse>, Integer, Hash)> get_all_chats_with_http_info(opts)

```ruby
begin
  # Get all chats
  data, status_code, headers = api_instance.get_all_chats_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAllChatsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_chats_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **status** | **String** | Fetch only (a)ctive, (c)losed or (d)eleted chats. | [optional] |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **voice** | **Integer** | Fetch results with voice calls. | [optional][default to 0] |
| **flat** | **Integer** | Should additional contact info be included? | [optional][default to 0] |

### Return type

[**GetAllChatsPaginatedResponse**](GetAllChatsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_all_inbound_messages

> <GetAllInboundMessagesPaginatedResponse> get_all_inbound_messages(opts)

Get all inbound messages

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc' # String | Order direction. Default is desc.
}

begin
  # Get all inbound messages
  result = api_instance.get_all_inbound_messages(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_inbound_messages: #{e}"
end
```

#### Using the get_all_inbound_messages_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAllInboundMessagesPaginatedResponse>, Integer, Hash)> get_all_inbound_messages_with_http_info(opts)

```ruby
begin
  # Get all inbound messages
  data, status_code, headers = api_instance.get_all_inbound_messages_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAllInboundMessagesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_inbound_messages_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |

### Return type

[**GetAllInboundMessagesPaginatedResponse**](GetAllInboundMessagesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_all_message_sessions

> <GetAllMessageSessionsPaginatedResponse> get_all_message_sessions(opts)

Get all sessions

Get all message sending sessions. > This list contains all of your sessions, including those which were sent but not via API 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56 # Integer | The number of results per page.
}

begin
  # Get all sessions
  result = api_instance.get_all_message_sessions(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_message_sessions: #{e}"
end
```

#### Using the get_all_message_sessions_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAllMessageSessionsPaginatedResponse>, Integer, Hash)> get_all_message_sessions_with_http_info(opts)

```ruby
begin
  # Get all sessions
  data, status_code, headers = api_instance.get_all_message_sessions_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAllMessageSessionsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_message_sessions_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |

### Return type

[**GetAllMessageSessionsPaginatedResponse**](GetAllMessageSessionsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_all_outbound_messages

> <GetAllOutboundMessagesPaginatedResponse> get_all_outbound_messages(opts)

Get all messages

Get all user oubound messages.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  last_id: 56 # Integer | Filter results by ID, selecting all values lesser than the specified ID. Note that the \\'page\\' parameter is ignored when \\'lastId\\' is specified.
}

begin
  # Get all messages
  result = api_instance.get_all_outbound_messages(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_outbound_messages: #{e}"
end
```

#### Using the get_all_outbound_messages_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAllOutboundMessagesPaginatedResponse>, Integer, Hash)> get_all_outbound_messages_with_http_info(opts)

```ruby
begin
  # Get all messages
  data, status_code, headers = api_instance.get_all_outbound_messages_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAllOutboundMessagesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_outbound_messages_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **last_id** | **Integer** | Filter results by ID, selecting all values lesser than the specified ID. Note that the \\&#39;page\\&#39; parameter is ignored when \\&#39;lastId\\&#39; is specified. | [optional] |

### Return type

[**GetAllOutboundMessagesPaginatedResponse**](GetAllOutboundMessagesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_all_scheduled_messages

> <GetAllScheduledMessagesPaginatedResponse> get_all_scheduled_messages(opts)

Get all scheduled messages

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  status: 'a', # String | Fetch schedules with a specific status: a - actual, c - completed, x - all.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc' # String | Order direction. Default is desc.
}

begin
  # Get all scheduled messages
  result = api_instance.get_all_scheduled_messages(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_scheduled_messages: #{e}"
end
```

#### Using the get_all_scheduled_messages_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAllScheduledMessagesPaginatedResponse>, Integer, Hash)> get_all_scheduled_messages_with_http_info(opts)

```ruby
begin
  # Get all scheduled messages
  data, status_code, headers = api_instance.get_all_scheduled_messages_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAllScheduledMessagesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_scheduled_messages_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **status** | **String** | Fetch schedules with a specific status: a - actual, c - completed, x - all. | [optional][default to &#39;x&#39;] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |

### Return type

[**GetAllScheduledMessagesPaginatedResponse**](GetAllScheduledMessagesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_all_templates

> <GetAllTemplatesPaginatedResponse> get_all_templates(opts)

Get all templates

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 1, # Integer | Fetch specified results page.
  limit: 10 # Integer | The number of results per page.
}

begin
  # Get all templates
  result = api_instance.get_all_templates(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_templates: #{e}"
end
```

#### Using the get_all_templates_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAllTemplatesPaginatedResponse>, Integer, Hash)> get_all_templates_with_http_info(opts)

```ruby
begin
  # Get all templates
  data, status_code, headers = api_instance.get_all_templates_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAllTemplatesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_all_templates_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional] |
| **limit** | **Integer** | The number of results per page. | [optional] |

### Return type

[**GetAllTemplatesPaginatedResponse**](GetAllTemplatesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_available_dedicated_numbers

> <GetAvailableDedicatedNumbersResponse> get_available_dedicated_numbers(country, opts)

Find dedicated numbers available for purchase

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
country = 'GB' # String | The 2-letter dedicated number country ISO code.
opts = {
  prefix: 447155, # Integer | Desired number prefix. Should include the country code (i.e. 447 for UK phone number format). Leave blank to get all the available numbers for the specified country.
  tollfree: 0 # Integer | Should we show only tollfree numbers (tollfree available only for US).
}

begin
  # Find dedicated numbers available for purchase
  result = api_instance.get_available_dedicated_numbers(country, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_available_dedicated_numbers: #{e}"
end
```

#### Using the get_available_dedicated_numbers_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAvailableDedicatedNumbersResponse>, Integer, Hash)> get_available_dedicated_numbers_with_http_info(country, opts)

```ruby
begin
  # Find dedicated numbers available for purchase
  data, status_code, headers = api_instance.get_available_dedicated_numbers_with_http_info(country, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAvailableDedicatedNumbersResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_available_dedicated_numbers_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **country** | **String** | The 2-letter dedicated number country ISO code. |  |
| **prefix** | **Integer** | Desired number prefix. Should include the country code (i.e. 447 for UK phone number format). Leave blank to get all the available numbers for the specified country. | [optional] |
| **tollfree** | **Integer** | Should we show only tollfree numbers (tollfree available only for US). | [optional][default to 0] |

### Return type

[**GetAvailableDedicatedNumbersResponse**](GetAvailableDedicatedNumbersResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_available_sender_setting_options

> <GetAvailableSenderSettingOptionsResponse> get_available_sender_setting_options(opts)

Get available sender settings

Get all available sender setting options which can be used in the \"from\" parameter of the POST messages method.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  country: 'US' # String | The 2-letter ISO country ID. If not specified, it returns all the available sender settings.
}

begin
  # Get available sender settings
  result = api_instance.get_available_sender_setting_options(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_available_sender_setting_options: #{e}"
end
```

#### Using the get_available_sender_setting_options_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAvailableSenderSettingOptionsResponse>, Integer, Hash)> get_available_sender_setting_options_with_http_info(opts)

```ruby
begin
  # Get available sender settings
  data, status_code, headers = api_instance.get_available_sender_setting_options_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAvailableSenderSettingOptionsResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_available_sender_setting_options_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **country** | **String** | The 2-letter ISO country ID. If not specified, it returns all the available sender settings. | [optional] |

### Return type

[**GetAvailableSenderSettingOptionsResponse**](GetAvailableSenderSettingOptionsResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_balance_notification_options

> <GetBalanceNotificationOptionsResponse> get_balance_notification_options

Returns the list of available balance options which can be used as a bound to determine when to send email to user with low balance notification. See https://my.textmagic.com/online/account/notifications/balance

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Returns the list of available balance options which can be used as a bound to determine when to send email to user with low balance notification. See https://my.textmagic.com/online/account/notifications/balance
  result = api_instance.get_balance_notification_options
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_balance_notification_options: #{e}"
end
```

#### Using the get_balance_notification_options_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetBalanceNotificationOptionsResponse>, Integer, Hash)> get_balance_notification_options_with_http_info

```ruby
begin
  # Returns the list of available balance options which can be used as a bound to determine when to send email to user with low balance notification. See https://my.textmagic.com/online/account/notifications/balance
  data, status_code, headers = api_instance.get_balance_notification_options_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetBalanceNotificationOptionsResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_balance_notification_options_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**GetBalanceNotificationOptionsResponse**](GetBalanceNotificationOptionsResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_balance_notification_settings

> <GetBalanceNotificationSettingsResponse> get_balance_notification_settings

Get balance notification settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Get balance notification settings
  result = api_instance.get_balance_notification_settings
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_balance_notification_settings: #{e}"
end
```

#### Using the get_balance_notification_settings_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetBalanceNotificationSettingsResponse>, Integer, Hash)> get_balance_notification_settings_with_http_info

```ruby
begin
  # Get balance notification settings
  data, status_code, headers = api_instance.get_balance_notification_settings_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetBalanceNotificationSettingsResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_balance_notification_settings_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**GetBalanceNotificationSettingsResponse**](GetBalanceNotificationSettingsResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_blocked_contacts

> <GetBlockedContactsPaginatedResponse> get_blocked_contacts(opts)

Get blocked contacts

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  query: 'query_example', # String | Find blocked contacts by specified search query.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc' # String | Order direction. Default is desc.
}

begin
  # Get blocked contacts
  result = api_instance.get_blocked_contacts(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_blocked_contacts: #{e}"
end
```

#### Using the get_blocked_contacts_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetBlockedContactsPaginatedResponse>, Integer, Hash)> get_blocked_contacts_with_http_info(opts)

```ruby
begin
  # Get blocked contacts
  data, status_code, headers = api_instance.get_blocked_contacts_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetBlockedContactsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_blocked_contacts_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **query** | **String** | Find blocked contacts by specified search query. | [optional] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |

### Return type

[**GetBlockedContactsPaginatedResponse**](GetBlockedContactsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_bulk_session

> <BulkSession> get_bulk_session(id)

Get bulk session status

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get bulk session status
  result = api_instance.get_bulk_session(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_bulk_session: #{e}"
end
```

#### Using the get_bulk_session_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<BulkSession>, Integer, Hash)> get_bulk_session_with_http_info(id)

```ruby
begin
  # Get bulk session status
  data, status_code, headers = api_instance.get_bulk_session_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <BulkSession>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_bulk_session_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**BulkSession**](BulkSession.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_callback_settings

> <GetCallbackSettingsResponse> get_callback_settings

Fetch callback URL settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Fetch callback URL settings
  result = api_instance.get_callback_settings
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_callback_settings: #{e}"
end
```

#### Using the get_callback_settings_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCallbackSettingsResponse>, Integer, Hash)> get_callback_settings_with_http_info

```ruby
begin
  # Fetch callback URL settings
  data, status_code, headers = api_instance.get_callback_settings_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCallbackSettingsResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_callback_settings_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**GetCallbackSettingsResponse**](GetCallbackSettingsResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_chat

> <Chat> get_chat(id)

Get a single chat

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get a single chat
  result = api_instance.get_chat(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_chat: #{e}"
end
```

#### Using the get_chat_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Chat>, Integer, Hash)> get_chat_with_http_info(id)

```ruby
begin
  # Get a single chat
  data, status_code, headers = api_instance.get_chat_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Chat>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_chat_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**Chat**](Chat.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_chat_by_phone

> <Chat> get_chat_by_phone(phone, opts)

Find chats by phone

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
phone = '447860021130' # String | 
opts = {
  upsert: 0, # Integer | Create a new chat if not found.
  reopen: 0 # Integer | Reopen chat if found or do not change status.
}

begin
  # Find chats by phone
  result = api_instance.get_chat_by_phone(phone, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_chat_by_phone: #{e}"
end
```

#### Using the get_chat_by_phone_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Chat>, Integer, Hash)> get_chat_by_phone_with_http_info(phone, opts)

```ruby
begin
  # Find chats by phone
  data, status_code, headers = api_instance.get_chat_by_phone_with_http_info(phone, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Chat>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_chat_by_phone_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **phone** | **String** |  |  |
| **upsert** | **Integer** | Create a new chat if not found. | [optional][default to 0] |
| **reopen** | **Integer** | Reopen chat if found or do not change status. | [optional][default to 0] |

### Return type

[**Chat**](Chat.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_chat_messages

> <GetChatMessagesPaginatedResponse> get_chat_messages(id, opts)

Get chat messages

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  query: 'query_example', # String | Find messages by specified search query.
  start: 'start_example', # String | Return messages since specified timestamp only. Required when `end` parameter specified.
  _end: '_end_example', # String | Return messages up to specified timestamp only. Required when `start` parameter specified.
  direction: 'asc', # String | Order direction. Default is desc.
  voice: 0, # Integer | Fetch results with voice calls.
  include_notes: 0 # Integer | Fetch results with messenger notes.
}

begin
  # Get chat messages
  result = api_instance.get_chat_messages(id, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_chat_messages: #{e}"
end
```

#### Using the get_chat_messages_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetChatMessagesPaginatedResponse>, Integer, Hash)> get_chat_messages_with_http_info(id, opts)

```ruby
begin
  # Get chat messages
  data, status_code, headers = api_instance.get_chat_messages_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetChatMessagesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_chat_messages_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **query** | **String** | Find messages by specified search query. | [optional] |
| **start** | **String** | Return messages since specified timestamp only. Required when &#x60;end&#x60; parameter specified. | [optional] |
| **_end** | **String** | Return messages up to specified timestamp only. Required when &#x60;start&#x60; parameter specified. | [optional] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |
| **voice** | **Integer** | Fetch results with voice calls. | [optional][default to 0] |
| **include_notes** | **Integer** | Fetch results with messenger notes. | [optional][default to 0] |

### Return type

[**GetChatMessagesPaginatedResponse**](GetChatMessagesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contact

> <Contact> get_contact(id)

Get the details of a specific contact

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | Contact ID.

begin
  # Get the details of a specific contact
  result = api_instance.get_contact(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact: #{e}"
end
```

#### Using the get_contact_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Contact>, Integer, Hash)> get_contact_with_http_info(id)

```ruby
begin
  # Get the details of a specific contact
  data, status_code, headers = api_instance.get_contact_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Contact>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Contact ID. |  |

### Return type

[**Contact**](Contact.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contact_by_phone

> <Contact> get_contact_by_phone(phone)

Get the details of a specific contact by phone number

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
phone = '447860021130' # String | 

begin
  # Get the details of a specific contact by phone number
  result = api_instance.get_contact_by_phone(phone)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_by_phone: #{e}"
end
```

#### Using the get_contact_by_phone_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Contact>, Integer, Hash)> get_contact_by_phone_with_http_info(phone)

```ruby
begin
  # Get the details of a specific contact by phone number
  data, status_code, headers = api_instance.get_contact_by_phone_with_http_info(phone)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Contact>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_by_phone_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **phone** | **String** |  |  |

### Return type

[**Contact**](Contact.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contact_if_blocked

> <Contact> get_contact_if_blocked(phone)

Check if a phone number is blocked

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
phone = '447860021130' # String | Phone number to check.

begin
  # Check if a phone number is blocked
  result = api_instance.get_contact_if_blocked(phone)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_if_blocked: #{e}"
end
```

#### Using the get_contact_if_blocked_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Contact>, Integer, Hash)> get_contact_if_blocked_with_http_info(phone)

```ruby
begin
  # Check if a phone number is blocked
  data, status_code, headers = api_instance.get_contact_if_blocked_with_http_info(phone)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Contact>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_if_blocked_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **phone** | **String** | Phone number to check. |  |

### Return type

[**Contact**](Contact.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contact_import_session_progress

> <GetContactImportSessionProgressResponse> get_contact_import_session_progress(id)

Check import progress

Get contact import session progress.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Check import progress
  result = api_instance.get_contact_import_session_progress(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_import_session_progress: #{e}"
end
```

#### Using the get_contact_import_session_progress_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetContactImportSessionProgressResponse>, Integer, Hash)> get_contact_import_session_progress_with_http_info(id)

```ruby
begin
  # Check import progress
  data, status_code, headers = api_instance.get_contact_import_session_progress_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetContactImportSessionProgressResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_import_session_progress_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**GetContactImportSessionProgressResponse**](GetContactImportSessionProgressResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contact_note

> <ContactNote> get_contact_note(id)

Get a contact note

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get a contact note
  result = api_instance.get_contact_note(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_note: #{e}"
end
```

#### Using the get_contact_note_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ContactNote>, Integer, Hash)> get_contact_note_with_http_info(id)

```ruby
begin
  # Get a contact note
  data, status_code, headers = api_instance.get_contact_note_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ContactNote>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_note_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**ContactNote**](ContactNote.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contact_notes

> <GetContactNotesPaginatedResponse> get_contact_notes(id, opts)

Fetch notes assigned to a given contact

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56 # Integer | The number of results per page.
}

begin
  # Fetch notes assigned to a given contact
  result = api_instance.get_contact_notes(id, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_notes: #{e}"
end
```

#### Using the get_contact_notes_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetContactNotesPaginatedResponse>, Integer, Hash)> get_contact_notes_with_http_info(id, opts)

```ruby
begin
  # Fetch notes assigned to a given contact
  data, status_code, headers = api_instance.get_contact_notes_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetContactNotesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contact_notes_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |

### Return type

[**GetContactNotesPaginatedResponse**](GetContactNotesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contacts

> <GetContactsPaginatedResponse> get_contacts(opts)

Get all contacts

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  shared: 0, # Integer | Should shared contacts be included?
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc' # String | Order direction. Default is desc.
}

begin
  # Get all contacts
  result = api_instance.get_contacts(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contacts: #{e}"
end
```

#### Using the get_contacts_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetContactsPaginatedResponse>, Integer, Hash)> get_contacts_with_http_info(opts)

```ruby
begin
  # Get all contacts
  data, status_code, headers = api_instance.get_contacts_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetContactsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contacts_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **shared** | **Integer** | Should shared contacts be included? | [optional][default to 0] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |

### Return type

[**GetContactsPaginatedResponse**](GetContactsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contacts_autocomplete

> <Array<GetContactsAutocompleteResponseItem>> get_contacts_autocomplete(query, opts)

Get contacts autocomplete suggestions

Get contacts autocomplete suggestions by given search terms.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
query = 'A' # String | Find recipients by specified search query.
opts = {
  limit: 56, # Integer | The number of results per page.
  lists: 0 # Integer | Should lists be returned or not?
}

begin
  # Get contacts autocomplete suggestions
  result = api_instance.get_contacts_autocomplete(query, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contacts_autocomplete: #{e}"
end
```

#### Using the get_contacts_autocomplete_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<GetContactsAutocompleteResponseItem>>, Integer, Hash)> get_contacts_autocomplete_with_http_info(query, opts)

```ruby
begin
  # Get contacts autocomplete suggestions
  data, status_code, headers = api_instance.get_contacts_autocomplete_with_http_info(query, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<GetContactsAutocompleteResponseItem>>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contacts_autocomplete_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **query** | **String** | Find recipients by specified search query. |  |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **lists** | **Integer** | Should lists be returned or not? | [optional][default to 0] |

### Return type

[**Array&lt;GetContactsAutocompleteResponseItem&gt;**](GetContactsAutocompleteResponseItem.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_contacts_by_list_id

> <GetContactsByListIdPaginatedResponse> get_contacts_by_list_id(id, opts)

Get all contacts in a list

A useful synonym for the \"contacts/search\" command with the provided \"listId\" parameter.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | Given group ID.
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc' # String | Order direction. Default is desc.
}

begin
  # Get all contacts in a list
  result = api_instance.get_contacts_by_list_id(id, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contacts_by_list_id: #{e}"
end
```

#### Using the get_contacts_by_list_id_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetContactsByListIdPaginatedResponse>, Integer, Hash)> get_contacts_by_list_id_with_http_info(id, opts)

```ruby
begin
  # Get all contacts in a list
  data, status_code, headers = api_instance.get_contacts_by_list_id_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetContactsByListIdPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_contacts_by_list_id_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Given group ID. |  |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |

### Return type

[**GetContactsByListIdPaginatedResponse**](GetContactsByListIdPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_countries

> <Array<Country>> get_countries

Get countries

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Get countries
  result = api_instance.get_countries
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_countries: #{e}"
end
```

#### Using the get_countries_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<Country>>, Integer, Hash)> get_countries_with_http_info

```ruby
begin
  # Get countries
  data, status_code, headers = api_instance.get_countries_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<Country>>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_countries_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;Country&gt;**](Country.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_current_user

> <User> get_current_user

Get current account information

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Get current account information
  result = api_instance.get_current_user
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_current_user: #{e}"
end
```

#### Using the get_current_user_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<User>, Integer, Hash)> get_current_user_with_http_info

```ruby
begin
  # Get current account information
  data, status_code, headers = api_instance.get_current_user_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <User>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_current_user_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**User**](User.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_custom_field

> <UserCustomField> get_custom_field(id)

Get the details of a specific custom field

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get the details of a specific custom field
  result = api_instance.get_custom_field(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_custom_field: #{e}"
end
```

#### Using the get_custom_field_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<UserCustomField>, Integer, Hash)> get_custom_field_with_http_info(id)

```ruby
begin
  # Get the details of a specific custom field
  data, status_code, headers = api_instance.get_custom_field_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <UserCustomField>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_custom_field_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**UserCustomField**](UserCustomField.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_custom_fields

> <GetCustomFieldsPaginatedResponse> get_custom_fields(opts)

Get all custom fields

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56 # Integer | The number of results per page.
}

begin
  # Get all custom fields
  result = api_instance.get_custom_fields(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_custom_fields: #{e}"
end
```

#### Using the get_custom_fields_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCustomFieldsPaginatedResponse>, Integer, Hash)> get_custom_fields_with_http_info(opts)

```ruby
begin
  # Get all custom fields
  data, status_code, headers = api_instance.get_custom_fields_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCustomFieldsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_custom_fields_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |

### Return type

[**GetCustomFieldsPaginatedResponse**](GetCustomFieldsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_dedicated_number

> <UsersInbound> get_dedicated_number(id)

Get the details of a specific dedicated number

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get the details of a specific dedicated number
  result = api_instance.get_dedicated_number(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_dedicated_number: #{e}"
end
```

#### Using the get_dedicated_number_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<UsersInbound>, Integer, Hash)> get_dedicated_number_with_http_info(id)

```ruby
begin
  # Get the details of a specific dedicated number
  data, status_code, headers = api_instance.get_dedicated_number_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <UsersInbound>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_dedicated_number_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**UsersInbound**](UsersInbound.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_email_senders

> <GetEmailSendersResponse> get_email_senders(opts)

Get list of email senders

Retrieves a list of configured email senders available for creating email campaigns.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  domain_id: 56 # Integer | Filter email senders by specific domain ID.
}

begin
  # Get list of email senders
  result = api_instance.get_email_senders(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_email_senders: #{e}"
end
```

#### Using the get_email_senders_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetEmailSendersResponse>, Integer, Hash)> get_email_senders_with_http_info(opts)

```ruby
begin
  # Get list of email senders
  data, status_code, headers = api_instance.get_email_senders_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetEmailSendersResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_email_senders_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **domain_id** | **Integer** | Filter email senders by specific domain ID. | [optional] |

### Return type

[**GetEmailSendersResponse**](GetEmailSendersResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_favorites

> <GetFavoritesPaginatedResponse> get_favorites(opts)

Get favorite contacts and lists

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  query: 'A' # String | Find contacts or lists by specified search query.
}

begin
  # Get favorite contacts and lists
  result = api_instance.get_favorites(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_favorites: #{e}"
end
```

#### Using the get_favorites_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetFavoritesPaginatedResponse>, Integer, Hash)> get_favorites_with_http_info(opts)

```ruby
begin
  # Get favorite contacts and lists
  data, status_code, headers = api_instance.get_favorites_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetFavoritesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_favorites_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **query** | **String** | Find contacts or lists by specified search query. | [optional] |

### Return type

[**GetFavoritesPaginatedResponse**](GetFavoritesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_inbound_message

> <MessageIn> get_inbound_message(id)

Get a single inbound message

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1782832 # Integer | The unique numeric ID for the inbound message.

begin
  # Get a single inbound message
  result = api_instance.get_inbound_message(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_inbound_message: #{e}"
end
```

#### Using the get_inbound_message_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<MessageIn>, Integer, Hash)> get_inbound_message_with_http_info(id)

```ruby
begin
  # Get a single inbound message
  data, status_code, headers = api_instance.get_inbound_message_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <MessageIn>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_inbound_message_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The unique numeric ID for the inbound message. |  |

### Return type

[**MessageIn**](MessageIn.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_inbound_messages_notification_settings

> <GetInboundMessagesNotificationSettingsResponse> get_inbound_messages_notification_settings

Get inbound messages notification settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Get inbound messages notification settings
  result = api_instance.get_inbound_messages_notification_settings
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_inbound_messages_notification_settings: #{e}"
end
```

#### Using the get_inbound_messages_notification_settings_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetInboundMessagesNotificationSettingsResponse>, Integer, Hash)> get_inbound_messages_notification_settings_with_http_info

```ruby
begin
  # Get inbound messages notification settings
  data, status_code, headers = api_instance.get_inbound_messages_notification_settings_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetInboundMessagesNotificationSettingsResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_inbound_messages_notification_settings_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**GetInboundMessagesNotificationSettingsResponse**](GetInboundMessagesNotificationSettingsResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_invoices

> <GetInvoicesPaginatedResponse> get_invoices(opts)

Get all invoices

With the TextMagic API, you can check the invoices and transactions for your account.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56 # Integer | The number of results per page.
}

begin
  # Get all invoices
  result = api_instance.get_invoices(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_invoices: #{e}"
end
```

#### Using the get_invoices_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetInvoicesPaginatedResponse>, Integer, Hash)> get_invoices_with_http_info(opts)

```ruby
begin
  # Get all invoices
  data, status_code, headers = api_instance.get_invoices_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetInvoicesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_invoices_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |

### Return type

[**GetInvoicesPaginatedResponse**](GetInvoicesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_list

> Array get_list(id)

Get the details of a specific list

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get the details of a specific list
  result = api_instance.get_list(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_list: #{e}"
end
```

#### Using the get_list_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(Array, Integer, Hash)> get_list_with_http_info(id)

```ruby
begin
  # Get the details of a specific list
  data, status_code, headers = api_instance.get_list_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => Array
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_list_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

**Array**

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_list_contacts_ids

> Array&lt;Integer&gt; get_list_contacts_ids(id)

Get all contact IDs in a list

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get all contact IDs in a list
  result = api_instance.get_list_contacts_ids(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_list_contacts_ids: #{e}"
end
```

#### Using the get_list_contacts_ids_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(Array&lt;Integer&gt;, Integer, Hash)> get_list_contacts_ids_with_http_info(id)

```ruby
begin
  # Get all contact IDs in a list
  data, status_code, headers = api_instance.get_list_contacts_ids_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => Array&lt;Integer&gt;
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_list_contacts_ids_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

**Array&lt;Integer&gt;**

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_lists

> <GetListsPaginatedResponse> get_lists(opts)

Get all lists

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | The current fetched page.
  limit: 56, # Integer | The number of results per page.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc', # String | Order direction. Default is desc.
  favorite_only: 0, # Integer | Return only favorited lists.
  only_mine: 0 # Integer | Return only current user lists.
}

begin
  # Get all lists
  result = api_instance.get_lists(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_lists: #{e}"
end
```

#### Using the get_lists_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetListsPaginatedResponse>, Integer, Hash)> get_lists_with_http_info(opts)

```ruby
begin
  # Get all lists
  data, status_code, headers = api_instance.get_lists_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetListsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_lists_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | The current fetched page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |
| **favorite_only** | **Integer** | Return only favorited lists. | [optional][default to 0] |
| **only_mine** | **Integer** | Return only current user lists. | [optional][default to 0] |

### Return type

[**GetListsPaginatedResponse**](GetListsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_lists_of_contact

> <GetListsOfContactPaginatedResponse> get_lists_of_contact(id, opts)

Get a contact's lists

Get all the lists in which a contact is included.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56 # Integer | The number of results per page.
}

begin
  # Get a contact's lists
  result = api_instance.get_lists_of_contact(id, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_lists_of_contact: #{e}"
end
```

#### Using the get_lists_of_contact_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetListsOfContactPaginatedResponse>, Integer, Hash)> get_lists_of_contact_with_http_info(id, opts)

```ruby
begin
  # Get a contact's lists
  data, status_code, headers = api_instance.get_lists_of_contact_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetListsOfContactPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_lists_of_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |

### Return type

[**GetListsOfContactPaginatedResponse**](GetListsOfContactPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_message_preview

> <GetMessagePreviewResponse> get_message_preview(opts)

Preview message

Get a messages preview (with dynamic fields merged) of up to 100 messages per session. 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  text: 'Test message test', # String | Message text. Required if **template_id** is not set.
  template_id: 1, # Integer | Template used instead of message text. Required if **text** is not set.
  sending_time: 1565606455, # Integer | DEPRECATED, consider using sendingDateTime and sendingTimezone parameters instead: Optional (required with rrule set). Message sending time is in unix timestamp format. Default is now.
  sending_date_time: '2020-05-27 13:02:33', # String | Sending time is in Y-m-d H:i:s format (e.g. 2016-05-27 13:02:33). This time is relative to the sendingTimezone.
  sending_timezone: 'America/Buenos_Aires', # String | The ID or ISO-name of the timezone used for sending when the sendingDateTime parameter is set, e.g. if you specify sendingDateTime = \\\"2016-05-27 13:02:33\\\" and sendingTimezone = \\\"America/Buenos_Aires\\\", your message will be sent on May 27, 2016 13:02:33 Buenos Aires time, or 16:02:33 UTC. Default is the account timezone.
  contacts: '1,2,3,4', # String | Comma-separated array of contact resources id message will be sent to.
  lists: '1,2,3,4', # String | Comma-separated array of list resources id message will be sent to.
  phones: '447860021130,447860021131', # String | Comma-separated array of E.164 phone numbers message will be sent to.
  cut_extra: 0, # Integer | Should sending method cut extra characters which not fit supplied partsCount or return 400 Bad request response instead.
  parts_count: 56, # Integer | Maximum message parts count (Textmagic allows sending of 1 to 6 message parts).
  reference_id: 1, # Integer | Custom message reference id which can be used in your application infrastructure.
  from: 'Test Sender ID', # String | One of the allowed Sender ID (phone number or alphanumeric sender ID). If the specified Sender ID is not allowed for some destinations, a fallback default Sender ID will be used to ensure delivery. See [Get timezones](https://docs.textmagic.com/#tag/Sender-IDs).
  rule: 'FREQ=YEARLY;BYMONTH=1;BYMONTHDAY=1;COUNT=1', # String | An iCal RRULE parameter to create recurrent scheduled messages. When used, sendingTime is mandatory as the start point of sending. See https://www.textmagic.com/free-tools/rrule-generator for format details.
  create_chat: 0, # Integer | Should the sending method try to create new Chat(if not exist) with specified recipients?
  tts: 0, # Integer | Send Text-to-Speech message.
  local: 0, # Integer | Treat phone numbers passed in the \\'phones\\' field as local.
  local_country: 'US' # String | The 2-letter ISO country code for local phone numbers, used when \\'local\\' is set to true. Default is the account country.
}

begin
  # Preview message
  result = api_instance.get_message_preview(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_message_preview: #{e}"
end
```

#### Using the get_message_preview_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetMessagePreviewResponse>, Integer, Hash)> get_message_preview_with_http_info(opts)

```ruby
begin
  # Preview message
  data, status_code, headers = api_instance.get_message_preview_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetMessagePreviewResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_message_preview_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **text** | **String** | Message text. Required if **template_id** is not set. | [optional] |
| **template_id** | **Integer** | Template used instead of message text. Required if **text** is not set. | [optional] |
| **sending_time** | **Integer** | DEPRECATED, consider using sendingDateTime and sendingTimezone parameters instead: Optional (required with rrule set). Message sending time is in unix timestamp format. Default is now. | [optional] |
| **sending_date_time** | **String** | Sending time is in Y-m-d H:i:s format (e.g. 2016-05-27 13:02:33). This time is relative to the sendingTimezone. | [optional] |
| **sending_timezone** | **String** | The ID or ISO-name of the timezone used for sending when the sendingDateTime parameter is set, e.g. if you specify sendingDateTime &#x3D; \\\&quot;2016-05-27 13:02:33\\\&quot; and sendingTimezone &#x3D; \\\&quot;America/Buenos_Aires\\\&quot;, your message will be sent on May 27, 2016 13:02:33 Buenos Aires time, or 16:02:33 UTC. Default is the account timezone. | [optional] |
| **contacts** | **String** | Comma-separated array of contact resources id message will be sent to. | [optional] |
| **lists** | **String** | Comma-separated array of list resources id message will be sent to. | [optional] |
| **phones** | **String** | Comma-separated array of E.164 phone numbers message will be sent to. | [optional] |
| **cut_extra** | **Integer** | Should sending method cut extra characters which not fit supplied partsCount or return 400 Bad request response instead. | [optional][default to 0] |
| **parts_count** | **Integer** | Maximum message parts count (Textmagic allows sending of 1 to 6 message parts). | [optional][default to 6] |
| **reference_id** | **Integer** | Custom message reference id which can be used in your application infrastructure. | [optional] |
| **from** | **String** | One of the allowed Sender ID (phone number or alphanumeric sender ID). If the specified Sender ID is not allowed for some destinations, a fallback default Sender ID will be used to ensure delivery. See [Get timezones](https://docs.textmagic.com/#tag/Sender-IDs). | [optional] |
| **rule** | **String** | An iCal RRULE parameter to create recurrent scheduled messages. When used, sendingTime is mandatory as the start point of sending. See https://www.textmagic.com/free-tools/rrule-generator for format details. | [optional] |
| **create_chat** | **Integer** | Should the sending method try to create new Chat(if not exist) with specified recipients? | [optional][default to 0] |
| **tts** | **Integer** | Send Text-to-Speech message. | [optional][default to 0] |
| **local** | **Integer** | Treat phone numbers passed in the \\&#39;phones\\&#39; field as local. | [optional][default to 0] |
| **local_country** | **String** | The 2-letter ISO country code for local phone numbers, used when \\&#39;local\\&#39; is set to true. Default is the account country. | [optional] |

### Return type

[**GetMessagePreviewResponse**](GetMessagePreviewResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_message_price

> <GetMessagePriceResponse> get_message_price(opts)

Check message price

Check pricing for a new outbound message.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  include_blocked: 0, # Integer | Should we show the pricing for blocked contacts?
  text: 'Test message test', # String | Message text. Required if the **template_id** is not set.
  template_id: 1, # Integer | Template used instead of message text. Required if the **text** is not set.
  sending_time: 1565606455, # Integer | DEPRECATED, consider using the sendingDateTime and sendingTimezone parameters instead: optional (required with rrule set). Message sending time is in unix timestamp format. Default is now.
  sending_date_time: '2020-05-27 13:02:33', # String | Sending time is in Y-m-d H:i:s format (e.g. 2016-05-27 13:02:33). This time is relative to the sendingTimezone.
  sending_timezone: 'America/Buenos_Aires', # String | The ID or ISO-name of the timezone used for sending when sendingDateTime parameter is set, e.g. if you specify sendingDateTime = \\\"2016-05-27 13:02:33\\\" and sendingTimezone = \\\"America/Buenos_Aires\\\", your message will be sent on May 27, 2016 13:02:33 Buenos Aires time, or 16:02:33 UTC. Default is the account timezone.
  contacts: '1,2,3,4', # String | Comma-separated array of contact resources id message will be sent to.
  lists: '1,2,3,4', # String | Comma-separated array of list resources id message will be sent to.
  phones: '447860021130,447860021131', # String | Comma-separated array of E.164 phone numbers message will be sent to.
  cut_extra: 0, # Integer | Should sending method cut extra characters which not fit supplied partsCount or return 400 Bad request response instead.
  parts_count: 56, # Integer | Maximum message parts count (Textmagic allows sending 1 to 6 message parts).
  reference_id: 1, # Integer | Custom message reference id which can be used in your application infrastructure.
  from: 'Test Sender ID', # String | One of the allowed Sender ID (phone number or alphanumeric sender ID). If the specified Sender ID is not allowed for some destinations, a fallback default Sender ID will be used to ensure delivery. See [Get timezones](https://docs.textmagic.com/#tag/Sender-IDs).
  rule: 'FREQ=YEARLY;BYMONTH=1;BYMONTHDAY=1;COUNT=1', # String | An iCal RRULE parameter to create recurrent scheduled messages. When used, sendingTime is mandatory as the start point of sending. See https://www.textmagic.com/free-tools/rrule-generator for format details.
  create_chat: 0, # Integer | Should the sending method try to create new Chat (if not exist) with specified recipients?
  tts: 0, # Integer | Send a Text-to-Speech message.
  local: 0, # Integer | Treat phone numbers passed in the \\'phones\\' field as local.
  local_country: 'US' # String | The 2-letter ISO country code for local phone numbers, used when \\'local\\' is set to true. Default is the account country.
}

begin
  # Check message price
  result = api_instance.get_message_price(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_message_price: #{e}"
end
```

#### Using the get_message_price_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetMessagePriceResponse>, Integer, Hash)> get_message_price_with_http_info(opts)

```ruby
begin
  # Check message price
  data, status_code, headers = api_instance.get_message_price_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetMessagePriceResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_message_price_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **include_blocked** | **Integer** | Should we show the pricing for blocked contacts? | [optional][default to 0] |
| **text** | **String** | Message text. Required if the **template_id** is not set. | [optional] |
| **template_id** | **Integer** | Template used instead of message text. Required if the **text** is not set. | [optional] |
| **sending_time** | **Integer** | DEPRECATED, consider using the sendingDateTime and sendingTimezone parameters instead: optional (required with rrule set). Message sending time is in unix timestamp format. Default is now. | [optional] |
| **sending_date_time** | **String** | Sending time is in Y-m-d H:i:s format (e.g. 2016-05-27 13:02:33). This time is relative to the sendingTimezone. | [optional] |
| **sending_timezone** | **String** | The ID or ISO-name of the timezone used for sending when sendingDateTime parameter is set, e.g. if you specify sendingDateTime &#x3D; \\\&quot;2016-05-27 13:02:33\\\&quot; and sendingTimezone &#x3D; \\\&quot;America/Buenos_Aires\\\&quot;, your message will be sent on May 27, 2016 13:02:33 Buenos Aires time, or 16:02:33 UTC. Default is the account timezone. | [optional] |
| **contacts** | **String** | Comma-separated array of contact resources id message will be sent to. | [optional] |
| **lists** | **String** | Comma-separated array of list resources id message will be sent to. | [optional] |
| **phones** | **String** | Comma-separated array of E.164 phone numbers message will be sent to. | [optional] |
| **cut_extra** | **Integer** | Should sending method cut extra characters which not fit supplied partsCount or return 400 Bad request response instead. | [optional][default to 0] |
| **parts_count** | **Integer** | Maximum message parts count (Textmagic allows sending 1 to 6 message parts). | [optional][default to 6] |
| **reference_id** | **Integer** | Custom message reference id which can be used in your application infrastructure. | [optional] |
| **from** | **String** | One of the allowed Sender ID (phone number or alphanumeric sender ID). If the specified Sender ID is not allowed for some destinations, a fallback default Sender ID will be used to ensure delivery. See [Get timezones](https://docs.textmagic.com/#tag/Sender-IDs). | [optional] |
| **rule** | **String** | An iCal RRULE parameter to create recurrent scheduled messages. When used, sendingTime is mandatory as the start point of sending. See https://www.textmagic.com/free-tools/rrule-generator for format details. | [optional] |
| **create_chat** | **Integer** | Should the sending method try to create new Chat (if not exist) with specified recipients? | [optional][default to 0] |
| **tts** | **Integer** | Send a Text-to-Speech message. | [optional][default to 0] |
| **local** | **Integer** | Treat phone numbers passed in the \\&#39;phones\\&#39; field as local. | [optional][default to 0] |
| **local_country** | **String** | The 2-letter ISO country code for local phone numbers, used when \\&#39;local\\&#39; is set to true. Default is the account country. | [optional] |

### Return type

[**GetMessagePriceResponse**](GetMessagePriceResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_message_session

> <MessageSession> get_message_session(id)

Get a session`s details

Get a specific session’s details.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | Session ID.

begin
  # Get a session`s details
  result = api_instance.get_message_session(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_message_session: #{e}"
end
```

#### Using the get_message_session_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<MessageSession>, Integer, Hash)> get_message_session_with_http_info(id)

```ruby
begin
  # Get a session`s details
  data, status_code, headers = api_instance.get_message_session_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <MessageSession>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_message_session_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Session ID. |  |

### Return type

[**MessageSession**](MessageSession.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_message_session_stat

> <GetMessageSessionStatResponse> get_message_session_stat(id, opts)

Get a session`s statistics

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
opts = {
  include_deleted: 0 # Integer | Search also in deleted messages.
}

begin
  # Get a session`s statistics
  result = api_instance.get_message_session_stat(id, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_message_session_stat: #{e}"
end
```

#### Using the get_message_session_stat_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetMessageSessionStatResponse>, Integer, Hash)> get_message_session_stat_with_http_info(id, opts)

```ruby
begin
  # Get a session`s statistics
  data, status_code, headers = api_instance.get_message_session_stat_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetMessageSessionStatResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_message_session_stat_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **include_deleted** | **Integer** | Search also in deleted messages. | [optional][default to 0] |

### Return type

[**GetMessageSessionStatResponse**](GetMessageSessionStatResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_messages_by_session_id

> <GetMessagesBySessionIdPaginatedResponse> get_messages_by_session_id(id, opts)

Get a session`s messages

A useful synonym for the \"messages/search\" command with the provided \"sessionId\" parameter.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  statuses: 'q', # String | Find messages by status.
  include_deleted: 0 # Integer | Search also in deleted messages.
}

begin
  # Get a session`s messages
  result = api_instance.get_messages_by_session_id(id, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_messages_by_session_id: #{e}"
end
```

#### Using the get_messages_by_session_id_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetMessagesBySessionIdPaginatedResponse>, Integer, Hash)> get_messages_by_session_id_with_http_info(id, opts)

```ruby
begin
  # Get a session`s messages
  data, status_code, headers = api_instance.get_messages_by_session_id_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetMessagesBySessionIdPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_messages_by_session_id_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **statuses** | **String** | Find messages by status. | [optional] |
| **include_deleted** | **Integer** | Search also in deleted messages. | [optional][default to 0] |

### Return type

[**GetMessagesBySessionIdPaginatedResponse**](GetMessagesBySessionIdPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_messaging_counters

> <GetMessagingCountersResponse> get_messaging_counters

Get sent/received messages counters values

Get total contacts, sent messages and received messages counters values.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Get sent/received messages counters values
  result = api_instance.get_messaging_counters
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_messaging_counters: #{e}"
end
```

#### Using the get_messaging_counters_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetMessagingCountersResponse>, Integer, Hash)> get_messaging_counters_with_http_info

```ruby
begin
  # Get sent/received messages counters values
  data, status_code, headers = api_instance.get_messaging_counters_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetMessagingCountersResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_messaging_counters_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**GetMessagingCountersResponse**](GetMessagingCountersResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_messaging_stat

> <Array<MessagingStatItem>> get_messaging_stat(opts)

Get messaging statistics

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  by: 'off', # String | *   **off** - to get total values per specified time interval; *   **day** - to show values grouped by day; *   **month** - to show values grouped by month; *   **year** - to show values grouped by year. 
  start: 1430438400, # Integer | Time period start in [UNIX timestamp](https://en.wikipedia.org/wiki/Unix_time) format. The default is 7 days prior. 
  _end: 1431648000 # Integer | Time period start in [UNIX timestamp](https://en.wikipedia.org/wiki/Unix_time) format. The default is today. 
}

begin
  # Get messaging statistics
  result = api_instance.get_messaging_stat(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_messaging_stat: #{e}"
end
```

#### Using the get_messaging_stat_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Array<MessagingStatItem>>, Integer, Hash)> get_messaging_stat_with_http_info(opts)

```ruby
begin
  # Get messaging statistics
  data, status_code, headers = api_instance.get_messaging_stat_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Array<MessagingStatItem>>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_messaging_stat_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **by** | **String** | *   **off** - to get total values per specified time interval; *   **day** - to show values grouped by day; *   **month** - to show values grouped by month; *   **year** - to show values grouped by year.  | [optional][default to &#39;off&#39;] |
| **start** | **Integer** | Time period start in [UNIX timestamp](https://en.wikipedia.org/wiki/Unix_time) format. The default is 7 days prior.  | [optional] |
| **_end** | **Integer** | Time period start in [UNIX timestamp](https://en.wikipedia.org/wiki/Unix_time) format. The default is today.  | [optional] |

### Return type

[**Array&lt;MessagingStatItem&gt;**](MessagingStatItem.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_outbound_message

> <MessageOut> get_outbound_message(id)

Get a single message

Get a single outgoing message.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get a single message
  result = api_instance.get_outbound_message(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_outbound_message: #{e}"
end
```

#### Using the get_outbound_message_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<MessageOut>, Integer, Hash)> get_outbound_message_with_http_info(id)

```ruby
begin
  # Get a single message
  data, status_code, headers = api_instance.get_outbound_message_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <MessageOut>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_outbound_message_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**MessageOut**](MessageOut.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_outbound_messages_history

> <GetOutboundMessagesHistoryPaginatedResponse> get_outbound_messages_history(opts)

Get history

Get the outbound messages history.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  limit: 56, # Integer | The number of results per page.
  last_id: 56, # Integer | Filter results by ID, selecting all values lesser than the specified ID.
  query: 'query_example', # String | Find message by specified search query.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc' # String | Order direction. Default is desc.
}

begin
  # Get history
  result = api_instance.get_outbound_messages_history(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_outbound_messages_history: #{e}"
end
```

#### Using the get_outbound_messages_history_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetOutboundMessagesHistoryPaginatedResponse>, Integer, Hash)> get_outbound_messages_history_with_http_info(opts)

```ruby
begin
  # Get history
  data, status_code, headers = api_instance.get_outbound_messages_history_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetOutboundMessagesHistoryPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_outbound_messages_history_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **last_id** | **Integer** | Filter results by ID, selecting all values lesser than the specified ID. | [optional] |
| **query** | **String** | Find message by specified search query. | [optional] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |

### Return type

[**GetOutboundMessagesHistoryPaginatedResponse**](GetOutboundMessagesHistoryPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_scheduled_message

> <MessagesIcs> get_scheduled_message(id)

Get a single scheduled message

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get a single scheduled message
  result = api_instance.get_scheduled_message(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_scheduled_message: #{e}"
end
```

#### Using the get_scheduled_message_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<MessagesIcs>, Integer, Hash)> get_scheduled_message_with_http_info(id)

```ruby
begin
  # Get a single scheduled message
  data, status_code, headers = api_instance.get_scheduled_message_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <MessagesIcs>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_scheduled_message_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**MessagesIcs**](MessagesIcs.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_sender_id

> <SenderId> get_sender_id(id)

Get the details of a specific Sender ID

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get the details of a specific Sender ID
  result = api_instance.get_sender_id(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_sender_id: #{e}"
end
```

#### Using the get_sender_id_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SenderId>, Integer, Hash)> get_sender_id_with_http_info(id)

```ruby
begin
  # Get the details of a specific Sender ID
  data, status_code, headers = api_instance.get_sender_id_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SenderId>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_sender_id_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**SenderId**](SenderId.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_sender_ids

> <GetSenderIdsPaginatedResponse> get_sender_ids(opts)

Get all your approved Sender IDs

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56 # Integer | The number of results per page.
}

begin
  # Get all your approved Sender IDs
  result = api_instance.get_sender_ids(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_sender_ids: #{e}"
end
```

#### Using the get_sender_ids_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetSenderIdsPaginatedResponse>, Integer, Hash)> get_sender_ids_with_http_info(opts)

```ruby
begin
  # Get all your approved Sender IDs
  data, status_code, headers = api_instance.get_sender_ids_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetSenderIdsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_sender_ids_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |

### Return type

[**GetSenderIdsPaginatedResponse**](GetSenderIdsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_sender_settings

> <GetSenderSettingsResponse> get_sender_settings(opts)

Get current sender settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  country: 'US' # String | Return sender settings enabled for sending to a specified country. Should be 2 upper-case characters.
}

begin
  # Get current sender settings
  result = api_instance.get_sender_settings(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_sender_settings: #{e}"
end
```

#### Using the get_sender_settings_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetSenderSettingsResponse>, Integer, Hash)> get_sender_settings_with_http_info(opts)

```ruby
begin
  # Get current sender settings
  data, status_code, headers = api_instance.get_sender_settings_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetSenderSettingsResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_sender_settings_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **country** | **String** | Return sender settings enabled for sending to a specified country. Should be 2 upper-case characters. | [optional] |

### Return type

[**GetSenderSettingsResponse**](GetSenderSettingsResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_spending_stat

> <GetSpendingStatPaginatedResponse> get_spending_stat(opts)

Get spending statistics

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  start: '2018-11-11 11:11', # String | Time period start in [UNIX timestamp](https://en.wikipedia.org/wiki/Unix_time) format. The default is 7 days prior. 
  _end: '2019-11-11 11:11' # String | Time period start in [UNIX timestamp](https://en.wikipedia.org/wiki/Unix_time) format. The default is today. 
}

begin
  # Get spending statistics
  result = api_instance.get_spending_stat(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_spending_stat: #{e}"
end
```

#### Using the get_spending_stat_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetSpendingStatPaginatedResponse>, Integer, Hash)> get_spending_stat_with_http_info(opts)

```ruby
begin
  # Get spending statistics
  data, status_code, headers = api_instance.get_spending_stat_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetSpendingStatPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_spending_stat_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **start** | **String** | Time period start in [UNIX timestamp](https://en.wikipedia.org/wiki/Unix_time) format. The default is 7 days prior.  | [optional] |
| **_end** | **String** | Time period start in [UNIX timestamp](https://en.wikipedia.org/wiki/Unix_time) format. The default is today.  | [optional] |

### Return type

[**GetSpendingStatPaginatedResponse**](GetSpendingStatPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_template

> <MessageTemplate> get_template(id)

Get a template`s details

Get a single template.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get a template`s details
  result = api_instance.get_template(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_template: #{e}"
end
```

#### Using the get_template_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<MessageTemplate>, Integer, Hash)> get_template_with_http_info(id)

```ruby
begin
  # Get a template`s details
  data, status_code, headers = api_instance.get_template_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <MessageTemplate>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_template_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**MessageTemplate**](MessageTemplate.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_timezones

> Object get_timezones(opts)

Get timezones

Return all available timezone IDs

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  full: 0 # Integer | Return full info about timezones in array (0 or 1). Default is 0.
}

begin
  # Get timezones
  result = api_instance.get_timezones(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_timezones: #{e}"
end
```

#### Using the get_timezones_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(Object, Integer, Hash)> get_timezones_with_http_info(opts)

```ruby
begin
  # Get timezones
  data, status_code, headers = api_instance.get_timezones_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => Object
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_timezones_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **full** | **Integer** | Return full info about timezones in array (0 or 1). Default is 0. | [optional][default to 0] |

### Return type

**Object**

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_unread_messages_total

> <GetUnreadMessagesTotalResponse> get_unread_messages_total

Get unread messages number

Get the total amount of unread messages in the current user chats.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Get unread messages number
  result = api_instance.get_unread_messages_total
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_unread_messages_total: #{e}"
end
```

#### Using the get_unread_messages_total_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetUnreadMessagesTotalResponse>, Integer, Hash)> get_unread_messages_total_with_http_info

```ruby
begin
  # Get unread messages number
  data, status_code, headers = api_instance.get_unread_messages_total_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetUnreadMessagesTotalResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_unread_messages_total_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**GetUnreadMessagesTotalResponse**](GetUnreadMessagesTotalResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_unsubscribed_contact

> <UnsubscribedContact> get_unsubscribed_contact(id)

Get the details of a specific unsubscribed contact

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 

begin
  # Get the details of a specific unsubscribed contact
  result = api_instance.get_unsubscribed_contact(id)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_unsubscribed_contact: #{e}"
end
```

#### Using the get_unsubscribed_contact_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<UnsubscribedContact>, Integer, Hash)> get_unsubscribed_contact_with_http_info(id)

```ruby
begin
  # Get the details of a specific unsubscribed contact
  data, status_code, headers = api_instance.get_unsubscribed_contact_with_http_info(id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <UnsubscribedContact>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_unsubscribed_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |

### Return type

[**UnsubscribedContact**](UnsubscribedContact.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_unsubscribers

> <GetUnsubscribersPaginatedResponse> get_unsubscribers(opts)

Get all unsubscribed contacts

When one of your message recipients sends a request with one of the [STOP-words](https://www.textmagic.com/sms-stop-command/), they will be immediately opted-out of your send lists and their contact status will change to an unsubscribed contact. To retrieve information on all contacts who have unsubscribed status, use: 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56 # Integer | The number of results per page.
}

begin
  # Get all unsubscribed contacts
  result = api_instance.get_unsubscribers(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_unsubscribers: #{e}"
end
```

#### Using the get_unsubscribers_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetUnsubscribersPaginatedResponse>, Integer, Hash)> get_unsubscribers_with_http_info(opts)

```ruby
begin
  # Get all unsubscribed contacts
  data, status_code, headers = api_instance.get_unsubscribers_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetUnsubscribersPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_unsubscribers_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |

### Return type

[**GetUnsubscribersPaginatedResponse**](GetUnsubscribersPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_user_dedicated_numbers

> <GetUserDedicatedNumbersPaginatedResponse> get_user_dedicated_numbers(opts)

Get all your dedicated numbers

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  survey_id: 56 # Integer | Fetch only those numbers that are ready for the survey.
}

begin
  # Get all your dedicated numbers
  result = api_instance.get_user_dedicated_numbers(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_user_dedicated_numbers: #{e}"
end
```

#### Using the get_user_dedicated_numbers_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetUserDedicatedNumbersPaginatedResponse>, Integer, Hash)> get_user_dedicated_numbers_with_http_info(opts)

```ruby
begin
  # Get all your dedicated numbers
  data, status_code, headers = api_instance.get_user_dedicated_numbers_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetUserDedicatedNumbersPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->get_user_dedicated_numbers_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **survey_id** | **Integer** | Fetch only those numbers that are ready for the survey. | [optional] |

### Return type

[**GetUserDedicatedNumbersPaginatedResponse**](GetUserDedicatedNumbersPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## import_contacts

> <ResourceLinkResponse> import_contacts(column, file, opts)

Import contacts

Import contacts from the CSV, XLS or XLSX file.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
column = '0:firstName;1:lastName;3:phone;4:email' # String | Import file column mapping. The string must contain sub-strings of mapping in format `columnNumber:field` glued by `;`. For example: `0:firstName;1:lastName;3:phone;4:email` where the value before `:` is a number of the column in the file, and the value after `:` is a field of the newly created contact or the ID of a custom field. Numbers of columns begin from zero. Allowed built-in contact fields are: `firstName`, `lastName`, `phone`, `email`. Existing of `phone` mapping is required. 
file = File.new('/path/to/some/file') # File | File containing contacts in csv or xls(x) formats.
opts = {
  list_id: 443, # Integer | List that ID contacts will be imported to. Ignored if `listName` is specified. 
  list_name: 'A new list' # String | List name. This list will be created during import. If such name is already taken, an ordinal (1, 2, ...) will be added to the end. Ignored if `listId` is specified. 
}

begin
  # Import contacts
  result = api_instance.import_contacts(column, file, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->import_contacts: #{e}"
end
```

#### Using the import_contacts_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> import_contacts_with_http_info(column, file, opts)

```ruby
begin
  # Import contacts
  data, status_code, headers = api_instance.import_contacts_with_http_info(column, file, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->import_contacts_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **column** | **String** | Import file column mapping. The string must contain sub-strings of mapping in format &#x60;columnNumber:field&#x60; glued by &#x60;;&#x60;. For example: &#x60;0:firstName;1:lastName;3:phone;4:email&#x60; where the value before &#x60;:&#x60; is a number of the column in the file, and the value after &#x60;:&#x60; is a field of the newly created contact or the ID of a custom field. Numbers of columns begin from zero. Allowed built-in contact fields are: &#x60;firstName&#x60;, &#x60;lastName&#x60;, &#x60;phone&#x60;, &#x60;email&#x60;. Existing of &#x60;phone&#x60; mapping is required.  |  |
| **file** | **File** | File containing contacts in csv or xls(x) formats. |  |
| **list_id** | **Integer** | List that ID contacts will be imported to. Ignored if &#x60;listName&#x60; is specified.  | [optional] |
| **list_name** | **String** | List name. This list will be created during import. If such name is already taken, an ordinal (1, 2, ...) will be added to the end. Ignored if &#x60;listId&#x60; is specified.  | [optional] |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## mark_chats_read_bulk

> mark_chats_read_bulk(mark_chats_read_bulk_input_object)

Mark chats as read (bulk)

Mark several chats as read by chat IDs or mark all chats as read

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
mark_chats_read_bulk_input_object = TextMagic::MarkChatsUnreadBulkRequest.new # MarkChatsUnreadBulkRequest | 

begin
  # Mark chats as read (bulk)
  api_instance.mark_chats_read_bulk(mark_chats_read_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->mark_chats_read_bulk: #{e}"
end
```

#### Using the mark_chats_read_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> mark_chats_read_bulk_with_http_info(mark_chats_read_bulk_input_object)

```ruby
begin
  # Mark chats as read (bulk)
  data, status_code, headers = api_instance.mark_chats_read_bulk_with_http_info(mark_chats_read_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->mark_chats_read_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **mark_chats_read_bulk_input_object** | [**MarkChatsUnreadBulkRequest**](MarkChatsUnreadBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## mark_chats_unread_bulk

> mark_chats_unread_bulk(mark_chats_unread_bulk_input_object)

Mark chats as unread (bulk)

Mark several chats as UNread by chat IDs or mark all chats as UNread

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
mark_chats_unread_bulk_input_object = TextMagic::MarkChatsUnreadBulkRequest.new # MarkChatsUnreadBulkRequest | 

begin
  # Mark chats as unread (bulk)
  api_instance.mark_chats_unread_bulk(mark_chats_unread_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->mark_chats_unread_bulk: #{e}"
end
```

#### Using the mark_chats_unread_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> mark_chats_unread_bulk_with_http_info(mark_chats_unread_bulk_input_object)

```ruby
begin
  # Mark chats as unread (bulk)
  data, status_code, headers = api_instance.mark_chats_unread_bulk_with_http_info(mark_chats_unread_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->mark_chats_unread_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **mark_chats_unread_bulk_input_object** | [**MarkChatsUnreadBulkRequest**](MarkChatsUnreadBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## mute_chat

> <ResourceLinkResponse> mute_chat(mute_chat_input_object)

Mute chat sounds

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
mute_chat_input_object = TextMagic::MuteChatRequest.new # MuteChatRequest | 

begin
  # Mute chat sounds
  result = api_instance.mute_chat(mute_chat_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->mute_chat: #{e}"
end
```

#### Using the mute_chat_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> mute_chat_with_http_info(mute_chat_input_object)

```ruby
begin
  # Mute chat sounds
  data, status_code, headers = api_instance.mute_chat_with_http_info(mute_chat_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->mute_chat_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **mute_chat_input_object** | [**MuteChatRequest**](MuteChatRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## mute_chats_bulk

> mute_chats_bulk(mute_chats_bulk_input_object)

Mute chats (bulk)

Mute several chats by chat ids or mute all chats.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
mute_chats_bulk_input_object = TextMagic::MuteChatsBulkRequest.new # MuteChatsBulkRequest | 

begin
  # Mute chats (bulk)
  api_instance.mute_chats_bulk(mute_chats_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->mute_chats_bulk: #{e}"
end
```

#### Using the mute_chats_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> mute_chats_bulk_with_http_info(mute_chats_bulk_input_object)

```ruby
begin
  # Mute chats (bulk)
  data, status_code, headers = api_instance.mute_chats_bulk_with_http_info(mute_chats_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->mute_chats_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **mute_chats_bulk_input_object** | [**MuteChatsBulkRequest**](MuteChatsBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## ping

> <PingResponse> ping

Ping

Make a simple ping request.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new

begin
  # Ping
  result = api_instance.ping
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->ping: #{e}"
end
```

#### Using the ping_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<PingResponse>, Integer, Hash)> ping_with_http_info

```ruby
begin
  # Ping
  data, status_code, headers = api_instance.ping_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <PingResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->ping_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**PingResponse**](PingResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## reopen_chats_bulk

> reopen_chats_bulk(reopen_chats_bulk_input_object)

Reopen chats (bulk)

Reopen chats by chat IDs or reopen all chats

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
reopen_chats_bulk_input_object = TextMagic::MarkChatsUnreadBulkRequest.new # MarkChatsUnreadBulkRequest | 

begin
  # Reopen chats (bulk)
  api_instance.reopen_chats_bulk(reopen_chats_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->reopen_chats_bulk: #{e}"
end
```

#### Using the reopen_chats_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> reopen_chats_bulk_with_http_info(reopen_chats_bulk_input_object)

```ruby
begin
  # Reopen chats (bulk)
  data, status_code, headers = api_instance.reopen_chats_bulk_with_http_info(reopen_chats_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->reopen_chats_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **reopen_chats_bulk_input_object** | [**MarkChatsUnreadBulkRequest**](MarkChatsUnreadBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## request_sender_id

> <ResourceLinkResponse> request_sender_id(request_sender_id_input_object)

Apply for a new Sender ID

> Sender IDs are shared among all of your sub-accounts.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
request_sender_id_input_object = TextMagic::RequestSenderIdRequest.new # RequestSenderIdRequest | 

begin
  # Apply for a new Sender ID
  result = api_instance.request_sender_id(request_sender_id_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->request_sender_id: #{e}"
end
```

#### Using the request_sender_id_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> request_sender_id_with_http_info(request_sender_id_input_object)

```ruby
begin
  # Apply for a new Sender ID
  data, status_code, headers = api_instance.request_sender_id_with_http_info(request_sender_id_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->request_sender_id_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **request_sender_id_input_object** | [**RequestSenderIdRequest**](RequestSenderIdRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## schedule_email_campaign

> <ScheduleEmailCampaignResponse> schedule_email_campaign(schedule_email_campaign_input_object)

Schedule new email campaign

Creates a new scheduled email campaign that will be sent at a specified time or according to a recurring schedule.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
schedule_email_campaign_input_object = TextMagic::ScheduleEmailCampaignRequest.new # ScheduleEmailCampaignRequest | 

begin
  # Schedule new email campaign
  result = api_instance.schedule_email_campaign(schedule_email_campaign_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->schedule_email_campaign: #{e}"
end
```

#### Using the schedule_email_campaign_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScheduleEmailCampaignResponse>, Integer, Hash)> schedule_email_campaign_with_http_info(schedule_email_campaign_input_object)

```ruby
begin
  # Schedule new email campaign
  data, status_code, headers = api_instance.schedule_email_campaign_with_http_info(schedule_email_campaign_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScheduleEmailCampaignResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->schedule_email_campaign_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **schedule_email_campaign_input_object** | [**ScheduleEmailCampaignRequest**](ScheduleEmailCampaignRequest.md) |  |  |

### Return type

[**ScheduleEmailCampaignResponse**](ScheduleEmailCampaignResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## search_chats

> <SearchChatsPaginatedResponse> search_chats(opts)

Find chats by message text

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  query: 'query_example' # String | Find chats by specified search query.
}

begin
  # Find chats by message text
  result = api_instance.search_chats(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_chats: #{e}"
end
```

#### Using the search_chats_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchChatsPaginatedResponse>, Integer, Hash)> search_chats_with_http_info(opts)

```ruby
begin
  # Find chats by message text
  data, status_code, headers = api_instance.search_chats_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchChatsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_chats_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **query** | **String** | Find chats by specified search query. | [optional] |

### Return type

[**SearchChatsPaginatedResponse**](SearchChatsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## search_chats_by_ids

> <SearchChatsByIdsPaginatedResponse> search_chats_by_ids(opts)

Find chats (bulk)

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  ids: 'ids_example' # String | Find chats by ID(s).
}

begin
  # Find chats (bulk)
  result = api_instance.search_chats_by_ids(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_chats_by_ids: #{e}"
end
```

#### Using the search_chats_by_ids_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchChatsByIdsPaginatedResponse>, Integer, Hash)> search_chats_by_ids_with_http_info(opts)

```ruby
begin
  # Find chats (bulk)
  data, status_code, headers = api_instance.search_chats_by_ids_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchChatsByIdsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_chats_by_ids_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **ids** | **String** | Find chats by ID(s). | [optional] |

### Return type

[**SearchChatsByIdsPaginatedResponse**](SearchChatsByIdsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## search_chats_by_receipent

> <SearchChatsByReceipentPaginatedResponse> search_chats_by_receipent(opts)

Find chats by recipient

Find chats by recipient (contact, list name or phone number).

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  query: 'query_example', # String | Find chats by specified search query.
  order_by: 'id' # String | Order results by some field. Default is id.
}

begin
  # Find chats by recipient
  result = api_instance.search_chats_by_receipent(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_chats_by_receipent: #{e}"
end
```

#### Using the search_chats_by_receipent_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchChatsByReceipentPaginatedResponse>, Integer, Hash)> search_chats_by_receipent_with_http_info(opts)

```ruby
begin
  # Find chats by recipient
  data, status_code, headers = api_instance.search_chats_by_receipent_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchChatsByReceipentPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_chats_by_receipent_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **query** | **String** | Find chats by specified search query. | [optional] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |

### Return type

[**SearchChatsByReceipentPaginatedResponse**](SearchChatsByReceipentPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## search_contacts

> <SearchContactsPaginatedResponse> search_contacts(opts)

Find contacts by given criteria

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  shared: 0, # Integer | Should shared contacts be included?
  ids: 'ids_example', # String | Find contacts by IDs.
  list_id: 56, # Integer | Find contacts by List ID.
  include_blocked: 0, # Integer | Should blocked contacts be included?
  query: 'query_example', # String | Find contacts by specified search query.
  local: 0, # Integer | Treat phone number passed in the \"query\" field as local. Default is 0.
  exact_match: 0, # Integer | Return only exactly matching contacts. Default is 0.
  country: 'country_example', # String | The 2-letter ISO country code for local phone numbers, used when \"local\" is set to true. Default is the account country.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc', # String | Order direction. Default is desc.
  tag_ids: 'tag_ids_example' # String | Find contacts by tag ID(s). Multiple IDs can be separated by comma.
}

begin
  # Find contacts by given criteria
  result = api_instance.search_contacts(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_contacts: #{e}"
end
```

#### Using the search_contacts_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchContactsPaginatedResponse>, Integer, Hash)> search_contacts_with_http_info(opts)

```ruby
begin
  # Find contacts by given criteria
  data, status_code, headers = api_instance.search_contacts_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchContactsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_contacts_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **shared** | **Integer** | Should shared contacts be included? | [optional][default to 0] |
| **ids** | **String** | Find contacts by IDs. | [optional] |
| **list_id** | **Integer** | Find contacts by List ID. | [optional] |
| **include_blocked** | **Integer** | Should blocked contacts be included? | [optional] |
| **query** | **String** | Find contacts by specified search query. | [optional] |
| **local** | **Integer** | Treat phone number passed in the \&quot;query\&quot; field as local. Default is 0. | [optional][default to 0] |
| **exact_match** | **Integer** | Return only exactly matching contacts. Default is 0. | [optional][default to 0] |
| **country** | **String** | The 2-letter ISO country code for local phone numbers, used when \&quot;local\&quot; is set to true. Default is the account country. | [optional] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |
| **tag_ids** | **String** | Find contacts by tag ID(s). Multiple IDs can be separated by comma. | [optional] |

### Return type

[**SearchContactsPaginatedResponse**](SearchContactsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## search_inbound_messages

> <SearchInboundMessagesPaginatedResponse> search_inbound_messages(opts)

Find inbound messages

Find inbound messages by given parameters.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  ids: 'ids_example', # String | Find message by ID(s).
  query: 'query_example', # String | Find recipients by specified search query.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc', # String | Order direction. Default is desc.
  expand: 0 # Integer | Expand by adding firstName, lastName and contactId.
}

begin
  # Find inbound messages
  result = api_instance.search_inbound_messages(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_inbound_messages: #{e}"
end
```

#### Using the search_inbound_messages_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchInboundMessagesPaginatedResponse>, Integer, Hash)> search_inbound_messages_with_http_info(opts)

```ruby
begin
  # Find inbound messages
  data, status_code, headers = api_instance.search_inbound_messages_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchInboundMessagesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_inbound_messages_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **ids** | **String** | Find message by ID(s). | [optional] |
| **query** | **String** | Find recipients by specified search query. | [optional] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |
| **expand** | **Integer** | Expand by adding firstName, lastName and contactId. | [optional][default to 0] |

### Return type

[**SearchInboundMessagesPaginatedResponse**](SearchInboundMessagesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## search_lists

> <SearchListsPaginatedResponse> search_lists(opts)

Find lists by given criteria

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  ids: '1,2,3,4', # String | Find lists by IDs.
  query: 'A', # String | Find lists by specified search query.
  only_mine: 0, # Integer | Return only current user lists.
  only_default: 56, # Integer | Return only default lists.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc' # String | Order direction. Default is desc.
}

begin
  # Find lists by given criteria
  result = api_instance.search_lists(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_lists: #{e}"
end
```

#### Using the search_lists_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchListsPaginatedResponse>, Integer, Hash)> search_lists_with_http_info(opts)

```ruby
begin
  # Find lists by given criteria
  data, status_code, headers = api_instance.search_lists_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchListsPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_lists_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **ids** | **String** | Find lists by IDs. | [optional] |
| **query** | **String** | Find lists by specified search query. | [optional] |
| **only_mine** | **Integer** | Return only current user lists. | [optional][default to 0] |
| **only_default** | **Integer** | Return only default lists. | [optional][default to 0] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |

### Return type

[**SearchListsPaginatedResponse**](SearchListsPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## search_outbound_messages

> <SearchOutboundMessagesPaginatedResponse> search_outbound_messages(opts)

Find messages

Find outbound messages by given parameters.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  last_id: 56, # Integer | Filter results by ID, selecting all values lesser than the specified ID. Note that the \\'page\\' parameter is ignored when \\'lastId\\' is specified.
  ids: 'ids_example', # String | Find message by ID(s).
  session_id: 56, # Integer | Find messages by session ID.
  statuses: 'q', # String | Find messages by status.
  include_deleted: 0, # Integer | Search also in deleted messages.
  query: 'query_example' # String | Find messages by specified search query.
}

begin
  # Find messages
  result = api_instance.search_outbound_messages(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_outbound_messages: #{e}"
end
```

#### Using the search_outbound_messages_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchOutboundMessagesPaginatedResponse>, Integer, Hash)> search_outbound_messages_with_http_info(opts)

```ruby
begin
  # Find messages
  data, status_code, headers = api_instance.search_outbound_messages_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchOutboundMessagesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_outbound_messages_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **last_id** | **Integer** | Filter results by ID, selecting all values lesser than the specified ID. Note that the \\&#39;page\\&#39; parameter is ignored when \\&#39;lastId\\&#39; is specified. | [optional] |
| **ids** | **String** | Find message by ID(s). | [optional] |
| **session_id** | **Integer** | Find messages by session ID. | [optional] |
| **statuses** | **String** | Find messages by status. | [optional] |
| **include_deleted** | **Integer** | Search also in deleted messages. | [optional][default to 0] |
| **query** | **String** | Find messages by specified search query. | [optional] |

### Return type

[**SearchOutboundMessagesPaginatedResponse**](SearchOutboundMessagesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## search_scheduled_messages

> <SearchScheduledMessagesPaginatedResponse> search_scheduled_messages(opts)

Find scheduled messages

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  query: 'query_example', # String | Find messages by specified search query.
  ids: 'ids_example', # String | Find schedules by ID(s).
  status: 'x', # String | Fetch schedules with a specific status: a - actual, c - completed, x - all.
  order_by: 'id', # String | Order results by some field. Default is id.
  direction: 'asc' # String | Order direction. Default is desc.
}

begin
  # Find scheduled messages
  result = api_instance.search_scheduled_messages(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_scheduled_messages: #{e}"
end
```

#### Using the search_scheduled_messages_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchScheduledMessagesPaginatedResponse>, Integer, Hash)> search_scheduled_messages_with_http_info(opts)

```ruby
begin
  # Find scheduled messages
  data, status_code, headers = api_instance.search_scheduled_messages_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchScheduledMessagesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_scheduled_messages_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **query** | **String** | Find messages by specified search query. | [optional] |
| **ids** | **String** | Find schedules by ID(s). | [optional] |
| **status** | **String** | Fetch schedules with a specific status: a - actual, c - completed, x - all. | [optional][default to &#39;x&#39;] |
| **order_by** | **String** | Order results by some field. Default is id. | [optional][default to &#39;id&#39;] |
| **direction** | **String** | Order direction. Default is desc. | [optional][default to &#39;desc&#39;] |

### Return type

[**SearchScheduledMessagesPaginatedResponse**](SearchScheduledMessagesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## search_templates

> <SearchTemplatesPaginatedResponse> search_templates(opts)

Find templates by criteria

Find user templates by given parameters.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
opts = {
  page: 56, # Integer | Fetch specified results page.
  limit: 56, # Integer | The number of results per page.
  ids: 'ids_example', # String | Find template by ID(s).
  name: 'name_example', # String | Find template by name.
  content: 'content_example' # String | Find template by content.
}

begin
  # Find templates by criteria
  result = api_instance.search_templates(opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_templates: #{e}"
end
```

#### Using the search_templates_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SearchTemplatesPaginatedResponse>, Integer, Hash)> search_templates_with_http_info(opts)

```ruby
begin
  # Find templates by criteria
  data, status_code, headers = api_instance.search_templates_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SearchTemplatesPaginatedResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->search_templates_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** | Fetch specified results page. | [optional][default to 1] |
| **limit** | **Integer** | The number of results per page. | [optional][default to 10] |
| **ids** | **String** | Find template by ID(s). | [optional] |
| **name** | **String** | Find template by name. | [optional] |
| **content** | **String** | Find template by content. | [optional] |

### Return type

[**SearchTemplatesPaginatedResponse**](SearchTemplatesPaginatedResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## send_message

> <SendMessageResponse> send_message(send_message_input_object)

Send message

This is the main entrypoint to send messages. See the examples above for the reference.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
send_message_input_object = TextMagic::SendMessageRequest.new # SendMessageRequest | 

begin
  # Send message
  result = api_instance.send_message(send_message_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->send_message: #{e}"
end
```

#### Using the send_message_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SendMessageResponse>, Integer, Hash)> send_message_with_http_info(send_message_input_object)

```ruby
begin
  # Send message
  data, status_code, headers = api_instance.send_message_with_http_info(send_message_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SendMessageResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->send_message_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **send_message_input_object** | [**SendMessageRequest**](SendMessageRequest.md) |  |  |

### Return type

[**SendMessageResponse**](SendMessageResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## set_chat_status

> <ResourceLinkResponse> set_chat_status(set_chat_status_input_object)

Change chat status

Set the status of the chat given by ID.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
set_chat_status_input_object = TextMagic::SetChatStatusRequest.new # SetChatStatusRequest | 

begin
  # Change chat status
  result = api_instance.set_chat_status(set_chat_status_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->set_chat_status: #{e}"
end
```

#### Using the set_chat_status_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> set_chat_status_with_http_info(set_chat_status_input_object)

```ruby
begin
  # Change chat status
  data, status_code, headers = api_instance.set_chat_status_with_http_info(set_chat_status_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->set_chat_status_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **set_chat_status_input_object** | [**SetChatStatusRequest**](SetChatStatusRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## unblock_contact

> unblock_contact(unblock_contact_input_object)

Unblock a contact by phone number

Unblock a contact by phone number

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
unblock_contact_input_object = TextMagic::BlockContactRequest.new # BlockContactRequest | 

begin
  # Unblock a contact by phone number
  api_instance.unblock_contact(unblock_contact_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->unblock_contact: #{e}"
end
```

#### Using the unblock_contact_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> unblock_contact_with_http_info(unblock_contact_input_object)

```ruby
begin
  # Unblock a contact by phone number
  data, status_code, headers = api_instance.unblock_contact_with_http_info(unblock_contact_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->unblock_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **unblock_contact_input_object** | [**BlockContactRequest**](BlockContactRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## unblock_contacts_bulk

> unblock_contacts_bulk(unblock_contacts_bulk_input_object)

Unblock contacts (bulk)

Unblock several contacts by blocked contact IDs or unblock all contacts.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
unblock_contacts_bulk_input_object = TextMagic::UnblockContactsBulkRequest.new # UnblockContactsBulkRequest | 

begin
  # Unblock contacts (bulk)
  api_instance.unblock_contacts_bulk(unblock_contacts_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->unblock_contacts_bulk: #{e}"
end
```

#### Using the unblock_contacts_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> unblock_contacts_bulk_with_http_info(unblock_contacts_bulk_input_object)

```ruby
begin
  # Unblock contacts (bulk)
  data, status_code, headers = api_instance.unblock_contacts_bulk_with_http_info(unblock_contacts_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->unblock_contacts_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **unblock_contacts_bulk_input_object** | [**UnblockContactsBulkRequest**](UnblockContactsBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## unmute_chats_bulk

> unmute_chats_bulk(unmute_chats_bulk_input_object)

Unmute chats (bulk)

Unmute several chats by chat ids or unmute all chats.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
unmute_chats_bulk_input_object = TextMagic::UnmuteChatsBulkRequest.new # UnmuteChatsBulkRequest | 

begin
  # Unmute chats (bulk)
  api_instance.unmute_chats_bulk(unmute_chats_bulk_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->unmute_chats_bulk: #{e}"
end
```

#### Using the unmute_chats_bulk_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> unmute_chats_bulk_with_http_info(unmute_chats_bulk_input_object)

```ruby
begin
  # Unmute chats (bulk)
  data, status_code, headers = api_instance.unmute_chats_bulk_with_http_info(unmute_chats_bulk_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->unmute_chats_bulk_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **unmute_chats_bulk_input_object** | [**UnmuteChatsBulkRequest**](UnmuteChatsBulkRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## unsubscribe_contact

> <ResourceLinkResponse> unsubscribe_contact(unsubscribe_contact_input_object)

Manually unsubscribe a contact

> Please note, if you unsubscribe a contact, this action cannot be reversed. 

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
unsubscribe_contact_input_object = TextMagic::UnsubscribeContactRequest.new # UnsubscribeContactRequest | 

begin
  # Manually unsubscribe a contact
  result = api_instance.unsubscribe_contact(unsubscribe_contact_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->unsubscribe_contact: #{e}"
end
```

#### Using the unsubscribe_contact_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> unsubscribe_contact_with_http_info(unsubscribe_contact_input_object)

```ruby
begin
  # Manually unsubscribe a contact
  data, status_code, headers = api_instance.unsubscribe_contact_with_http_info(unsubscribe_contact_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->unsubscribe_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **unsubscribe_contact_input_object** | [**UnsubscribeContactRequest**](UnsubscribeContactRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_balance_notification_settings

> update_balance_notification_settings(update_balance_notification_settings_input_object)

Update balance notification settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
update_balance_notification_settings_input_object = TextMagic::UpdateBalanceNotificationSettingsRequest.new # UpdateBalanceNotificationSettingsRequest | 

begin
  # Update balance notification settings
  api_instance.update_balance_notification_settings(update_balance_notification_settings_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_balance_notification_settings: #{e}"
end
```

#### Using the update_balance_notification_settings_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> update_balance_notification_settings_with_http_info(update_balance_notification_settings_input_object)

```ruby
begin
  # Update balance notification settings
  data, status_code, headers = api_instance.update_balance_notification_settings_with_http_info(update_balance_notification_settings_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_balance_notification_settings_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **update_balance_notification_settings_input_object** | [**UpdateBalanceNotificationSettingsRequest**](UpdateBalanceNotificationSettingsRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## update_callback_settings

> update_callback_settings(update_callback_settings_input_object)

Update callback URL settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
update_callback_settings_input_object = TextMagic::UpdateCallbackSettingsRequest.new # UpdateCallbackSettingsRequest | 

begin
  # Update callback URL settings
  api_instance.update_callback_settings(update_callback_settings_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_callback_settings: #{e}"
end
```

#### Using the update_callback_settings_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> update_callback_settings_with_http_info(update_callback_settings_input_object)

```ruby
begin
  # Update callback URL settings
  data, status_code, headers = api_instance.update_callback_settings_with_http_info(update_callback_settings_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_callback_settings_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **update_callback_settings_input_object** | [**UpdateCallbackSettingsRequest**](UpdateCallbackSettingsRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_chat_desktop_notification_settings

> update_chat_desktop_notification_settings(update_chat_desktop_notification_settings_input_object)

Update chat desktop notification settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
update_chat_desktop_notification_settings_input_object = TextMagic::UpdateChatDesktopNotificationSettingsRequest.new # UpdateChatDesktopNotificationSettingsRequest | 

begin
  # Update chat desktop notification settings
  api_instance.update_chat_desktop_notification_settings(update_chat_desktop_notification_settings_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_chat_desktop_notification_settings: #{e}"
end
```

#### Using the update_chat_desktop_notification_settings_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> update_chat_desktop_notification_settings_with_http_info(update_chat_desktop_notification_settings_input_object)

```ruby
begin
  # Update chat desktop notification settings
  data, status_code, headers = api_instance.update_chat_desktop_notification_settings_with_http_info(update_chat_desktop_notification_settings_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_chat_desktop_notification_settings_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **update_chat_desktop_notification_settings_input_object** | [**UpdateChatDesktopNotificationSettingsRequest**](UpdateChatDesktopNotificationSettingsRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_contact

> <ResourceLinkResponse> update_contact(id, update_contact_input_object)

Edit a contact

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
update_contact_input_object = TextMagic::UpdateContactRequest.new # UpdateContactRequest | 

begin
  # Edit a contact
  result = api_instance.update_contact(id, update_contact_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_contact: #{e}"
end
```

#### Using the update_contact_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> update_contact_with_http_info(id, update_contact_input_object)

```ruby
begin
  # Edit a contact
  data, status_code, headers = api_instance.update_contact_with_http_info(id, update_contact_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_contact_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **update_contact_input_object** | [**UpdateContactRequest**](UpdateContactRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_contact_note

> <ResourceLinkResponse> update_contact_note(id, update_contact_note_input_object)

Update a contact note

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
update_contact_note_input_object = TextMagic::UpdateContactNoteRequest.new # UpdateContactNoteRequest | 

begin
  # Update a contact note
  result = api_instance.update_contact_note(id, update_contact_note_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_contact_note: #{e}"
end
```

#### Using the update_contact_note_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> update_contact_note_with_http_info(id, update_contact_note_input_object)

```ruby
begin
  # Update a contact note
  data, status_code, headers = api_instance.update_contact_note_with_http_info(id, update_contact_note_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_contact_note_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **update_contact_note_input_object** | [**UpdateContactNoteRequest**](UpdateContactNoteRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_current_user

> <UpdateCurrentUserResponse> update_current_user(update_current_user_input_object)

Edit current account info

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
update_current_user_input_object = TextMagic::UpdateCurrentUserRequest.new # UpdateCurrentUserRequest | 

begin
  # Edit current account info
  result = api_instance.update_current_user(update_current_user_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_current_user: #{e}"
end
```

#### Using the update_current_user_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<UpdateCurrentUserResponse>, Integer, Hash)> update_current_user_with_http_info(update_current_user_input_object)

```ruby
begin
  # Edit current account info
  data, status_code, headers = api_instance.update_current_user_with_http_info(update_current_user_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <UpdateCurrentUserResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_current_user_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **update_current_user_input_object** | [**UpdateCurrentUserRequest**](UpdateCurrentUserRequest.md) |  |  |

### Return type

[**UpdateCurrentUserResponse**](UpdateCurrentUserResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_custom_field

> <ResourceLinkResponse> update_custom_field(id, update_custom_field_input_object)

Edit a custom field

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
update_custom_field_input_object = TextMagic::CreateCustomFieldRequest.new # CreateCustomFieldRequest | 

begin
  # Edit a custom field
  result = api_instance.update_custom_field(id, update_custom_field_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_custom_field: #{e}"
end
```

#### Using the update_custom_field_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> update_custom_field_with_http_info(id, update_custom_field_input_object)

```ruby
begin
  # Edit a custom field
  data, status_code, headers = api_instance.update_custom_field_with_http_info(id, update_custom_field_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_custom_field_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **update_custom_field_input_object** | [**CreateCustomFieldRequest**](CreateCustomFieldRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_custom_field_value

> <ResourceLinkResponse> update_custom_field_value(id, update_custom_field_value_input_object)

Edit the custom field value of a specified contact

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 554 # Integer | 
update_custom_field_value_input_object = TextMagic::UpdateCustomFieldValueRequest.new # UpdateCustomFieldValueRequest | 

begin
  # Edit the custom field value of a specified contact
  result = api_instance.update_custom_field_value(id, update_custom_field_value_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_custom_field_value: #{e}"
end
```

#### Using the update_custom_field_value_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> update_custom_field_value_with_http_info(id, update_custom_field_value_input_object)

```ruby
begin
  # Edit the custom field value of a specified contact
  data, status_code, headers = api_instance.update_custom_field_value_with_http_info(id, update_custom_field_value_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_custom_field_value_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **update_custom_field_value_input_object** | [**UpdateCustomFieldValueRequest**](UpdateCustomFieldValueRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_inbound_messages_notification_settings

> update_inbound_messages_notification_settings(update_inbound_messages_notification_settings_input_object)

Update inbound messages notification settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
update_inbound_messages_notification_settings_input_object = TextMagic::UpdateInboundMessagesNotificationSettingsRequest.new # UpdateInboundMessagesNotificationSettingsRequest | 

begin
  # Update inbound messages notification settings
  api_instance.update_inbound_messages_notification_settings(update_inbound_messages_notification_settings_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_inbound_messages_notification_settings: #{e}"
end
```

#### Using the update_inbound_messages_notification_settings_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> update_inbound_messages_notification_settings_with_http_info(update_inbound_messages_notification_settings_input_object)

```ruby
begin
  # Update inbound messages notification settings
  data, status_code, headers = api_instance.update_inbound_messages_notification_settings_with_http_info(update_inbound_messages_notification_settings_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_inbound_messages_notification_settings_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **update_inbound_messages_notification_settings_input_object** | [**UpdateInboundMessagesNotificationSettingsRequest**](UpdateInboundMessagesNotificationSettingsRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## update_list

> <ResourceLinkResponse> update_list(id, opts)

Edit a list

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
opts = {
  update_list_object: TextMagic::UpdateListRequest.new # UpdateListRequest | 
}

begin
  # Edit a list
  result = api_instance.update_list(id, opts)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_list: #{e}"
end
```

#### Using the update_list_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> update_list_with_http_info(id, opts)

```ruby
begin
  # Edit a list
  data, status_code, headers = api_instance.update_list_with_http_info(id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_list_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **update_list_object** | [**UpdateListRequest**](UpdateListRequest.md) |  | [optional] |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_sender_setting

> update_sender_setting(update_sender_setting_input_object)

Change sender settings

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
update_sender_setting_input_object = TextMagic::UpdateSenderSettingRequest.new # UpdateSenderSettingRequest | 

begin
  # Change sender settings
  api_instance.update_sender_setting(update_sender_setting_input_object)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_sender_setting: #{e}"
end
```

#### Using the update_sender_setting_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> update_sender_setting_with_http_info(update_sender_setting_input_object)

```ruby
begin
  # Change sender settings
  data, status_code, headers = api_instance.update_sender_setting_with_http_info(update_sender_setting_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_sender_setting_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **update_sender_setting_input_object** | [**UpdateSenderSettingRequest**](UpdateSenderSettingRequest.md) |  |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*


## update_template

> <ResourceLinkResponse> update_template(id, update_template_input_object)

Update a template

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
update_template_input_object = TextMagic::CreateTemplateRequest.new # CreateTemplateRequest | 

begin
  # Update a template
  result = api_instance.update_template(id, update_template_input_object)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_template: #{e}"
end
```

#### Using the update_template_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> update_template_with_http_info(id, update_template_input_object)

```ruby
begin
  # Update a template
  data, status_code, headers = api_instance.update_template_with_http_info(id, update_template_input_object)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->update_template_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **update_template_input_object** | [**CreateTemplateRequest**](CreateTemplateRequest.md) |  |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## upload_avatar

> upload_avatar(image)

Upload an avatar

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
image = File.new('/path/to/some/file') # File | User avatar. Should be a PNG or JPG file not more than 10 MB.

begin
  # Upload an avatar
  api_instance.upload_avatar(image)
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_avatar: #{e}"
end
```

#### Using the upload_avatar_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> upload_avatar_with_http_info(image)

```ruby
begin
  # Upload an avatar
  data, status_code, headers = api_instance.upload_avatar_with_http_info(image)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_avatar_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **image** | **File** | User avatar. Should be a PNG or JPG file not more than 10 MB. |  |

### Return type

nil (empty response body)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## upload_contact_avatar

> <ResourceLinkResponse> upload_contact_avatar(id, image)

Upload an avatar

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
image = File.new('/path/to/some/file') # File | Contact avatar. Should be a PNG or JPG file not more than 10 MB.

begin
  # Upload an avatar
  result = api_instance.upload_contact_avatar(id, image)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_contact_avatar: #{e}"
end
```

#### Using the upload_contact_avatar_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> upload_contact_avatar_with_http_info(id, image)

```ruby
begin
  # Upload an avatar
  data, status_code, headers = api_instance.upload_contact_avatar_with_http_info(id, image)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_contact_avatar_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **image** | **File** | Contact avatar. Should be a PNG or JPG file not more than 10 MB. |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## upload_list_avatar

> <ResourceLinkResponse> upload_list_avatar(id, image)

Add an avatar for a list

Add an avatar for a list

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
id = 1 # Integer | 
image = File.new('/path/to/some/file') # File | List avatar. Should be a PNG or JPG file not more than 10 MB.

begin
  # Add an avatar for a list
  result = api_instance.upload_list_avatar(id, image)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_list_avatar: #{e}"
end
```

#### Using the upload_list_avatar_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ResourceLinkResponse>, Integer, Hash)> upload_list_avatar_with_http_info(id, image)

```ruby
begin
  # Add an avatar for a list
  data, status_code, headers = api_instance.upload_list_avatar_with_http_info(id, image)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ResourceLinkResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_list_avatar_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **image** | **File** | List avatar. Should be a PNG or JPG file not more than 10 MB. |  |

### Return type

[**ResourceLinkResponse**](ResourceLinkResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## upload_message_attachment

> <UploadMessageAttachmentResponse> upload_message_attachment(file)

Upload message attachment

Upload a new file to insert it as a link.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
file = File.new('/path/to/some/file') # File | Attachment. Supports .jpg, .gif, .png, .pdf, .txt, .csv, .doc, .docx, .xls, .xlsx, .ppt, .pptx & .vcf file formats.

begin
  # Upload message attachment
  result = api_instance.upload_message_attachment(file)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_message_attachment: #{e}"
end
```

#### Using the upload_message_attachment_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<UploadMessageAttachmentResponse>, Integer, Hash)> upload_message_attachment_with_http_info(file)

```ruby
begin
  # Upload message attachment
  data, status_code, headers = api_instance.upload_message_attachment_with_http_info(file)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <UploadMessageAttachmentResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_message_attachment_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **file** | **File** | Attachment. Supports .jpg, .gif, .png, .pdf, .txt, .csv, .doc, .docx, .xls, .xlsx, .ppt, .pptx &amp; .vcf file formats. |  |

### Return type

[**UploadMessageAttachmentResponse**](UploadMessageAttachmentResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## upload_message_mms_attachment

> <UploadMessageAttachmentResponse> upload_message_mms_attachment(file)

Upload message mms attachment

Upload a new file to mms.

### Examples

```ruby
require 'time'
require 'textmagic_rest_client'
# setup authorization
TextMagic.configure do |config|
  # Configure HTTP basic authorization: BasicAuth
  config.username = 'YOUR USERNAME'
  config.password = 'YOUR PASSWORD'
end

api_instance = TextMagic::TextMagicApi.new
file = File.new('/path/to/some/file') # File | Attachment. Supports .jpg, .gif, .png, .pdf, .txt, .csv, .doc, .docx, .xls, .xlsx, .ppt, .pptx & .vcf file formats.

begin
  # Upload message mms attachment
  result = api_instance.upload_message_mms_attachment(file)
  p result
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_message_mms_attachment: #{e}"
end
```

#### Using the upload_message_mms_attachment_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<UploadMessageAttachmentResponse>, Integer, Hash)> upload_message_mms_attachment_with_http_info(file)

```ruby
begin
  # Upload message mms attachment
  data, status_code, headers = api_instance.upload_message_mms_attachment_with_http_info(file)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <UploadMessageAttachmentResponse>
rescue TextMagic::ApiError => e
  puts "Error when calling TextMagicApi->upload_message_mms_attachment_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **file** | **File** | Attachment. Supports .jpg, .gif, .png, .pdf, .txt, .csv, .doc, .docx, .xls, .xlsx, .ppt, .pptx &amp; .vcf file formats. |  |

### Return type

[**UploadMessageAttachmentResponse**](UploadMessageAttachmentResponse.md)

### Authorization

[BasicAuth](../README.md#BasicAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

