# SunshineConversationsClient::Content

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **String** | The type of message. | [default to &#39;template&#39;]
**text** | **String** | The fallback text message used when location messages are not supported by the channel. | [optional] [readonly] 
**actions** | [**Array&lt;ActionSubset&gt;**](ActionSubset.md) | An array of objects representing the actions associated with the message. The array length is limited by the third party channel. | [optional] 
**payload** | **String** | The payload of a [reply button](https://docs.smooch.io/guide/structured-messages/#reply-buttons) response message. | [optional] 
**items** | [**Array&lt;Item&gt;**](Item.md) | An array of objects representing the items associated with the message. Only present in carousel and list type messages. | 
**display_settings** | [**CarouselMessageDisplaySettings**](CarouselMessageDisplaySettings.md) |  | [optional] 
**media_url** | **String** | The URL for media, such as an image, attached to the message. &lt;aside class&#x3D;\&quot;notice\&quot;&gt;Note that for private attachments an authorization header is required to access the mediaUrl. See &lt;a href&#x3D;\&quot;https://developer.zendesk.com/documentation/zendesk-web-widget-sdks/messaging_private_attachments/\&quot;&gt;Configuring private attachments for messaging&lt;/a&gt; guide for more details.&lt;/aside&gt;  | 
**media_size** | **Float** | The size of the media in bytes. | [optional] [readonly] 
**media_type** | **String** | The type of media. | [optional] [readonly] 
**alt_text** | **String** | An optional description of the image for accessibility purposes. The field will be saved by default with the file name as the value. | [optional] 
**attachment_id** | **String** | An identifier used by Sunshine Conversations for internal purposes. | [optional] 
**submitted** | **Boolean** | Flag which states whether the form is submitted. | [optional] [readonly] 
**block_chat_input** | **Boolean** | true if the message should block the chat input on Web Messenger. | [optional] 
**fields** | [**Array&lt;FormResponseMessageField&gt;**](FormResponseMessageField.md) | Array of field objects that contain the submitted fields. | 
**text_fallback** | **String** | A string containing the &#x60;label: value&#x60; of all fields, each separated by a newline character. | [optional] [readonly] 
**coordinates** | [**LocationMessageCoordinates**](LocationMessageCoordinates.md) |  | 
**location** | [**LocationMessageLocation**](LocationMessageLocation.md) |  | [optional] 
**template** | [**Object**](.md) | The whatsapp template message to send. For more information, consult the [guide](https://docs.smooch.io/guide/whatsapp#sending-message-templates). &#x60;schema&#x60; must be set to &#x60;whatsapp&#x60;. | 

## Code Sample

```ruby
require 'SunshineConversationsClient'

instance = SunshineConversationsClient::Content.new(type: null,
                                 text: null,
                                 actions: null,
                                 payload: null,
                                 items: null,
                                 display_settings: null,
                                 media_url: null,
                                 media_size: null,
                                 media_type: null,
                                 alt_text: null,
                                 attachment_id: null,
                                 submitted: null,
                                 block_chat_input: null,
                                 fields: null,
                                 text_fallback: null,
                                 coordinates: null,
                                 location: null,
                                 template: null)
```


