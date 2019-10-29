# What's new
The Bot Framework SDK v4 is an [Open Source SDK][1a] that enable developers to model and build sophisticated conversation 
using their favorite programming language. Click [here](./README.md) to learn more about Microsoft Bot Framework. 

This page summarizes key new features and improvements in Bot Framework and Azure Bot Service. 

## November 2019 (Ignite)

<a name="V4-whats-new"></a>

### Bot Framework SDK v4
The November release includes a new SDK version - 4.6.

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

#### Bot Framework SDK for Microsoft Teams (GA)
The Bot Framework SDK v4.6 release fully integrates support for building Teams bots allowing users to use them in channel or group chat conversations. By adding a bot to a team or chat, all users of the conversation can take advantage of the bot functionality right in the conversation.  [[Docs][00] | [C# sample][00] | [JS sample][00]]

#### Bot Framework SDK Skills (Preview)
Create a reusable conversational skill to add functionality to a bot. Leverage pre-built skills, such as Calendar, Email, Task, Point of Interest, Automotive, Weather and News skills. Skills include language models, dialogs, QnA, and integration code delivered to customize and extend as required. [[Download]()]

#### Adaptive Dialog (Preview)
Adaptive Dialogs enable developers to build conversations that can be dynamically changed as the conversation progresses. It allows developers to dynamically update conversation flow based on context and events. This is especially handy when dealing with conversation context switches and interruptions in the middle of a conversation. [[Docs][48] | [C# samples][49]] 

#### Language Generation (Preview)
Language Generation enables developers to separate logic used to generate bot's respones including ability to define multiple variations on a phrase, execute simple expressions based on context, refer to conversational memory. [[Docs][44] | [C# samples][45]]

#### Common Expression Language (Preview)
Common Expression Language allows you to evaluate the outcome of a condition-based logic at runtime information. We provide a common language that can be used across the Bot Framework SDK and conversational AI components, such as Adaptive Dialogs and Language Generation. [[Docs][40] | [API][41]]


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

### Bot Framework Composer (Preview)
Bot Framework Composer is an integrated development tool for developers and multi-disciplinary teams to build bots and conversational experiences with the Microsoft Bot Framework. Within this tool, you'll find everything you need to build a sophisticated conversational experience. [[Docs](https://github.com/microsoft/BotFramework-Composer/tree/kaiqb/Ignite2019)]

### Azure Bot Service
- **Direct Line Speech (GA)**: Bot Framework and Microsoft's Speech Services provide a channel that enables streamed speech and text bi-directionally from the client to the bot application using WebSockets on Azure Bot Service. [[Docs](https://docs.microsoft.com/azure/bot-service/directline-speech-bot?view=azure-bot-service-4.0)] 

- **Direct Line App Service Extension (Preview)**: A version of Direct Line App Service Extension that isolates your bot from other traffic on the Bot Service by running Direct Line on your dedicated Azure App Service. This also allows bots to participate in Azure VNET configurations. A VNET lets developers create your own private space in Azure and is crucial to your cloud network as it offers isolation, segmentation, and other key benefits. [[Docs](https://aka.ms/directline-ase)]

[27]:https://azure.microsoft.com/en-us/services/bot-service/
[28]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0
[29]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0
[30]:https://github.com/Microsoft/BotFramework-DirectLineJS/blob/master/README.md

### Bot Framework Web Chat (GA)
Bot Framework Web Chat component is a highly customizable web-based client for the Bot Framework V4 SDK. Updates include: React upgrade to 16.8.6 to support React Hooks and stateful function components, uploaded image attachments can now include a thumbnail, and UI improvements and customizability include bubble nub, timestamp format, and customizable user and bot icons. [[Docs](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-webchat-overview?view=azure-bot-service-4.0)]

### Bot Framework CLI (GA)
BF CLI aggregates the collection of cross-platform tools into one cohesive and consistent interface. For the 4.6 release, we've ported Chatdown, QnAMaker, LuDown, and LuisGen. [[Docs](https://aka.ms/bfcli)]

## Related Services

### Language Understanding 
Language Understanding (LUIS) is an Azure service for building natural language experiences. You can quickly create enterprise-ready, custom models that continuously improve. Updates include: sophisticated hierarchical language models, import and export .lu files for an effective CI/CD process, and basic support for Arabic and Hindi (public preview). [[Docs](https://docs.microsoft.com/en-gb/azure/cognitive-services/luis/whats-new#november-4-2019---ignite)] 

### QnA Maker
QnA Maker is an Azure service that can be used to find the most appropriate answer from your custom knowledge base (KB). Updates include: multi-turn Q&A conversations, new set of languages supported for chit-chat dataset, US Government cloud support, and the ability to set the KB language for your service. [[Docs](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/whats-new)]

### Speech
Speech Services on Azure converts speech <-> text and integrates into your bot. You can use the Direct Line Speech channel in the Azure Bot Service to stream speech, create transcipt files from audio files, and neural-text-to-speech which can make the voice of your bot nearly indistinguishable from voices of the people. [[Docs]]

[70]:https://azure.microsoft.com/en-us/services/cognitive-services/speech-services/

[11]:https://www.nuget.org/packages/Microsoft.Bot.Builder/3.20.1
[12]:https://www.npmjs.com/package/botbuilder/v/3.16.0
[13]:https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-3.0
[14]:https://github.com/Microsoft/BotBuilder-V3/tree/master/CSharp/Samples
[15]:https://github.com/Microsoft/BotBuilder-V3/tree/master/Node/examples


##
# July 2019
The Bot Framework SDK v4 is an [Open Source SDK][1a] that enable developers to model and build sophisticated conversation 
using their favorite programming language. Click [here](./README.md) to learn more about Microsoft Bot Framework. 

This page summarizes key new features and improvements in Bot Framework and Azure Bot Service. 

|   | C#  | JS  | Python |   
|---|:---:|:---:|:------:|
|SDK |[4.5][1] | [4.5][2] | [4.4.0b2 (preview)][3] | 
|Docs | [docs][5] |[docs][5] |  | |
|Samples |[.NET Core][6], [WebAPI][10] |[Node.js][7] , [TypeScript][8], [es6][9]  | [Python][111] | | 

[1a]:https://github.com/microsoft/botframework-sdk/#readme
[1]:https://github.com/Microsoft/botbuilder-dotnet/#packages
[2]:https://github.com/Microsoft/botbuilder-js#packages
[3]:https://github.com/Microsoft/botbuilder-python#packages
[5]:https://docs.microsoft.com/azure/bot-service/?view=azure-bot-service-4.0
[6]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore
[7]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_nodejs
[8]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_typescript
[9]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_es6
[10]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_webapi
[111]:https://github.com/Microsoft/botbuilder-python/tree/master/samples


## Bot Framework Channels
- [Direct Line Speech (public preview)](https://aka.ms/streaming-extensions) | [docs](https://docs.microsoft.com/azure/bot-service/directline-speech-bot?view=azure-bot-service-4.0): Bot Framework and Microsoft's Speech Services provide a channel that enables streamed speech and text bi-directionally from the client to the bot application using WebSockets.  

- [Better isolation for your bot: Direct Line VNet (public preview)](https://portal.azure.com) | [docs](https://aka.ms/directline-ase): A version of Direct Line that allows bots to participate in Azure VNet. A VNet lets you create your own private space in Azure and is crucial to your cloud network as it offers isolation, segmentation, and other key benefits. 

## Bot Framework SDK
- [Adaptive Dialog (SDK v4.6 preview)](https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog#readme) | [docs](https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/docs) | [C# samples](https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/csharp_dotnetcore): 
Adaptive Dialog now allow developers to dynamically update conversation flow based on context and events. This is especially useful when dealing with conversation context switches and interruptions in the middle of a conversation. 
  
- [Bot Framework Python SDK (preview 2)](https://github.com/microsoft/botbuilder-python) | [samples](https://github.com/Microsoft/botbuilder-python/tree/master/samples): The Python SDK now supports OAuth, Prompts, CosmosDB, and includes all major functionality in SDK 4.5. Plus, samples to help you learn about the new features in the SDK.

## Bot Framework Testing
- [Unit Testing](http://aka.ms/bot-test-package) | [docs](https://aka.ms/testing-framework) | [C# sample](https://aka.ms/corebot-test) | [JS sample](https://aka.ms/js-core-test-sample): Addressing customers’ and developers’ ask for better testing tools, the July version of the SDK introduces a new unit testing capability. The Microsoft.Bot.Builder.testing package simplifies the process of unit testing dialogs in your bot. 

- [Channel Testing](https://github.com/Microsoft/BotFramework-Emulator/releases): 
Introduced at Microsoft Build 2019, the Bot Inspector is a new feature in the Bot Framework Emulator which lets you debug and test bots on channels like Microsoft Teams, Slack, Cortana, and more. As you use the bot on specific channels, messages will be mirrored to the Bot Framework Emulator where you can inspect the message data that the bot received. Additionally, a snapshot of the bot memory state for any given turn between the channel and the bot is rendered as well.

## Web Chat
Based on enterprise customers asks, we've added a [web chat sample](https://github.com/microsoft/BotFramework-WebChat/tree/master/samples/19.a.single-sign-on-for-enterprise-apps#single-sign-on-demo-for-enterprise-apps-using-oauth) that shows how to authorize a user to access resources on an enterprise app with a bot. Two types of resources are used to demonstrate the interoperability of OAuth with Microsoft Graph and GitHub API.

## Solutions
- [Virtual Assistant Solution Acclerator](https://github.com/Microsoft/botframework-solutions#readme) : Provides a set of templates, solution accelerators and skills to help build sophisticated conversational experiences. New Android app client for Virtual Assistant that integrates with Direct-Line Speech and Virtual Assistant demonstrating how a device client can interact with your Virtual Assistant and render Adaptive Cards. Updates also include support for Direct-Line Speech and Microsoft Teams.
  
- [Dynamics 365 Virtual Agent for Customer Service (public preview)](https://dynamics.microsoft.com/en-us/ai/virtual-agent-for-customer-service/): With the public preview, you can provide exceptional customer service with intelligent, adaptable virtual agents. Customer service experts can easily create and enhance bots with AI-driven insights.
  
- [Chat for Dynamics 365](https://www.powerobjects.com/powerpacks/powerchat/): Chat for Dynamics 365 offers several capabilities to ensure the support agents and end users can interact effectively and remain highly productive. Live chat and track conversations from visitors on your website within Microsoft Dynamics 365.
  

## 
# May 2019
- [Sessions](#Sessions)
- [What's new](#whats-new)

### Sessions
- [Vision Keynote][1] by Satya Nadella, Microsoft CEO.
- [Microsoft Azure][2] by Scott Guthrie, EVP, CLOUD & ENTERPRISE 
- [The Microsoft Office 365 Platform][3] by Rajesh Jha, EVP, EXPERIENCES + DEVICES
- [How to use Azure Conversational AI to scale your business for the next generation - A deep dive into La Liga’s story][4] by Tulasi Menon, Nayer Wanas, Jesus Serrano Castro
- [Your App, Your Device, Your Assistant - How to build a branded, voice-first Virtual Assistant][5] by Darren Jefford, Travis Wilson, Khuram Shahid. 
- [Microsoft Research APIs – Project Personality Chat in action][6], by Tulasi Menon
- [Designing for Speech][7] by Jessica Engström

[1]:https://mybuild.techcommunity.microsoft.com/sessions/77571?source=sessions#top-anchor
[2]:https://mybuild.techcommunity.microsoft.com/sessions/77572?source=sessions#top-anchor
[3]:https://mybuild.techcommunity.microsoft.com/sessions/77573?source=sessions#top-anchor
[4]:https://mybuild.techcommunity.microsoft.com/sessions/76965?source=sessions#top-anchor
[5]:https://mybuild.techcommunity.microsoft.com/sessions/76969?source=sessions#top-anchor
[6]:https://mybuild.techcommunity.microsoft.com/sessions/77258?source=sessions#top-anchor
[7]:https://mybuild.techcommunity.microsoft.com/sessions/77154?source=sessions#top-anchor
[sdkv4]:https://github.com/microsoft/botframework-sdk#readme
[channelsv4]:https://github.com/microsoft/botframework-sdk#channels-and-adapters

### What's new
- [Bot Framework SDK V4][sdkv4]
    - [Adaptive Dialog][47] | [docs][48] | [C# samples][49] :: Simplify the development of sophisticated dialogs by dynamically updating as the conversation unfolds. This is especially useful when the context of conversation is switched or if there are interruptions in the middle of a conversation.

    - [Language Generation][43] | [docs][44] | [C# samples][45] :: Streamlines the creation of smart and dynamic bot responses by constructing meaningful, variable and grammatically correct responses that a bot can send back to the user.

    - [Common Expression Language][40] | [api][41] :: Both Adaptive dialogs and Language Generation rely on and use a common expression language to power bot conversations.
    
    - [Botkit][b1] :: Major version update with support for Bot Framework Emulator, Azure Bot Service. New model for handling interruptions and composable dialogs. 

- [Bot Framework Channels][channelsv4]
    - Enhanced Speech capabilities, Direct Line Speech Channel – (private preview) Streamlined integration of the Bot Framework and Microsoft's Speech Services in [Azure Bot Service](./README.md#ABS-whats-new) as a new channel, with support for custom wake words and bi-directional speech and text. To sign up, add the Direct Line Speech channel to your Azure Bot Service.

    - SDK Channel adapters available [here][b1] - New platform adapters for Web chat, Slack, Webex, Facebook, Google Hangouts and Twilio SMS. Work with Bot Framework V4 SDK (JS only). Additional new adapters put together by the [BotBuilderCommunity][b2]

- [Bot Framework Skills](https://github.com/Microsoft/AI/tree/master/docs#readme)
    - Skills include language models, dialogs, and cards that can be reusable across bots. Examples include productivity (calendar, email and task productivity- powered by Microsoft Graph), industry (point of interest, and automotive), and custom. 
    
- [Virtual Assistant Template](https://github.com/Microsoft/AI/tree/master/docs#readme)
    - This template incorporates the previous Enterprise Template and brings together all of the best practices and supporting components identified through building advanced assistant-like conversational experiences. It greatly simplifies the creation of a new bot project including: basic conversational intents, Dispatch integration, QnA Maker, Application Insights and an automated deployment.
    
- [Bot Framework Emulator](./README.md#Emulator-whats-new)
    - Bot Inspector, a new ability to debug live conversations in your bots on any channel or adapter - Microsoft Teams, Slack, Cortana, Facebook Messenger, Skype, etc.

- [Language Understanding](./README.md#LUIS-whats-new)
    - Roles, External Entities and Dynamic Entities :: Extract more detailed information from text and build more intelligent solutions with less effort. 
        - Entity Roles are now available for all entity types which enables you to identify subtypes based on context, such as from and to which are both types of location.
        - External entities gives you the ability to use external context for more accurate understanding of user intent.
        - Dynamic lists help append synonyms to list entities, at prediction time enabling dynamic, user-specific information to get matched exactly. 
    - Analytics dashboard :: Provides insight into your models’ quality and potential data problems. Gives guidance to help solve issues and adopt best practices. 

- [QnA Maker](./README.md#QnA-whats-new)
Multi-turn Conversations (Public Preview): Extract information from URL or .pdf, .docx files to create multi-turn conversational flows. You can edit and author your own multi-turn flows and test them using the new contextual ranker. See this [sample](https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/qnamaker-prompting) to create a multi-turn QnA Maker bot.


[b1]:https://github.com/howdyai/botkit#readme
[b2]:https://github.com/BotBuilderCommunity/botbuilder-community-dotnet/tree/develop/libraries
[40]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/common-expression-language
[41]:https://github.com/Microsoft/BotBuilder-Samples/blob/master/experimental/common-expression-language/api-reference.md
[43]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation
[44]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/docs
[45]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/csharp_dotnetcore
[46]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/javascript_nodejs/13.core-bot
[47]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog
[48]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/docs
[49]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/csharp_dotnetcore
[50]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/declarative
