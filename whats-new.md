# What's new

> See [here](./README.md) to learn more about Microsoft Bot Framework

This page lists the latest updates to Bot Framework. 

## //BUILD 2019
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
