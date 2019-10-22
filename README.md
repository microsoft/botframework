
# Microsoft Bot Framework 

The Microsoft Bot Framework is a comprehensive platform for building enterprise-grade conversational AI experiences. It includes a set of open source SDKs, tools, and services which enable developers to **build**, **test**, and **connect** bots that interact naturally with users, wherever they are. With the Microsoft Bot Framework, it is easy to create a bot with the ability to speak, listen, understand, and learn from your users with Azure Cognitive Services. 

![Bot Framework](./docs/media/Bot-Framework-header.jpg)

This repo lists the SDK, tools, and services needed to build a great conversational AI experience. Its role is to serve as a landing page and one place to find all the information required to get started. 

# What's new (Ignite 2019)

## Bot Framework Composer (Preview)
[Bot Framework Composer](https://github.com/microsoft/BotFramework-Composer/tree/kaiqb/Ignite2019) | [docs]() :: is an integrated development tool for developers and multi-disciplinary team of professional conversation designers for building bots and other types of conversational software with the Microsoft Bot Framework technology stack. Within this web-based tool, you'll find everything you need to build a modern, state-of-the-art conversational experience.


## Bot Framework SDK v4
The Bot Framework SDK v4 is an [open source SDK][1a] that enable developers to model and build sophisticated conversation using their favorite programming language.

|   | C#  | JS  | Python |  Java | 
|---|:---:|:---:|:------:|:-----:|
|Release |[4.6 GA][1] | [4.6 GA][2] | [Beta 4][3] | [Preview 3][3a]|
|Docs | [docs][5] |[docs][5] |  | |
|Samples |[.NET Core][6], [WebAPI][10] |[Node.js][7], [TypeScript][8], [es6][9]  | | | 

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

<a name="V4-whats-new"></a>

### Microsoft Teams support (GA)
Microsoft Teams support | [docs][00] | [C# sample][00] | [JS sample][00] :: Build and connect intelligent bots to interact with Microsoft Teams users naturally through chat. The Bot Framework SDK v4.6 release adds native support for building Teams bots allowing users to bring bots into their channel or group chat conversations. By adding a bot to a team or chat, all users of the conversation can take advantage of the bot functionality right in the conversation.

### Dynamics 365 Virtual Agent for Customer Service (??)
[Virtual Agent for Customer Service](https://docs.microsoft.com/en-us/dynamics365/ai/customer-service-virtual-agent/overview), built on the Microsoft Bot Framework, makes it easy to create bots that address common support issues. It removes the complexity of exposing teams to the nuances of conversational AI and the need to write complex code. It provides exceptional customer service with intelligent, adaptable virtual agents.

### Adaptive Dialog (Preview)
- [Adaptive Dialog][47] | [docs][48] | [C# samples][49] :: Adaptive Dialogs enable developers to build conversations that can be dynamically changed as the conversation progresses.
    - Adaptive dialog now includes trigger to action pairs, recognizer, and generator. This makes every adaptive dialog self-contained and easy to compose.
    - Events have been cleaned up to correspond to activity level events and dialog level events.
    - Regex recognizer now supports 10+ prebuilt entity types
    - Triggers, actions have been refined based on feedback
    - Stability improvements and bug fixes.
    
### Language Generation (Preview)
- [Language Generation][43] | [docs][44] | [C# samples][45] :: Language Generation enable developers to separate logic used to generate bot's respones including ability to define multiple variations on a phrase, execute simple expressions based on context, refer to conversational memory.
    - Structured template support - with this you can now use Langauge Generation for multi-modal responses including spoken response, displayed response as well as UI cards etc.
    - Ability to import and refer to .lg files. This helps streamline organization of templates, its composability and re-usability.
    - Stability improvements and bug fixes.

### Common Expression Language (Preview)
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

## Azure Bot Service
- [Direct Line Speech (GA)](https://aka.ms/streaming-extensions) | [docs](https://docs.microsoft.com/azure/bot-service/directline-speech-bot?view=azure-bot-service-4.0): Bot Framework and Microsoft's Speech Services provide a channel that enables streamed speech and text bi-directionally from the client to the bot application using WebSockets.  

- [A Private Direct Line: Direct Line App Serive Extension (Preview)](https://portal.azure.com) | [docs](https://aka.ms/directline-ase): A version of Direct Line that isolates your bot from other traffic on the Bot Service by running Direct Line on its Azure App Service. This both improves latency, and allows bots to participate in Azure VNET configuraitons. A VNET lets developers create your own private space in Azure and is crucial to your cloud network as it offers isolation, segmentation, and other key benefits.

[27]:https://azure.microsoft.com/en-us/services/bot-service/
[28]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0
[29]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0
[30]:https://github.com/Microsoft/BotFramework-DirectLineJS/blob/master/README.md

## Bot Framework Web Chat (GA)
- React was [upgraded](https://github.com/microsoft/BotFramework-WebChat/pull/2322) to 16.8.6 to support [React Hooks](https://reactjs.org/docs/hooks-intro.html) and stateful function components.
- Uploaded image attachments can now include a [thumbnail](https://github.com/microsoft/BotFramework-WebChat/pull/2433). Additional UI improvements and customizability include:
  - [Bubble nub](https://github.com/Microsoft/BotFramework-WebChat/pull/2137) styling options were added.
  - [Timestamp format](https://github.com/microsoft/BotFramework-WebChat/pull/2295) were modified to allow absolute and relative time.
  - [Stylable avatar background colors](https://github.com/microsoft/BotFramework-WebChat/pull/2384) were added.
- Following demos were released:
  - [Single Sign-On for Microsoft Teams using OAuth](https://microsoft.github.io/BotFramework-WebChat/19.c.single-sign-on-for-teams-apps/) shows user authorization through a bot.
  - [Select Voice for Speech Synthesis](https://github.com/microsoft/BotFramework-WebChat/blob/master/samples/06.g.select-voice/) shows how to select [DNN-based voices](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/language-support#neural-voices).
- The accessibility experience was improved for customers utilizing Assistive Technology across [different browsers](https://github.com/microsoft/BotFramework-WebChat/pull/2278).

- To see the rest of Web Chat's updates for 4.6, take a look at the [changelog](https://github.com/microsoft/BotFramework-WebChat/blob/master/CHANGELOG.md).

## Bot Framework CLI Tools (GA)
The new [BF CLI](https://aka.ms/bfcli) tool replaces legacy standalone tools used to manage Bot Framework bots and related services. We have ported most tools and are in process of porting the rest. BF CLI aggregates the collection of cross-platform tools into one cohesive and consistent interface.

For the 4.6 release, the following commands were ported over:

| BF [New Command]             | Old Tool |
| ---------------------------- | -------- |
| Chatdown                     | Chatdown |
| QnAMaker                     | QnAMaker |
| luis:convert, luis:translate | LuDown   |
| luis:convert                 | LuisGen  |


The old tools will be deprecated in subsequent releases. All new investments, bug fixes, and new features will be implemented in the new consolided BF CLI alone. Click [here](https://aka.ms/bfcli) for more information.


## Bot Framework Solutions 
Virtual Assistan Solution Accelerator for Enterprise (??)


## Related Services

### Language Understanding 
A machine learning-based service to build natural language experiences. Quickly create enterprise-ready, custom models that continuously improve. Language Understanding Service(LUIS) allows your application to understand what a person wants in their own words.

**Advanced language understanding capabilities** - build sophisticated language models with less effort

  * Define machine learning features at the model level and enable models to be used as signals to other model, like using entities as features to intents and to other entities.
  * Extract information from text in the format of deep hierarchical structure, making conversation applications more powerful.

**Improved developer productivity** -  General availability of prediction endpoint V3. Ability to import and export .lu files paves the way for an effective CI/CD process. 

**Enhanced user experience** - labeling experience enables building and debugging complex models

**Language expansion** - basic support for Arabic and Hindi (public preview)

Check the [documentation](https://docs.microsoft.com/en-gb/azure/cognitive-services/luis/whats-new#november-4-2019---ignite) to learn more. 

### QnA Maker
QnA Maker is a cloud-based API service that creates a conversational, question-and-answer layer over your data. With QnA Maker, you can build, train and publish a simple question and answer bot based on FAQ URLs, structured documents, product manuals or editorial content in minutes.

[Multi-turn Q&A Conversations:](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/how-to/multiturn-conversation) Multi-turn feature is available to build guided conversational flows. With the latest release, multi-turn moves out of preview, and you can build multi-turn Q&A conversations with no code.

[Chit-Chat:](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/how-to/chit-chat-knowledge-base) QnA Maker now provides support to add personality to your bots in 8 new languages in addition to English. The new set of languages supported for chit-chat dataset are Chinese, French, German, Japanese, Italian, Korean, Portugese, Spanish. The new languages have chit-chat available for only 1 personality today - the professional personality. 

[US Government Cloud Support:](https://docs.microsoft.com/en-us/azure/azure-government/documentation-government-services-aiandcognitiveservices#language) QnA Maker is now available (GA) for US Government cloud. 

Enhanced KB Management Experience: The new KB language settings option lets you explicitly set the KB language for your service. Excel file format support has been added to the import and export actions for easy editing and replacment of the content. [Batch Testing](https://aka.ms/qna_batchtest) allows you to batch test your KB or KBs to analyse the quality and training of your KB data.

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
