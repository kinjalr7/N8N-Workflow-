# 🤖 Basic AI Chatbot on Telegram (n8n Workflow)

An n8n automation workflow that turns your Telegram bot into an 
AI-powered chatbot using Groq's LLM — with memory support for 
natural, context-aware conversations.

## 🔄 How It Works

1. User sends a message to your Telegram bot
2. The message is passed to an AI Agent powered by Groq (GPT-OSS 120B)
3. Simple Memory keeps track of the conversation per chat session
4. The AI's response is sent back to the user on Telegram

## 🛠️ Tools & Integrations

- **Telegram** — Trigger & send messages
- **Groq** — LLM provider (model: `openai/gpt-oss-120b`)
- **n8n AI Agent** — Orchestrates the conversation
- **Window Buffer Memory** — Maintains chat history per user

## 📦 How to Import

1. Download the `basic_chatting_on_tg.json` file
2. Open your n8n instance
3. Click **"Add Workflow" → "Import from file"**
4. Select the JSON file
5. Add your credentials:
   - Telegram Bot API token
   - Groq API key

## ⚙️ Requirements

- n8n (self-hosted or cloud)
- A Telegram Bot (create via [@BotFather](https://t.me/BotFather))
- A [Groq API key](https://console.groq.com)

## 📸 Workflow Preview

<!-- Add a screenshot of your n8n workflow here -->

## 📄 License

MIT — free to use and modify!
