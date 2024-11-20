# SunshineConversationsClient::AppleAllOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **String** | To configure an Apple Messages for Business integration, acquire the required information and call the Create Integration endpoint.  | [optional] [default to &#39;apple&#39;]
**business_id** | **String** | Apple Messages for Business ID. | 
**api_secret** | **String** | Your Apple API secret which is tied to your Messaging Service Provider. | 
**msp_id** | **String** | Your Messaging Service Provider ID. | 
**authentication_message_secret** | **String** | A secret used to create the state value when sending Apple authentication 2.0 messages | [optional] 

## Code Sample

```ruby
require 'SunshineConversationsClient'

instance = SunshineConversationsClient::AppleAllOf.new(type: null,
                                 business_id: 2740f141-89c1-515f-07eb-1128dd73491,
                                 api_secret: QLA//Z13paUYo/2tLReQa-43c5JEAASujGamiY/QTvs&#x3D;,
                                 msp_id: e7e495d5-bf78-531d-baf6-7f419f7fb592,
                                 authentication_message_secret: eH3Ea4329FzUGEsWkjQr1dbD1JDpn5Ygo/kbW0/f8gOQ4eHTr31bjDUcCfv3s9QaAwRgpd4sckdlSXwMOAGHBQ&#x3D;&#x3D;)
```


