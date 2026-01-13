# Awesome Bot Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of frameworks, libraries, tools, and resources for building bots across all platforms

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Contents

- [Platforms](#platforms)
  - [WhatsApp](#whatsapp)
  - [Telegram](#telegram)
  - [Discord](#discord)
  - [Slack](#slack)
  - [Messenger](#messenger)
- [AI & NLP](#ai--nlp)
- [Development Tools](#development-tools)
- [Deployment](#deployment)
- [Testing](#testing)
- [Learning Resources](#learning-resources)
- [Communities](#communities)

## Platforms

### WhatsApp

#### Official APIs
- [WhatsApp Business API](https://developers.facebook.com/docs/whatsapp) - Official WhatsApp Cloud API
- [WhatsApp Business Platform](https://business.whatsapp.com/products/business-platform) - Enterprise messaging platform

#### Libraries & Frameworks
- [whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js) - Node.js client connecting through WhatsApp Web
- [Baileys](https://github.com/WhiskeySockets/Baileys) - Lightweight WhatsApp Web API in Node.js
- [PyWhatKit](https://github.com/Ankit404butfound/PyWhatKit) - Python library for WhatsApp automation
- [go-whatsapp](https://github.com/Rhymen/go-whatsapp) - WhatsApp Web API implementation in Go

#### Starter Templates
- [WorqNow Architecture](https://github.com/ibrahimpelumi6142/WorqNow) - FastAPI + MongoDB production template
- [WhatsApp Cloud API Starter](https://github.com/ibrahimpelumi6142/WhatsApp-Cloud-API-Starter) - Quick start template

### Telegram

#### Official
- [Telegram Bot API](https://core.telegram.org/bots/api) - Official HTTP-based API
- [MTProto API](https://core.telegram.org/api) - Protocol for building custom clients

#### Libraries
**Python:**
- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) - Pure Python async wrapper
- [aiogram](https://github.com/aiogram/aiogram) - Modern async framework
- [Pyrogram](https://github.com/pyrogram/pyrogram) - MTProto API framework

**JavaScript/Node.js:**
- [Telegraf](https://github.com/telegraf/telegraf) - Modern Telegram bot framework
- [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) - Node.js wrapper
- [GrammY](https://github.com/grammyjs/grammY) - TypeScript-first bot framework

**Go:**
- [telebot](https://github.com/tucnak/telebot) - Clean Go framework

### Discord

#### Official
- [Discord Developer Portal](https://discord.com/developers/docs/intro) - Official documentation

#### Libraries
**Python:**
- [discord.py](https://github.com/Rapptz/discord.py) - Modern async API wrapper
- [nextcord](https://github.com/nextcord/nextcord) - discord.py fork with active development
- [py-cord](https://github.com/Pycord-Development/pycord) - Modern fork with slash commands

**JavaScript:**
- [discord.js](https://github.com/discordjs/discord.js) - Powerful Node.js library
- [Eris](https://github.com/abalabahaha/eris) - Lightweight library

### Slack

#### Official
- [Slack API](https://api.slack.com/) - Official API documentation
- [Bolt Framework](https://slack.dev/bolt-js/) - Official JavaScript framework
- [Bolt for Python](https://slack.dev/bolt-python/) - Official Python framework

#### Libraries
- [slackclient](https://github.com/slackapi/python-slack-sdk) - Official Python SDK
- [slack-ruby-client](https://github.com/slack-ruby/slack-ruby-client) - Ruby client

### Messenger

#### Official
- [Messenger Platform](https://developers.facebook.com/docs/messenger-platform) - Facebook Messenger API

#### Libraries
- [bottender](https://github.com/Yoctol/bottender) - Multi-platform framework (Messenger, LINE, Telegram)
- [facebook-chat-api](https://github.com/Schmavery/facebook-chat-api) - Unofficial Node.js API

## AI & NLP

### LLM APIs
- [OpenAI API](https://platform.openai.com/) - GPT-4, GPT-3.5 Turbo
- [Google Gemini](https://ai.google.dev/) - Google's multimodal AI
- [Anthropic Claude](https://www.anthropic.com/) - Constitutional AI assistant
- [Together AI](https://www.together.ai/) - Open source LLMs
- [DeepInfra](https://deepinfra.com/) - Serverless inference

### Free LLM Resources
- [free-llm-api-resources](https://github.com/kofany/free-llm-api-resources) - Curated list of free LLM APIs
- [Hugging Face](https://huggingface.co/) - Open source models and APIs

### NLP Libraries
- [spaCy](https://github.com/explosion/spaCy) - Industrial-strength NLP
- [NLTK](https://github.com/nltk/nltk) - Natural Language Toolkit
- [Rasa](https://github.com/RasaHQ/rasa) - Open source conversational AI

## Development Tools

### Frameworks
- [Botpress](https://github.com/botpress/botpress) - Open source conversational platform
- [Microsoft Bot Framework](https://github.com/microsoft/botframework-sdk) - Enterprise bot building
- [ChatterBot](https://github.com/gunthercox/ChatterBot) - Machine learning chatbot

### Utilities
- [python-dotenv](https://github.com/theskumar/python-dotenv) - Environment variable management
- [aiohttp](https://github.com/aio-libs/aiohttp) - Async HTTP client/server
- [FastAPI](https://github.com/tiangolo/fastapi) - Modern API framework
- [Express.js](https://expressjs.com/) - Node.js web framework

### Database
- [MongoDB](https://www.mongodb.com/) - NoSQL database
- [Redis](https://redis.io/) - In-memory data store for caching
- [PostgreSQL](https://www.postgresql.org/) - Relational database
- [SQLite](https://www.sqlite.org/) - Lightweight embedded database

## Deployment

### Platforms
- [Railway](https://railway.app/) - Simple deployment platform
- [Heroku](https://www.heroku.com/) - Cloud application platform
- [Vercel](https://vercel.com/) - Frontend and serverless deployment
- [Render](https://render.com/) - Unified cloud platform
- [Fly.io](https://fly.io/) - Global app distribution
- [DigitalOcean](https://www.digitalocean.com/) - Cloud infrastructure
- [AWS Lambda](https://aws.amazon.com/lambda/) - Serverless functions
- [Google Cloud Functions](https://cloud.google.com/functions) - Event-driven serverless

### Containerization
- [Docker](https://www.docker.com/) - Container platform
- [Docker Compose](https://docs.docker.com/compose/) - Multi-container applications

## Testing

### Testing Frameworks
- [pytest](https://pytest.org/) - Python testing framework
- [unittest](https://docs.python.org/3/library/unittest.html) - Built-in Python testing
- [Jest](https://jestjs.io/) - JavaScript testing
- [Mocha](https://mochajs.org/) - Node.js testing framework

### Mocking & Testing
- [pytest-mock](https://github.com/pytest-dev/pytest-mock) - Pytest mocking plugin
- [responses](https://github.com/getsentry/responses) - Mock HTTP requests
- [nock](https://github.com/nock/nock) - HTTP mocking for Node.js

## Learning Resources

### Tutorials
- [Building Your First Telegram Bot](https://core.telegram.org/bots/tutorial) - Official Telegram tutorial
- [Discord.py Guide](https://discordpy.readthedocs.io/en/stable/) - Comprehensive discord.py docs
- [WhatsApp Cloud API Quickstart](https://developers.facebook.com/docs/whatsapp/cloud-api/get-started) - Official guide

### Courses
- [Chatbot Development with Python](https://www.udemy.com/topic/chatbot/) - Udemy courses
- [Building Conversational Experiences](https://www.coursera.org/learn/conversational-experiences-dialogflow) - Coursera

### Books
- "Building Chatbots with Python" by Sumit Raj
- "Designing Bots" by Amir Shevat

### Blogs & Articles
- [Chatbots Magazine](https://chatbotsmagazine.com/)
- [Bot Academy](https://botacademy.com/blog/)

## Communities

### Discord Servers
- [Discord API](https://discord.gg/discord-api) - Official Discord dev community
- [discord.py](https://discord.gg/dpy) - discord.py support server

### Reddit
- [r/TelegramBots](https://www.reddit.com/r/TelegramBots/)
- [r/Discord_Bots](https://www.reddit.com/r/Discord_Bots/)
- [r/botbuilders](https://www.reddit.com/r/botbuilders/)

### GitHub Discussions
- [BotDev Community Discussions](https://github.com/orgs/botdev-community/discussions)

## Contributing

Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md) before submitting.

### How to Contribute
1. Fork this repository
2. Add your resource in the appropriate category
3. Follow the format: `[Name](link) - Description`
4. Submit a pull request

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
