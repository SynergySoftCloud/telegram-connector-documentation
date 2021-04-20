
# **Telegram messenger Connector 1.0.0 Reference - Mule 4**

Support Category: Certified

Anypoint Connector for Telegram messenger (Telegram Connector) enables you to create apps that can send, update and delete messages from the chat-bot conversation and react to Telegram messenger chat-bot events such as sending messages by user.

<span style="text-decoration:underline;">Release Notes: Telegram messenger Connector Release Notes</span>


### **Config**


#### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Name
   </td>
   <td>String
   </td>
   <td>The name for this configuration. Connectors reference the configuration with this name.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Connection
   </td>
   <td><span style="text-decoration:underline;">Chatbot Auth Token Connection Provider</span>
   </td>
   <td>The connection types to provide to this configuration.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>1
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>MINUTES
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>AUTO
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name
   </td>
   <td>String
   </td>
   <td>The identifier of this element used to reference it in other components
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Expiration Policy
   </td>
   <td><a href="#ExpirationPolicy">Expiration Policy</a>
   </td>
   <td>Configures the minimum amount of time that a dynamic configuration instance can remain idle before Mule considers it eligible for expiration. This does not mean that the platform expires the instance at the exact moment that it becomes eligible. Mule purges the instances as appropriate.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



#### **Connection Types**


##### 
**Chatbot Auth Token Connection Provider**


###### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Default Headers
   </td>
   <td>Array of <a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#DefaultHeader">Default Header</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Query Parameters
   </td>
   <td>Array of <a href="#DefaultQueryParam">Default Query Param</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Connection Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for establishing connections to the remote service
   </td>
   <td>30
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Connection Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit that qualifies the Connection Timeout
   </td>
   <td>SECONDS
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Use Persistent Connections
   </td>
   <td>Boolean
   </td>
   <td>If false, each connection will be closed after the first request is completed.
   </td>
   <td>true
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Max Connections
   </td>
   <td>Number
   </td>
   <td>The maximum number of outbound connections to keep open at the same time
   </td>
   <td>-1
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Connection Idle Timeout
   </td>
   <td>Number
   </td>
   <td>A timeout for how long a connection can remain idle before it is closed
   </td>
   <td>30
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Connection Idle Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit that qualifies the connection Idle Timeout
   </td>
   <td>SECONDS
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Proxy Config
   </td>
   <td><a href="#Proxy">Proxy</a>
   </td>
   <td>The reusable configuration element for outbound connections through a proxy
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Stream Response
   </td>
   <td>Boolean
   </td>
   <td>Whether or not received responses should be streamed
   </td>
   <td>false
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Buffer Size
   </td>
   <td>Number
   </td>
   <td>The space in bytes for the buffer where the HTTP response will be stored.
   </td>
   <td>-1
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Base Uri
   </td>
   <td>String
   </td>
   <td>Parameter base URI, each instance/tenant gets its own
   </td>
   <td><a href="https://api.twilio.com/">https://</a><span style="text-decoration:underline;">api.telegram.org</span>
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>Secure token
   </td>
   <td>String
   </td>
   <td>The token is a string along the lines of 110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw that is required to authorize the bot and send requests to the Bot API. Keep your token secure and store it safely, it can be used by anyone to control your bot.
   </td>
   <td>
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>TLS Configuration
   </td>
   <td><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Tls">Tls</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection
   </td>
   <td><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnection">Reconnection</a>
   </td>
   <td>When the application is deployed, a connectivity test is performed on all connectors. If set to true, deployment fails if the test doesn’t pass after exhausting the associated reconnection strategy.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



## **Supported Operations**



