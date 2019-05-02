
# Microsoft Bot Framework 
The Microsoft Bot Framework is a comprehensive framework for building enterprise-grade conversational AI experiences. It includes a set of open source SDKs and tools that enable developers to build, test, and connect bots that interact naturally with users, wherever they are. With the Microsoft Bot Framework, it is easy can create a bot with the ability to speak, listen, understand, and learn from your users with Azure Cognitive Services. 

![Bot Framework](./docs/media/Bot-Framework-header.jpg)

This repo lists all the different SDK, tools, and services needed to build a great conversational AI experience. Its role is to serve as a landing page and one place to find all the information required to get start building bots. 

- [Azure Bot Service](#Azure-Bot-Service)
- [Bot Framework SDK v4](#Bot-Framework-SDK-v4)
- [Bot Framework SDK v3](#Bot-Framework-SDK-v3)
- [Bot Framework Tools](#Bot-Framework-Tools)
- [Bot Framework Emulator](#Bot-Framework-Emulator)
- [Bot Framework Web Chat](#Bot-Framework-Web-Chat)
- [Language Understanding](#Language-Understanding)
- [QnA Maker](#QnA-Maker)
- [Bot Framework Solutions](#Bot-Framework-Solutions)
- [Speech Services](#Speech-Services) 

## Azure Bot Service
Azure Bot Service enables you to host intelligent, enterprise-grade bots with complete ownership and control of your data. Developers can register and connect their bots to users on Skype, Microsoft Teams, Cortana, Web Chat, and more.

- [Azure][27]  |  [docs][28] | [connect to channels][29] 

[27]:https://azure.microsoft.com/en-us/services/bot-service/
[28]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0
[29]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-manage-channels?view=azure-bot-service-4.0

## Bot Framework SDK v4
The Bot Framework SDK v4 includes SDKs that enable developers to model and build sophisticated conversation using their favorite programing language.


|   | C#  | JS  | Python |  Java | 
|---|:---:|:---:|:------:|:-----:|
|stable release |[4.3.2][1] | [4.3.4][2] | [4.0.0a6 (preview)][3] | |
|Docs | [docs][5] |[docs][5] | | |
|Samples |[.NET Core][6], [WebAPI][10] |[Node.js][7] , [TypeScript][8], [es6][9]  | | | 

[1]:https://github.com/Microsoft/botbuilder-dotnet/#packages
[2]:https://github.com/Microsoft/botbuilder-js#packages
[3]:https://github.com/Microsoft/botbuilder-python#packages
[4]:https://github.com/Microsoft/botbuilder-java#packages
[5]:https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0
[6]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore
[7]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_nodejs
[8]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_typescript
[9]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_es6
[10]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_webapi


### Bot Framework SDK v4 - Futures (preview)
The Bot Framework SDK v4 - Futures includes cool features we are working hard on but are still in preview and are not production ready. 

- [Common Expression Language][40] | [api][41] 
- [Langauge Generation][43] | [docs][44] | samples: [C#][45] , [JS][46]
- [Adaptive Dialog][47] | [docs][48] | [C# samples][49] | 
- [Declarative Dialog][50] 

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

## Bot Framework SDK v3
The Bot Framework SDK v3 includes SDKs that enable developers to model and build sophisticated conversation using their favorite programing language.

|  | C# | JS |  
|---|:---:|:---:|
|stable release |[3.20.1][11] | [3.16.0][12] | 
|Docs | [docs][13] |[docs][13] | 
|Samples |[C#][14] |[Node.js][15] |

[11]:https://www.nuget.org/packages/Microsoft.Bot.Builder/3.20.1
[12]:https://www.npmjs.com/package/botbuilder/v/3.16.0
[13]:https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-3.0
[14]:https://github.com/Microsoft/BotBuilder-V3/tree/master/CSharp/Samples
[15]:https://github.com/Microsoft/BotBuilder-V3/tree/master/Node/examples

> Note: While we actively maintain the v3 SDK, we are focusing out attention on the v4 of the SDK. Read more on [SDK v3 long-term support](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-resources-bot-framework-faq?view=azure-bot-service-3.0#bot-framework-sdk-version-3-lifetime-support).

## Bot Framework Tools
The Bot Framework [tools](https://github.com/Microsoft/botbuilder-tools) are a collection of cross-platform command line tools designed to cover end-to-end bot development workflow.

| Tool | Description |
|------|--------------|
| [Chatdown][16] | Prototype mock conversations in markdown and convert the markdown to transcripts you can load and view in the new V4 Bot Framework Emulator |
| [LUDown][17]| Build LUIS language understanding models using markdown files|
| [LUIS][18]| Create and manage your [LUIS.ai](http://luis.ai) applications |
| [QnAMaker][19] | Create and manage [QnAMaker.ai](http://qnamaker.ai) Knowledge Bases. |
| [Dispatch][20] | Build language models allowing you to dispatch between disparate components (such as QnA, LUIS and custom code)|
| [LUISGen][21] | Auto generate backing C# / Typescript classes for your LUIS intents and entities.|
| [az bot][36] | Manage Azure Bot Service using Azure cli|
| [MSBot][22]| Create and manage connected services in your bot configuration file|

[16]:https://github.com/Microsoft/botbuilder-tools/blob/master/packages/Chatdown
[17]:https://github.com/Microsoft/botbuilder-tools/blob/master/packages/Ludown
[18]:https://github.com/Microsoft/botbuilder-tools/blob/master/packages/LUIS
[19]:https://github.com/Microsoft/botbuilder-tools/blob/master/packages/QnAMaker
[20]:https://github.com/Microsoft/botbuilder-tools/blob/master/packages/Dispatch
[21]:https://github.com/Microsoft/botbuilder-tools/blob/master/packages/LUISGen
[22]:https://github.com/Microsoft/botbuilder-tools/blob/master/packages/MSBot
[36]:https://docs.microsoft.com/en-us/cli/azure/bot?view=azure-cli-latest

## Bot Framework Solutions

The [Bot Framework Solutions repository](https://github.com/Microsoft/AI] is the home for a set of templates, solutions and skills to help build more advanced, assistant-like conversational experiences.

### Bot Framework Virtual Assistant Template

Creation of a high quality conversational experience requires a foundational set of capabilities. To help you succeed with building more complex, assistant-like conversational experiences, we have created an Virtual Assistant Template. This template brings together all of the best practices and supporting components we've identified through building of conversational experiences.

### Bot Framework Skills
Developers can compose conversational experiences by stitching together re-usable conversational capabilities, known as Skills.

Within an Enterprise, this could be creating one parent bot bringing together multiple sub-bots owned by different teams, or more broadly leveraging common capabilities provided by other developers. 

## Bot Framework Emulator
The [Bot Framework Emulator][60] is a  cross-platform desktop application that allows bot developers to test and debug bots built using the Bot Framework SDK. You can use the Bot Framework Emulator to test bots running either locally on your machine or connect to bots running remotely.

- [downlad latest][61] | [docs][62]

[60]:https://github.com/Microsoft/BotFramework-Emulator
[61]:https://github.com/Microsoft/BotFramework-Emulator/releases/latest
[62]:https://docs.microsoft.com/en-us/azure/bot-service/bot-service-debug-emulator?view=azure-bot-service-4.0


## Bot Framework Web Chat
The Bot Framework [Web Chat][23], is highly customizable web-based client chat control for Azure Bot Services, which provides the ability for users to interact with your bot directly in a web page.

- [stable release][24] | [docs][25]  | [samples][26]

[23]:https://github.com/Microsoft/BotFramework-WebChat
[24]:https://www.npmjs.com/package/botframework-webchat
[25]:https://github.com/Microsoft/BotFramework-WebChat/tree/master/doc
[26]:https://github.com/Microsoft/BotFramework-WebChat/tree/master/samples

## Language Understanding 
A machine learning-based service to build natural language experiences. Quickly create enterprise-ready, custom models that continuously improve. [Language Understanding service][30] allows your application to understand what a person wants in their own words.

- [docs][31] | [add language understanding to your bot][32] | use [LUDown][17] and [LUIS][18] command line tools 

[30]:https://www.luis.ai
[31]:https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/Home
[32]:https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-luis?view=azure-bot-service-4.0&branch=pr-en-us-1325&tabs=csharp


## QnA Maker
[QnA Maker][33] is a cloud-based API service that creates a conversational, question and answer layer over your data. with QnA Maker, you can build, train and publish a simple question and answer bot based on FAQ URLs, structured documents, product manuals or editorial content in minutes.

- [docs][34]  | [add qnamaker to your bot][35] | use [LUDdown][17] and [QnAMaker][19] command line tools

[33]:https://www.qnamaker.ai/
[34]:https://aka.ms/qnamaker-docs-home
[35]:https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-qna?view=azure-bot-service-4.0&branch=pr-en-us-1325&tabs=cs

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
