# What's new

> See [here](./README.md) to learn more about Microsoft Bot Framework

This page lists what's new with Bot Framework. 

## //BUILD 2019
- [Sessions](#Sessions)
- [What's new](#whats-new)

### Sessions
- [**Vision Keynote**][1] by Satya Nadella
- [**Microsoft Azure**][2] - Technical keynote by Scott Guthrie
- [**The Microsoft Office 365 Platform**][3] - Technical keynote by Rajesh Jha
- [**Session: BRK3003**][4] How to use Azure Conversational AI to scale your business for the next generation - A deep dive into La Liga’s story; Tulasi Menon, Nayer Wanas, Jesus Serrano Castro
- [**Sesssion: BRK4001**][5] Your App, Your Device, Your Assistant - How to build a branded, voice-first Virtual Assistant; Darren Jefford, Travis Wilson, Khuram Shahid. 

[1]:https://mybuild.techcommunity.microsoft.com/sessions/77571?source=sessions#top-anchor
[2]:https://mybuild.techcommunity.microsoft.com/sessions/77310?source=sessions#top-anchor
[3]:https://mybuild.techcommunity.microsoft.com/sessions/77573?source=sessions#top-anchor
[4]:https://mybuild.techcommunity.microsoft.com/sessions/76965?source=sessions#top-anchor
[5]:https://mybuild.techcommunity.microsoft.com/sessions/76969?source=sessions#top-anchor

### Whats new
- [Azure Bot Service](./README.md#ABS-whats-new)
    - Direct Line Speech Channel – (new) Almost every enterprise bot customer is looking at least one or more scenario involving voice enabled assistants, whether it be customer care or virtual assistant, often via IoT.  Quality of experience, minimal latency, and custom wake words are all critical to a great experience. We are bringing together the Bot Framework and Microsoft's Speech Services to provide a channel that enables bi-directional streamed speech and text from the client to the bot application. This brings together our development communities for Virtual Assistants and Mixed Reality around our common developer offering. To sign up, add the 'Direct Line Speech' channel to your Azure Bot Service registration.

- [Bot Framework SDK](./README.md#V4-whats-new)
    - [Adaptive Dialog][47] | [docs][48] | [C# samples][49] :: Adaptive Dialogs enable developers to create conversation flows that can be dynamically changed as the conversation progresses.  Traditionally developers have mapped out the entire flow of a conversation up front, which limits the flexibility of the conversation.  Adaptive dialogs allow them to be more flexible, to respond to changes in context and insert new steps or entire sub-dialogs into the conversation as it progresses. Additionally as with other SDK V4 concepts, we have defined adaptive dialogs such that they can be defined via [metadata files][50] that are interpreted at runtime; which allows us to have tooling on top of this and integrate with services. 

    - [Language Generation][43] | [docs][44] | [C# samples][45] :: Learning from our customers experiences and bringing together capabilities first implemented by Cortana and Cognition teams, we are introducing Language Generation; which allows the developer to extract the embedded strings from their code and resource files and manage them through a Language Generation runtime and file format.  Language Generation enable customers to define multiple variations on a phrase, execute simple expressions based on context, refer to conversational memory, and over time will enable us to bring additional capabilities all leading to a more natural conversational experience.

    - [Common Expression Language][40] | [api][41] :: Both Adaptive dialogs and Language Generation rely on and use a common expression language to power bot conversations.

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

- [Bot Framework Solutions](./README.md#Solutions-whats-new)
    - The Bot Framework solutions includes the following new features in preview: [Skills](https://github.com/Microsoft/AI/blob/master/docs/overview/skills.md)   

- [Bot Framework Emulator](./README.md#Emulator-whats-new)
    - The Bot Framework Emulator has released a Beta of the new Bot Inspector feature: a way to debug and test your Bot Framework SDK v4 bots on channels like Microsoft Teams, Slack, Cortana, Facebook Messenger, Skype, etc.

- [Language Understanding](./README.md#LUIS-whats-new)
    - **Roles, External Entities and Dynamic Entities** :: LUIS has added several features that let developers extract more detailed information from text, so users can now build more intelligent solutions with less effort. LUIS also extended roles to all entity types, which allows the same entities to be classified with different subtypes based on context. Developers now have more granular control of what they can do with LUIS, including being able to identify and update models at runtime through dynamic lists and external entities. Dynamic lists are used to append to list entities at prediction time, permitting user-specific information to get matched exactly. Separate supplementary entity extractors are run with external entities, and that information can be appended to LUIS as strong signals for other models.

    - **Analytics dashboard** :: LUIS is releasing a more detailed, visually-rich comprehensive analytics dashboard. Its user-friendly design highlights common issues most users face when designing applications, by providing simple explanations on how to resolve them to help users gain more insight into their models’ quality, potential data problems, and guidance to adopt best practices.

- [QnA Maker](./README.md#QnA-whats-new)
    - Extraction pipeline: Now you can extract hierarchical information from URLs, files and sharepoint
    - Intelligence: Contextual ranking models, active learning suggestions
    - Conversation: Multi-turn conversations in QnA Maker.