*   [Get Updates](#GetUpdates)
*   [Delete Message](#DeleteMessage)
*   <span style="text-decoration:underline;">Send text message</span>
*   <span style="text-decoration:underline;">Send video message</span>
*   <span style="text-decoration:underline;">Send audio message</span>
*   <span style="text-decoration:underline;">Send animation message</span>
*   <span style="text-decoration:underline;">Send document message</span>
*   <span style="text-decoration:underline;">Send media group message</span>
*   <span style="text-decoration:underline;">Send photo message</span>
*   <span style="text-decoration:underline;">Edit caption of media message</span>
*   <span style="text-decoration:underline;">Edit media message</span>
*   <span style="text-decoration:underline;">Edit text message</span>


## **Operations**


## 
**Get Updates**


```
<telegram:get-bot-get-updates-by-token>
```


Get Updates This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/getUpdates endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Offset
   </td>
   <td>Number
   </td>
   <td>Identifier of the first update to be returned. Must be greater by one than the highest among the identifiers of previously received updates. By default, updates starting with the earliest unconfirmed update are returned. An update is considered confirmed as soon as getUpdates is called with an offset higher than its update_id. The negative offset can be specified to retrieve updates starting from -offset update from the end of the updates queue. All previous updates will be forgotten.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Limit
   </td>
   <td>Number
   </td>
   <td>Limits the number of updates to be retrieved. Values between 1-100 are accepted. Defaults to 100.
   </td>
   <td>100
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Timeout
   </td>
   <td>Number
   </td>
   <td>Timeout in seconds for long polling. Defaults to 0, i.e. usual short polling. Should be positive, short polling should be used for testing purposes only.
   </td>
   <td>0
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Send text message**



```
<telegram:create-bot-send-message-by-token>
```


Send text message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/sendMessage.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Text
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Send animation message**



```
<telegram:create-bot-send-animation-by-token>
```


Send animation message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/sendAnimation.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Animation
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the request content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Send audio message**



```
<telegram:create-bot-send-audio-by-token>
```


Send audio message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/sendAudio.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Audio
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Send document message**



```
<telegram:create-bot-send-document-by-token>
```


Send document message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/sendDocument.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Document
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Send media group message**



```
<telegram:create-bot-send-media-group-by-token>
```


Send media group message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/sendMediaGroup.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Media group
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Send photo message**



```
<telegram:create-bot-send-photo-by-token>
```


Send photo message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/sendAnimation.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Animation
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the request content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Send video message**



```
<telegram:create-bot-send-video-by-token>
```


Send video message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/sendVideo.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Video
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Delete message**



```
<telegram:create-bot-delete-message-by-token>
```


Delete message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/deleteMessage.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Object - Delete message
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Edit caption of media message**



```
<telegram:create-bot-edit-message-caption-by-token>
```


Edit caption of media message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/editMessageCaption.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Edit Message caption
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Edit media message**



```
<telegram:create-bot-edit-message-media-by-token>
```


Edit media message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/editMessageMedia.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Edit Media object
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE

## 
**Edit text message**



```
<telegram:create-bot-edit-message-text-by-token>
```


Edit text message This operation makes an HTTPS GET request to the https://api.telegram.org:443/bot{secure.token}/editMessageText.json endpoint


### 
**Parameters**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Configuration
   </td>
   <td>String
   </td>
   <td>The name of the configuration to use.
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Text
   </td>
   <td>Object
   </td>
   <td>the content to use
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Config Ref
   </td>
   <td>ConfigurationProvider
   </td>
   <td>The name of the configuration to use to execute this component
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Streaming Strategy
   </td>
   <td>
<ul>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableInMemoryStream">Repeatable In Memory Stream</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#RepeatableFileStoreStream">Repeatable File Store Stream</a>

<li>non-repeatable-stream
</li>
</ul>
   </td>
   <td>Configure if repeatable streams should be used and their behaviour
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Query Parameters
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Custom Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout
   </td>
   <td>Number
   </td>
   <td>The timeout for the request to the remote service.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Response Timeout Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit which qualifies the Response Timeout}
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Streaming Type
   </td>
   <td>Enumeration, one of:
<ul>

<li>AUTO

<li>ALWAYS

<li>NEVER
</li>
</ul>
   </td>
   <td>Defines if the request should be sent using streaming. Setting the value to AUTO will automatically define the best strategy based on the requested content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Variable
   </td>
   <td>String
   </td>
   <td>The name of a variable to store the operation’s output.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Target Value
   </td>
   <td>String
   </td>
   <td>An expression to evaluate against the operation’s output and store the expression outcome in the target variable
   </td>
   <td>#[payload]
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li> \
<a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Reconnect">Reconnect</a>

<li><a href="https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>A retry strategy in case of connectivity errors
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Output**


<table>
  <tr>
   <td>Type
   </td>
   <td>Any
   </td>
  </tr>
  <tr>
   <td>Attributes Type
   </td>
   <td><a href="#HttpResponseAttributes">HTTP Response Attributes</a>
   </td>
  </tr>
</table>



### 
**For Configurations**



*   [Config](https://docs.mulesoft.com/twilio-connector/4.0/twilio-connector-reference#Config)

### 
**Throws**

*   TELEGRAM:BAD_REQUEST
*   TELEGRAM:CLIENT_ERROR
*   TELEGRAM:CONNECTIVITY
*   TELEGRAM:INTERNAL_SERVER_ERROR
*   TELEGRAM:NOT_ACCEPTABLE
*   TELEGRAM:NOT_FOUND
*   TELEGRAM:RETRY_EXHAUSTED
*   TELEGRAM:SERVER_ERROR
*   TELEGRAM:SERVICE_UNAVAILABLE
*   TELEGRAM:TIMEOUT
*   TELEGRAM:TOO_MANY_REQUESTS
*   TELEGRAM:UNAUTHORIZED
*   TELEGRAM:UNSUPPORTED_MEDIA_TYPE


## **Types**


### 
**Default Header**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Key
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Value
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
</table>



### 
**Default Query Param**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Key
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Value
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
</table>



### 
**Proxy**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Host
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Port
   </td>
   <td>Number
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Username
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Password
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Non Proxy Hosts
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Tls**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Enabled Protocols
   </td>
   <td>String
   </td>
   <td>A comma-separated list of protocols enabled for this context.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Enabled Cipher Suites
   </td>
   <td>String
   </td>
   <td>A comma-separated list of cypher suites enabled for this context.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Trust Store
   </td>
   <td><a href="#TrustStore">Trust Store</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Key Store
   </td>
   <td><a href="#KeyStore">Key Store</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Revocation Check
   </td>
   <td>
<ul>

<li> \
<a href="#StandardRevocationCheck">Standard Revocation Check</a>

<li><a href="#CustomOcspResponder">Custom Ocsp Responder</a>

<li><a href="#CrlFile">Crl File</a>
</li>
</ul>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Trust Store**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Path
   </td>
   <td>String
   </td>
   <td>The location (which will be resolved relative to the current classpath and file system, if possible) of the trust store.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Password
   </td>
   <td>String
   </td>
   <td>The password used to protect the trust store.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Type
   </td>
   <td>String
   </td>
   <td>The type of store used.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Algorithm
   </td>
   <td>String
   </td>
   <td>The algorithm used by the trust store.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Insecure
   </td>
   <td>Boolean
   </td>
   <td>If true, no certificate validations will be performed, rendering connections vulnerable to attacks. Use at your own risk.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Key Store**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Path
   </td>
   <td>String
   </td>
   <td>The location (which will be resolved relative to the current classpath and file system, if possible) of the key store.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Type
   </td>
   <td>String
   </td>
   <td>The type of store used.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Alias
   </td>
   <td>String
   </td>
   <td>When the key store contains many private keys, this attribute indicates the alias of the key that should be used. If not defined, the first key in the file will be used by default.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Key Password
   </td>
   <td>String
   </td>
   <td>The password used to protect the private key.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Password
   </td>
   <td>String
   </td>
   <td>The password used to protect the key store.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Algorithm
   </td>
   <td>String
   </td>
   <td>The algorithm used by the key store.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Standard Revocation Check**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Only End Entities
   </td>
   <td>Boolean
   </td>
   <td>Only verify the last element of the certificate chain.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Prefer Crls
   </td>
   <td>Boolean
   </td>
   <td>Try CRL instead of OCSP first.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>No Fallback
   </td>
   <td>Boolean
   </td>
   <td>Do not use the secondary checking method (the one not selected before).
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Soft Fail
   </td>
   <td>Boolean
   </td>
   <td>Avoid verification failure when the revocation server can not be reached or is busy.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Custom Ocsp Responder**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Url
   </td>
   <td>String
   </td>
   <td>The URL of the OCSP responder.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Cert Alias
   </td>
   <td>String
   </td>
   <td>Alias of the signing certificate for the OCSP response (must be in the trust store), if present.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Crl File**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Path
   </td>
   <td>String
   </td>
   <td>The path to the CRL file.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Reconnection**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Fails Deployment
   </td>
   <td>Boolean
   </td>
   <td>When the application is deployed, a connectivity test is performed on all connectors. If set to true, deployment fails if the test doesn’t pass after exhausting the associated reconnection strategy.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reconnection Strategy
   </td>
   <td>
<ul>

<li><a href="#Reconnect">Reconnect</a>

<li><a href="#ReconnectForever">Reconnect Forever</a>
</li>
</ul>
   </td>
   <td>The reconnection strategy to use.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Reconnect**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Frequency
   </td>
   <td>Number
   </td>
   <td>How often in milliseconds to reconnect
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Blocking
   </td>
   <td>Boolean
   </td>
   <td>If false, the reconnection strategy will run in a separate, non-blocking thread
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Count
   </td>
   <td>Number
   </td>
   <td>How many reconnection attempts to make.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Reconnect Forever**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Frequency
   </td>
   <td>Number
   </td>
   <td>How often in milliseconds to reconnect
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Blocking
   </td>
   <td>Boolean
   </td>
   <td>If false, the reconnection strategy will run in a separate, non-blocking thread
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Expiration Policy**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Max Idle Time
   </td>
   <td>Number
   </td>
   <td>A scalar time value for the maximum amount of time a dynamic configuration instance should be allowed to be idle before it’s considered eligible for expiration
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Time Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>NANOSECONDS

<li>MICROSECONDS

<li>MILLISECONDS

<li>SECONDS

<li>MINUTES

<li>HOURS

<li>DAYS
</li>
</ul>
   </td>
   <td>A time unit that qualifies the maxIdleTime attribute
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Http Response Attributes**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Status Code
   </td>
   <td>Number
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Headers
   </td>
   <td>Object
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
  <tr>
   <td>Reason Phrase
   </td>
   <td>String
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>x
   </td>
  </tr>
</table>



### 
**Repeatable In Memory Stream**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Initial Buffer Size
   </td>
   <td>Number
   </td>
   <td>The amount of memory that will be allocated to consume the stream and provide random access to it. If the stream contains more data than can be fit into this buffer, then the buffer expands according to the bufferSizeIncrement attribute, with an upper limit of maxInMemorySize.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Buffer Size Increment
   </td>
   <td>Number
   </td>
   <td>This is by how much the buffer size expands if it exceeds its initial size. Setting a value of zero or lower means that the buffer should not expand, meaning that a STREAM_MAXIMUM_SIZE_EXCEEDED error is raised when the buffer gets full.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Max Buffer Size
   </td>
   <td>Number
   </td>
   <td>The maximum amount of memory to use. If more than that is used then a STREAM_MAXIMUM_SIZE_EXCEEDED error is raised. A value lower than or equal to zero means no limit.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Buffer Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>BYTE

<li>KB

<li>MB

<li>GB
</li>
</ul>
   </td>
   <td>The unit in which all these attributes are expressed
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### 
**Repeatable File Store Stream**


<table>
  <tr>
   <td><strong>Field</strong>
   </td>
   <td><strong>Type</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Default Value</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>In Memory Size
   </td>
   <td>Number
   </td>
   <td>Defines the maximum memory that the stream should use to keep data in memory. If more than that is consumed content on the disk is buffered.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Buffer Unit
   </td>
   <td>Enumeration, one of:
<ul>

<li>BYTE

<li>KB

<li>MB

<li>GB
</li>
</ul>
   </td>
   <td>The unit in which maxInMemorySize is expressed
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



## **See Also**



*   [Introduction to Anypoint Connectors](https://docs.mulesoft.com/connectors/introduction/introduction-to-anypoint-connectors)
*   [MuleSoft Help Center](https://help.mulesoft.com/)
