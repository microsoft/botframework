
# Microsoft Bot Framework 

### [Click here to find out what's new with Bot Framework](./whats-new.md#whats-new)

The Microsoft Bot Framework is a comprehensive platform for building enterprise-grade conversational AI experiences. It includes a set of open source SDKs, tools, and services which enable developers to **build**, **test**, and **connect** bots that interact naturally with users, wherever they are. With the Microsoft Bot Framework, it is easy to create a bot with the ability to speak, listen, understand, and learn from your users with Azure Cognitive Services. 

![Bot Framework](./docs/media/Bot-Framework-header.jpg)

This repo lists the SDK, tools, and services needed to build a great conversational AI experience. Its role is to serve as a landing page and one place to find all the information required to get started. 

- [Bot Framework SDK v4](#Bot-Framework-SDK-v4)
- [Bot Framework Solutions](#Bot-Framework-Solutions)
- [Azure Bot Service](#Azure-Bot-Service)
- [Bot Framework Emulator](#Bot-Framework-Emulator)
- [Bot Framework Web Chat](#Bot-Framework-Web-Chat)
- [Bot Framework Tools](#bot-framework-cli-tools)
- [Language Understanding](#Language-Understanding)
- [QnA Maker](#QnA-Maker)
- [Dispatch](#Dispatch)
- [Speech Services](#Speech-Services)  
- [Adaptive cards](#Adaptive-Cards)
- [Analytics](#Analytics)
- [Bot Framework SDK v3](#Bot-Framework-SDK-v3)

## Bot Framework SDK v4
The Bot Framework SDK v4 is an [open source SDK][1a] that enable developers to model and build sophisticated conversation using their favorite programming language.


|   | C#  | JS  | Python |  Java | 
|---|:---:|:---:|:------:|:-----:|
|Release |[4.6 GA][1] | [4.6 GA][2] | [Beta 4][3] | [Preview 3][3a]|
|Docs | [docs][5] |[docs][5] |  | |
|Samples |[.NET Core][6], [WebAPI][10] |[Node.js][7] , [TypeScript][8], [es6][9]  | [Python][111] | | 

[1a]:https://github.com/microsoft/botframework-sdk/#readme
[1]:https://github.com/Microsoft/botbuilder-dotnet/#packages
[2]:https://github.com/Microsoft/botbuilder-js#packages
[3]:https://github.com/Microsoft/botbuilder-python#packages
[3a]:https://github.com/Microsoft/botbuilder-java#packages
[4]:https://github.com/Microsoft/botbuilder-java#packages
[5]:https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0
[6]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore
[7]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_nodejs
[8]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/typescript_nodejs
[9]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_es6
[10]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_webapi
[111]:https://github.com/Microsoft/botbuilder-python/tree/master/samples

<a name="V4-whats-new"></a>

### Bot Framework SDK v4 (v4.6 GA)
- Microsoft Teams support | [docs][00] | [C# sample][00] | [JS sample][00] :: Bot Framework SDK v4.6 adds native support for building Teams bots so that you don't have to install Teams extensions to develop bots. A bot behaves differently depending on what kind of conversation it is involved in. Bots in Teams support several kinds of conversations:
  - `teams`: Also called channel conversations
  - `personal`: Conversations between a bot and a single user
  - `groupChat`: A conversation between a bot and 2 or more users
  
- [Bot Framework CLI][00] :: As part of the effort to improve Bot Framework SDK toolset we are introducing of a new command line Interface tool that will eventually replace the suite of tools currently used during Bot development. The new CLI, called BF is being released as an early preview. << UPDATE SECTION >>

### The Bot Framework SDK v4 - (version 4.7 preview)
- [Bot Framework Composer][00] :: Bot Framework Composer is an integrated development tool for developers and multi-disciplinary team of professional conversation designers for building bots and other types of conversational software with the Microsoft Bot Framework technology stack. Within this web-based tool, you'll find everything you need to build a modern, state-of-the-art conversational experience.

- [Adaptive Dialog][47] | [docs][48] | [C# samples][49] :: Adaptive Dialogs enable developers to build conversations that can be dynamically changed as the conversation progresses.
    - Adaptive dialog now includes trigger to action pairs, recognizer, and generator. This makes every adaptive dialog self-contained and easy to compose.
    - Events have been cleaned up to correspond to activity level events and dialog level events.
    - Regex recognizer now supports 10+ prebuilt entity types
    - Triggers, actions have been refined based on feedback
    - Stability improvements and bug fixes.
- [Language Generation][43] | [docs][44] | [C# samples][45] :: Language Generation enable developers to separate logic used to generate bot's respones including ability to define multiple variations on a phrase, execute simple expressions based on context, refer to conversational memory.
    - Structured template support - with this you can now use Langauge Generation for multi-modal responses including spoken response, displayed response as well as UI cards etc.
    - Ability to import and refer to .lg files. This helps streamline organization of templates, its composability and re-usability.
    - Stability improvements and bug fixes.

- [Common Expression Language][40] | [api][41] :: Both Adaptive dialogs and Language Generation rely on and use a common expression language to power bot conversations.
    - New prebuilt functions (jpath, eval)
    - Stability improvements and bug fixes.


[40]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/common-expression-language#readme
[41]:https://github.com/Microsoft/BotBuilder-Samples/blob/master/experimental/common-expression-language/api-reference.md
[43]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation#readme
[44]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/docs
[45]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/csharp_dotnetcore
[46]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/javascript_nodejs/13.core-bot
[47]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog#readme
[48]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/docs
[49]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/csharp_dotnetcore
[50]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/declarative

[00]:http://docs.microsoft.com

## Botkit
<< UPDATE SECTION >>

## Bot Framework Solutions 
<< UPDATE SECTION >>

## Azure Bot Service

<< UPDATE SECTION >>

Azure Bot Service enables you to host intelligent, enterprise-grade bots with complete ownership and control of your data. Developers can register and connect their bots to users on Skype, Microsoft Teams, Cortana, Web Chat, and more. [Azure][27]  |  [docs][28] | [connect to channels][29] 

* **Direct Line JS Client**: If you want to use the Direct Line channel in Azure Bot Service and are not using the WebChat client, the Direct Line JS client can be used in your custom application. [Github][30]

<a name="ABS-whats-new"></a>

* **Direct Line Speech Channel**: We are bringing together the Bot Framework and Microsoft's Speech Services to provide a channel that enables streamed speech and text bi-directionally from the client to the bot application.  To sign up, add the 'Direct Line Speech' channel to your Azure Bot Service.

[27]:https://azure.microsoft.com/en-us/services/bot-service/
[28]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0
[29]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0
[30]:https://github.com/Microsoft/BotFramework-DirectLineJS/blob/master/README.md

* **Better isolation for your Bot - Direct Line App Service Extension** : The Direct Line App Service Extension can be deployed as part of a VNET, allowing IT administrators to have more control over conversation traffic and improved latency in conversations due to reduction in the number of hops. Get started with Direct Line App Service Extension here. A VNET lets you create your own private space in Azure and is crucial to your cloud network as it offers isolation, segmentation, and other key benefits. 

## Bot Framework Emulator
<< UPDATE SECTION >>


## Bot Framework Web Chat
<< UPDATE SECTION >>


## Bot Framework CLI Tools


## Bot Framework CLI Tools
The new [BF CLI](https://aka.ms/bfcli) tool replaces legacy standalone tools used to manage Bot Framework bots and related services. We have ported most tools and are in process of porting the rest. BF CLI aggregates the collection of cross-platform tools into one cohesive and consistent interface.

For the 4.6 release, the following commands were ported over:

| BF [New Command]             | Old Tool |
| ---------------------------- | -------- |
| Chatdown                     | Chatdown |
| QnAMaker                     | QnAMaker |
| luis:convert, luis:translate | LuDown   |
| luis:convert                 | LuisGen  |

In the next release we will port the following tools: 

* LUIS (API)
* Dispatch

And finally, alongside the release of new features, we plan to add new commands to BF CLI such as for: 

* Language Generation management
* Adaptive Dialogs management
* Microsoft Teams bots configuration
* Bot Skills configuration management

The old tools will be deprecated in subsequent releases. All new investments, bug fixes, and new features will be implemented in the new consolided BF CLI alone.

See more in https://aka.ms/bfcli.

## Related Services

### Language Understanding 
A machine learning-based service to build natural language experiences. Quickly create enterprise-ready, custom models that continuously improve. Language Understanding Service(LUIS) allows your application to understand what a person wants in their own words.

<< UPDATE SECTION >>

### QnA Maker
QnA Maker is a cloud-based API service that creates a conversational, question-and-answer layer over your data. With QnA Maker, you can build, train and publish a simple question and answer bot based on FAQ URLs, structured documents, product manuals or editorial content in minutes.

<< UPDATE SECTION >>

### Speech Services
[Speech Services][70] convert audio to text, perform speech translation and text-to-speech with the unified Speech services. With the speech services, you can integrate speech into your bot, create custom wake words, and author in multiple languages.

[70]:https://azure.microsoft.com/en-us/services/cognitive-services/speech-services/

### Adaptive Cards
[Adaptive Cards](https://adaptivecards.io) are an open standard for developers to exchange card content in a common and consistent way, 
and are used by Bot Framework developers to create great cross-channel conversatational experiences.

* **Open framework, native performance** - A simple open card format enables an ecosystem of shared tooling, seamless integration between apps, and native cross-platform performance on any device.
* **Speech enabled from day one** - We live in an exciting era where users can talk to their devices. Adaptive Cards embrace this new world and were designed from the ground up to support these new experiences.

## Bot Framework SDK v3

> Note: While we actively maintain the v3 SDK, we are focusing out attention on the v4 of the SDK. Read more on [SDK v3 long-term support](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-resources-bot-framework-faq?view=azure-bot-service-3.0#bot-framework-sdk-version-3-lifetime-support).

The Bot Framework SDK v3 includes SDKs that enable developers to model and build sophisticated conversation using their favorite programing language.

|  | C# | JS |  
|---|:---:|:---:|
|Stable Release |[3.20.1][11] | [3.16.0][12] | 
|Docs | [docs][13] |[docs][13] | 
|Samples |[C#][14] |[Node.js][15] |

[11]:https://www.nuget.org/packages/Microsoft.Bot.Builder/3.20.1
[12]:https://www.npmjs.com/package/botbuilder/v/3.16.0
[13]:https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-3.0
[14]:https://github.com/Microsoft/BotBuilder-V3/tree/master/CSharp/Samples
[15]:https://github.com/Microsoft/BotBuilder-V3/tree/master/Node/examples

## Reporting Security Issues

Security issues and bugs should be reported privately, via email, to the Microsoft Security Response Center (MSRC) at [secure@microsoft.com](mailto:secure@microsoft.com). You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message. Further information, including the [MSRC PGP](https://technet.microsoft.com/en-us/security/dn606155) key, can be found in the [Security TechCenter](https://technet.microsoft.com/en-us/security/default).

Copyright (c) Microsoft Corporation. All rights reserved.
