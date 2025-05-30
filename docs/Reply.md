# SunshineConversationsClient::Reply

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **String** | The type of action. | 
**text** | **String** | The button text. We recommend a non-empty value because some channels may not support empty ones. Text longer than 20 characters will be truncated on Facebook Messenger, and longer than 40 characters will be truncated on Web Messenger, iOS, and Android. | 
**payload** | **String** | A string payload to help you identify the action context. Used when posting the reply. You can also use metadata for more complex needs. | 
**metadata** | **Hash&lt;String, Object&gt;** | Flat object containing custom properties. Strings, numbers and booleans  are the only supported format that can be passed to metadata. The metadata is limited to 4KB in size.  | [optional] 
**icon_url** | **String** | An icon to render next to the reply option. | [optional] 

## Code Sample

```ruby
require 'SunshineConversationsClient'

instance = SunshineConversationsClient::Reply.new(type: null,
                                 text: null,
                                 payload: null,
                                 metadata: {&quot;lang&quot;:&quot;en-ca&quot;},
                                 icon_url: null)
```


