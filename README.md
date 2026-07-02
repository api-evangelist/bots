# Bots (bots)
An index and topic collection covering chatbots, conversational agents, and bot frameworks across messaging, voice, and customer experience channels. Bots are scripted or model-augmented conversational interfaces deployed inside Slack, Discord, Microsoft Teams, Telegram, WhatsApp, web chat widgets, and voice channels. This collection brings together developer-oriented bot frameworks like Microsoft Bot Framework, Botpress, Rasa, Botkit, Hubot, and Errbot alongside SaaS conversational platforms like Intercom, Drift, ManyChat, Tidio, Landbot, Dialogflow, IBM watsonx Assistant, and Amazon Lex. Bots in this collection are distinct from autonomous AI agents — they are conversational, channel-bound interfaces driven by intents, dialog flows, and integration triggers.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - Chatbots, Conversational AI, Bot Framework, Slack Bot, Discord Bot, Messaging, Voice Bot, Customer Support Bot

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Bot Definition Schema](https://raw.githubusercontent.com/api-evangelist/bots/refs/heads/main/json-schema/bots-bot-definition-schema.json)
- [JSONSchema - Conversation Turn Schema](https://raw.githubusercontent.com/api-evangelist/bots/refs/heads/main/json-schema/bots-conversation-turn-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/bots/refs/heads/main/json-ld/bots-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/bots/refs/heads/main/vocabulary/bots-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Channel Integration | Bot platforms expose adapters that connect a single bot implementation to multiple messaging channels — Slack, Teams, Discord, Telegram, WhatsApp, web chat, and voice — without rewriting conversation logic per surface. |
| Intent Recognition and NLU | Conversational AI platforms like Dialogflow, Amazon Lex, IBM watsonx Assistant, and Rasa classify utterances into intents and extract entities. |
| Dialog Flow Management | Frameworks model multi-turn conversations as state machines, decision trees, or graphs, tracking context across turns. |
| Bot SDKs and Builder Tooling | SDKs like Microsoft Bot Framework, Botkit, Botpress, and Hubot abstract event handling, message sending, and deployment. |
| Low-Code Bot Builders | Visual flow editors from ManyChat, Chatfuel, Tidio, and Landbot let non-developers assemble bots via drag-and-drop nodes. |
| Human Handoff and Hybrid Conversations | Customer support bots escalate to live agents when intents fall outside the bot's confidence threshold or scope. |
| Channel-Native Rich Messaging | Bots emit Slack blocks, Discord embeds, Teams adaptive cards, and WhatsApp interactive lists through unified or channel-targeted payloads. |
| Voice and Telephony Bots | Voice-bot platforms like Amazon Lex, Amazon Connect, Voiceflow, and Retell AI wire conversational logic into PSTN telephony and IVRs. |

## Use Cases

| Name | Description |
|------|-------------|
| Customer Support Automation | Bots in Intercom Fin, Drift, Freshchat, and Zendesk deflect common questions, qualify tickets, and hand off with full conversation history. |
| Lead Qualification and Marketing | Sales chatbots from Drift, ManyChat, and Landbot greet visitors, qualify leads, and route prospects into CRM pipelines. |
| Internal Productivity and ChatOps | Slack and Teams bots automate deploys, on-call alerts, polls, and time tracking inside the team's primary chat channel. |
| Conversational Commerce | WhatsApp, Messenger, and Instagram bots powered by Sinch, MessageBird, WATI, and Twilio handle catalog browsing and order placement. |
| HR and Recruiting Conversations | Recruiting bots like Paradox Olivia screen candidates, schedule interviews, and handle FAQ across SMS, WhatsApp, and career-site chat. |
| IVR Modernization and Voice Bots | Voice-bot frameworks from Amazon Lex, Dialogflow CX, and Voiceflow replace touch-tone IVRs with natural-language voice flows. |
| Community and Moderation Bots | Discord and Slack community bots handle onboarding, role assignment, moderation, polls, and gamification. |
| Knowledge Base Q and A | Bots integrate with knowledge bases and retrieval systems to answer policy, product, and how-to questions in chat. |

## Integrations

| Name | Description |
|------|-------------|
| Slack | Workplace messaging platform with a rich bot and app ecosystem; the de facto channel for ChatOps and internal automation bots. |
| Microsoft Bot Framework | Microsoft's SDK and channel connector service for building bots that deploy across Teams, Web Chat, Direct Line, SMS, and other channels. |
| Google Dialogflow | Google Cloud's conversational AI platform with intent classification, entity extraction, and Dialogflow CX visual flow builder. |
| Amazon Lex | AWS conversational AI service for building text and voice bots, with native integration to Amazon Connect. |
| Botpress | Open-source conversational AI platform with a visual flow builder, NLU engine, and channel integrations for self-hosted bots. |
| Intercom | Customer messaging platform with the Fin AI agent and a long-standing chatbot product for support deflection. |
| Twilio | Cloud communications platform exposing SMS, WhatsApp, voice, and chat channels that bot frameworks plug into. |
| ManyChat | Low-code chatbot builder focused on Messenger, Instagram, WhatsApp, and SMS for marketing and conversational commerce. |

## Artifacts

Machine-readable definitions for bot configuration, conversations, and intents.

### JSON Schema

- [Bot Definition Schema](json-schema/bots-bot-definition-schema.json)
- [Conversation Turn Schema](json-schema/bots-conversation-turn-schema.json)

### JSON Structure

- [Bot Definition Structure](json-structure/bots-bot-definition-structure.json)
- [Conversation Turn Structure](json-structure/bots-conversation-turn-structure.json)

### JSON-LD

- [Bots Context](json-ld/bots-context.jsonld)

## Vocabulary

- [Bots Vocabulary](vocabulary/bots-vocabulary.yaml) — Unified taxonomy mapping bot resources, conversation actions, dialog workflows, and personas across messaging channels, conversational AI platforms, and bot frameworks

## Network

This index references the following bot, chatbot, and conversational AI repositories:

- [Amazon Connect](https://github.com/api-evangelist/amazon-connect)
- [Amazon Lex](https://github.com/api-evangelist/amazon-lex)
- [Botpress](https://github.com/api-evangelist/botpress)
- [Character.AI](https://github.com/api-evangelist/character-ai)
- [Cisco Webex](https://github.com/api-evangelist/webex)
- [Crisp](https://github.com/api-evangelist/crisp)
- [Discord](https://github.com/api-evangelist/discord)
- [Drift](https://github.com/api-evangelist/drift)
- [Freshchat](https://github.com/api-evangelist/freshchat)
- [Google Assistant](https://github.com/api-evangelist/google-assistant)
- [Google Chat](https://github.com/api-evangelist/google-chat-integrations-for-workspace)
- [Google Cloud Dialogflow CX](https://github.com/api-evangelist/google-cloud-dialogflow-cx)
- [Google Dialogflow](https://github.com/api-evangelist/google-dialogflow)
- [HipChat](https://github.com/api-evangelist/hipchat)
- [IBM Watson](https://github.com/api-evangelist/ibm-watson)
- [Intercom](https://github.com/api-evangelist/intercom)
- [Inworld](https://github.com/api-evangelist/inworld)
- [LINE](https://github.com/api-evangelist/line)
- [LivePerson](https://github.com/api-evangelist/liveperson)
- [ManyChat](https://github.com/api-evangelist/manychat)
- [Mattermost](https://github.com/api-evangelist/mattermost)
- [MessageBird](https://github.com/api-evangelist/messagebird)
- [Microsoft Bot Framework](https://github.com/api-evangelist/microsoft-bot-framework)
- [Microsoft Copilot](https://github.com/api-evangelist/microsoft-copilot)
- [Microsoft Power Virtual Agents](https://github.com/api-evangelist/microsoft-power-virtual-agents)
- [Microsoft Teams](https://github.com/api-evangelist/microsoft-teams)
- [Olark](https://github.com/api-evangelist/olark)
- [Paradox](https://github.com/api-evangelist/paradox)
- [Quora](https://github.com/api-evangelist/quora)
- [Retell AI](https://github.com/api-evangelist/retell-ai)
- [RingCentral](https://github.com/api-evangelist/ringcentral)
- [Salesforce Einstein](https://github.com/api-evangelist/salesforce-einstein)
- [Salesforce Service Cloud](https://github.com/api-evangelist/salesforce-service-cloud)
- [Sendbird](https://github.com/api-evangelist/sendbird)
- [Sinch](https://github.com/api-evangelist/sinch)
- [Slack](https://github.com/api-evangelist/slack)
- [Symphony](https://github.com/api-evangelist/symphony)
- [Telegram](https://github.com/api-evangelist/telegram)
- [Twilio](https://github.com/api-evangelist/twilio)
- [Voiceflow](https://github.com/api-evangelist/voiceflow)
- [Vonage](https://github.com/api-evangelist/vonage)
- [WATI](https://github.com/api-evangelist/wati)
- [WhatsApp](https://github.com/api-evangelist/whatsapp)
- [Zendesk](https://github.com/api-evangelist/zendesk)
- [Zulip](https://github.com/api-evangelist/zulip)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
