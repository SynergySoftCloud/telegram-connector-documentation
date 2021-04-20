
# **Telegram messenger Connector 1.0.0 - Mule 4**

Support Category: Certified

Anypoint Connector for Telegram messenger (Telegram Connector) enables you to create apps that can send, update and delete messages from the chat-bot conversation and react to the Telegram messenger Chatbot events such as sending messages by user.

Telegram Connector enables you to connect to the Telegram messenger APIs. 

This connector works with the Telegram messenger REST API. Each API call uses a request/response pattern over an HTTPS connection. All required request headers, error handling, and HTTPS connection configurations are built into the connector.

For compatibility information and fixed issues, see the Telegram messenger Connector release notes.


## 
**Prerequisites**

To use this connector, you must be familiar with:



*   The REST APIs
*   Anypoint Connectors
*   Mule runtime engine (Mule)
*   Elements and global elements in a Mule flow
*   Creating a Mule app using Anypoint Studio (Studio)

Before creating an app, you must have:



*   Access to the Telegram messenger [Chatbot](https://core.telegram.org/bots), which requires a Telegram messenger security token. You can learn about obtaining tokens and generating new ones in this [document](https://core.telegram.org/bots#6-botfather). \


## 
**Limitations**

*   Telegram Connector does not expose all possible operations of the Telegram messenger APIs.

## 
**Authentication Types**


Telegram Connector connections use the following authentication types:



*   Authentication token. Uses a secure token for authentication

## 
**Installation**



## You can install a connector in Anypoint Studio using the instructions in [To Import an Asset from Exchange.](https://docs.mulesoft.com/studio/6/import-asset-exchange-task)


## 
**Use Studio to Configure Telegram messenger Connector 1.0.0 - Mule 4**

Anypoint Studio (Studio) editors help you design and update your Mule applications, properties, and configuration files.

To add and configure a connector in Studio:



1. [Create a Mule project](https://docs.google.com/document/d/1WN4N6m5-0E0NdYyJe3Ie3QB1-UhyEuPaRsm04uJrHDE/edit#create-mule-project)<span style="text-decoration:underline;">.</span>
2. [Add the connector to your Mule project](https://docs.google.com/document/d/1WN4N6m5-0E0NdYyJe3Ie3QB1-UhyEuPaRsm04uJrHDE/edit#add-connector-to-project)<span style="text-decoration:underline;">.</span>
3. [Configure a source for the connector’s flow](https://docs.google.com/document/d/1WN4N6m5-0E0NdYyJe3Ie3QB1-UhyEuPaRsm04uJrHDE/edit#configure-input-source)<span style="text-decoration:underline;">.</span>
4. [Add a connector operation to the flow](https://docs.google.com/document/d/1WN4N6m5-0E0NdYyJe3Ie3QB1-UhyEuPaRsm04uJrHDE/edit#add-connector-operation)<span style="text-decoration:underline;">.</span>
5. [Configure a global element for the connector](https://docs.google.com/document/d/1WN4N6m5-0E0NdYyJe3Ie3QB1-UhyEuPaRsm04uJrHDE/edit#configure-global-element)<span style="text-decoration:underline;">.</span>
6. [Configure the Other Connector Fields](https://docs.google.com/document/d/1WN4N6m5-0E0NdYyJe3Ie3QB1-UhyEuPaRsm04uJrHDE/edit#configure-other-fields)<span style="text-decoration:underline;">.</span>

When you run the connector, you can view the app log to check for problems in real time, as described in [View the App Log](https://docs.google.com/document/d/1WN4N6m5-0E0NdYyJe3Ie3QB1-UhyEuPaRsm04uJrHDE/edit#view-app-log)<span style="text-decoration:underline;">.</span>


## 
**Create a Mule Project**

In Studio, create a new Mule project in which to add and configure the connector:



1. In Studio, select File > New > Mule Project.
2. Enter a name for your Mule project and click Finish.

## 
**Add the Connector to Your Mule Project**


Add Telegram messenger Connector to your Mule project to automatically populate the XML code with the connector’s namespace and schema location and to add the required dependencies to the project’s `pom.xml` file:



1. In the Mule Palette view, click (X) Search in Exchange.
2. In the Add Dependencies to Project window, type `telegram` in the search field.
3. Click Telegram messenger Connector in Available modules.
4. Click Add.
5. Click Finish.

Adding a connector to a Mule project in Studio does not make that connector available to other projects in your Studio workspace.


## 
**Configure a Source**

A source initiates a flow when a specified condition is met. You can configure one of these sources to use with Telegram messenger Connector:



*   HTTP Listener \
Initiates a flow each time it receives a request on the configured host and port
*   Scheduler \
Initiates a flow when a time-based condition is met

For example, to configure an HTTP Listener source, follow these steps:



1. In the Mule Palette view, select HTTP > Listener.
2. Drag Listener to the Studio canvas.
3. On the Listener configuration screen, optionally change the value of the Display Name field.
4. Specify a value for the Path field.
5. Click the plus sign (+) next to the Connector configuration field to configure a global element that can be used by all instances of the HTTP Listener source in the app.
6. On the General tab, specify the connection information for the connector.
7. On the TLS tab, optionally specify the TLS information for the connector.
8. On the Advanced tab, optionally specify reconnection information, including a reconnection strategy.
9. Click OK.

## 
**Add a Connector Operation to the Flow**


When you add a connector operation to your flow, you are specifying an action for that connector to perform.

To add an operation for Telegram messenger Connector, follow these steps:



1. In the Mule Palette view, select Telegram Connector and then select the desired operation.
2. Drag the operation onto the Studio canvas and to the right of the source.

## 
**Configure a Global Element for the Connector**


When you configure a connector, it’s best to configure a global element that all instances of that connector in the app can use. Configuring a global element requires you to provide the authentication credentials that the connector requires to access the target Telegram messenger API. Telegram Connector supports Secure token authentication.

To configure the global element for Telegram Connector, follow these steps:



1. Select the name of the connector in the Studio canvas.
2. Select the operation in the Studio canvas.
3. In the configuration screen for the operation, click the plus sign (+) next to the Connector configuration field to access the global element configuration fields. \
You can reference a configuration file that contains ANT-style property placeholders (recommended), or you can enter your authorization credentials in the global configuration properties. For information about the benefits of using property placeholders and how to configure them, see [Anypoint Connector Configuration](https://docs.mulesoft.com/connectors/introduction/intro-connector-configuration-overview).
4. In the Telegram Connector Config window, in the General tab, enter the following configuration values:

<table>
  <tr>
   <td>
<strong>Field</strong>
   </td>
   <td><strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td>Name
   </td>
   <td>Enter a name for this configuration to reference it later.
   </td>
  </tr>
  <tr>
   <td>Base URL
   </td>
   <td>Enter the Telegram messenger API instance URL. Default value is https://api.telegram.org
   </td>
  </tr>
  <tr>
   <td>Secure token
   </td>
   <td>The token is a string along the lines of 110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw that is required to authorize the bot and send requests to the Bot API. Keep your token secure and store it safely, it can be used by anyone to control your bot.
   </td>
  </tr>
</table>




5. On the Advanced tab, optionally specify an expiration policy.
6. Click Test Connection to confirm that Mule can connect with the specified server.
7. Click OK.

## 
**Configure the Get Updates Operation**

*   Drag the Get Updates operation to the Studio canvas.
*   Configure the Get Updates operation in the General tab:

Use this method to receive incoming updates using long polling (wiki). An Array of Update objects is returned. In order to avoid getting duplicate updates, recalculate offset after each server response.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>offset
   </td>
   <td>Integer
   </td>
   <td>dentifier of the first update to be returned. Must be greater by one than the highest among the identifiers of previously received updates. By default, updates starting with the earliest unconfirmed update are returned. An update is considered confirmed as soon as getUpdates is called with an offset higher than its update_id. The negative offset can be specified to retrieve updates starting from -offset update from the end of the updates queue. All previous updates will forgotten.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>limit
   </td>
   <td>Integer
   </td>
   <td>Limits the number of updates to be retrieved. Values between 1-100 are accepted. Defaults to 100.
   </td>
   <td>100
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>timeout
   </td>
   <td>Integer
   </td>
   <td>Timeout in seconds for long polling. Defaults to 0, i.e. usual short polling. Should be positive, short polling should be used for testing purposes only.
   </td>
   <td>0
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Allowed updates
   </td>
   <td>	Array of String
   </td>
   <td>A JSON-serialized list of the update types you want your bot to receive. For example, specify [“message”, “edited_channel_post”, “callback_query”] to only receive updates of these types. See Update for a complete list of available update types. Specify an empty list to receive all update types except chat_member (default). If not specified, the previous setting will be used.
<p>
Please note that this parameter doesn't affect updates created before the call to the getUpdates, so unwanted updates may be received for a short period of time.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Send text message Operation**



*   Drag the Send text message operation to the Studio canvas.
*   Configure the Send text message operation in the General tab:

Use this method to send text messages. On success, the sent Message is returned.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#sendmessage">Link for the type of Text message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Send video message Operation**



*   Drag the Send video message operation to the Studio canvas.
*   Configure the Send video message operation in the General tab:

Use this method to send video files, Telegram clients support mp4 videos (other formats may be sent as Document). On success, the sent Message is returned. Bots can currently send video files of up to 50 MB in size, this limit may be changed in the future.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#sendvideo">Link for the type of Video message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Send photo message Operation**



*   Drag the Send photo message operation to the Studio canvas.
*   Configure the Send photo message operation in the General tab:

Use this method to send photos. On success, the sent Message is returned.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#sendphoto">Link for the type of Photo message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Send media group message Operation**



*   Drag the Send media group message operation to the Studio canvas.
*   Configure the Send media group message operation in the General tab:

Use this method to send a group of photos, videos, documents or audios as an album. Documents and audio files can be only grouped in an album with messages of the same type. On success, an array of Messages that were sent is returned.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#sendmediagroup">Link for the type of Media group message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Send document message Operation**



*   Drag the Send document message operation to the Studio canvas.
*   Configure the Send document message operation in the General tab:

Use this method to send general files. On success, the sent Message is returned. Bots can currently send files of any type of up to 50 MB in size, this limit may be changed in the future.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#senddocument">Link for the type of Document message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Send audio message Operation**



*   Drag the Send audio message operation to the Studio canvas.
*   Configure the Send audio message operation in the General tab:

Use this method to send audio files, if you want Telegram clients to display them in the music player. Your audio must be in the .MP3 or .M4A format. On success, the sent Message is returned. Bots can currently send audio files of up to 50 MB in size, this limit may be changed in the future.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#sendaudio">Link for the type of Audio message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Send animation message Operation**



*   Drag the Send animation message operation to the Studio canvas.
*   Configure the Send animation message operation in the General tab:

Use this method to send animation files (GIF or H.264/MPEG-4 AVC video without sound). On success, the sent Message is returned. Bots can currently send animation files of up to 50 MB in size, this limit may be changed in the future.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#sendanimation">Link for the type of Animation message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Send document message Operation**



*   Drag the Send document message operation to the Studio canvas.
*   Configure the Send document message operation in the General tab:

Use this method to send general files. On success, the sent Message is returned. Bots can currently send files of any type of up to 50 MB in size, this limit may be changed in the future.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#sendphoto">Link for the type of Document message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Delete message Operation**



*   Drag the Delete message operation to the Studio canvas.
*   Configure the Delete message operation in the General tab:

Use this method to delete a message, including service messages, with the following limitations:

- A message can only be deleted if it was sent less than 48 hours ago.

- A dice message in a private chat can only be deleted if it was sent more than 24 hours ago.

- Bots can delete outgoing messages in private chats, groups, and supergroups.

- Bots can delete incoming messages in private chats.

- Bots granted can_post_messages permissions can delete outgoing messages in channels.

- If the bot is an administrator of a group, it can delete any message there.

- If the bot has can_delete_messages permission in a supergroup or a channel, it can delete any message there.

Returns True on success.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#deletemessage">Link for the type of Delete message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Edit caption of media message Operation**



*   Drag the Edit caption of media message operation to the Studio canvas.
*   Configure the Edit caption of media message operation in the General tab:

Use this method to edit captions of messages. On success, if the edited message is not an inline message, the edited Message is returned, otherwise True is returned.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#editmessagecaption">Link for the type of  Edit caption of media message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Edit media message Operation**



*   Drag the Edit media message operation to the Studio canvas.
*   Configure the Edit media message operation in the General tab:

Use this method to edit animation, audio, document, photo, or video messages. If a message is part of a message album, then it can be edited only to an audio for audio albums, only to a document for document albums and to a photo or a video otherwise. When an inline message is edited, a new file can't be uploaded. Use a previously uploaded file via its file_id or specify a URL. On success, if the edited message was sent by the bot, the edited Message is returned, otherwise True is returned.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#editmessagemedia">Link for the type of  Edit media message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**Configure the Edit text message Operation**



*   Drag the Edit text message operation to the Studio canvas.
*   Configure the Edit text message operation in the General tab:

Use this method to edit text and [game](https://core.telegram.org/bots/api#games) messages. On success, if the edited message is not an inline message, the edited [Message](https://core.telegram.org/bots/api#message) is returned, otherwise _True_ is returned.


<table>
  <tr>
   <td>Name
   </td>
   <td>Type
   </td>
   <td>Description
   </td>
   <td>Default Value
   </td>
   <td>Required
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
   <td>Body
   </td>
   <td>String
   </td>
   <td>The Body must be of the type required the Telegram messenger API. <a href="https://core.telegram.org/bots/api#editmessagetext">Link for the type of  Edit text message</a>. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


In the Advanced tab, configure the reconnection strategy.


## 
**View the App Log**

To check for problems, you can view the app log as follows:



*   If you’re running the app from Anypoint Platform, the output is visible in the Anypoint Studio console window.
*   If you’re running the app using Mule from the command line, the app log is visible in your OS console.

Unless the log file path is customized in the app’s log file (`log4j2.xml`), you can also view the app log in the default location `MULE_HOME/logs/&lt;app-name>.log`.


## 
**See Also**



*   [Introduction to Anypoint Connectors](https://docs.mulesoft.com/connectors/introduction/introduction-to-anypoint-connectors)
*   [Use Studio to Configure a Connector](https://docs.mulesoft.com/connectors/introduction/intro-config-use-studio)
*   [Telegram Connector Reference](https://docs.google.com/document/d/1WN4N6m5-0E0NdYyJe3Ie3QB1-UhyEuPaRsm04uJrHDE/edit#telegramconnector-reference)
*   [Use Exchange to Discover Connectors, Templates, and Examples](https://docs.mulesoft.com/connectors/introduction/intro-use-exchange)
*   [Telegram messanger’s REST APIs](https://core.telegram.org/bots/api)
*   [MuleSoft Help Center](https://help.mulesoft.com/)
