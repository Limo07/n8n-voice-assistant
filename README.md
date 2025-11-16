# Voice-Driven Personal Assistant (n8n + Cloud Run)

This project uses [n8n](https://n8n.io) to automate voice-driven task management:
- Telegram voice messages are transcribed and translated.
- An AI agent (GPT) interprets the intent.
- Actions are routed to Notion (Workout, Idea, Task).

## Workflow
![Workflow Screenshot](<img width="1268" height="632" alt="Screenshot 2025-11-16 134100" src="https://github.com/user-attachments/assets/abb4284c-82a5-45db-bb68-c0ece562acbc" />
)


## APIs
- Telegram Bot API Key TELEGRAM_API_KEY=<your-telegram-bot-token>

- OpenAI API Key OPENAI_API_KEY=<your-openai-api-key>

- Notion Integration Token NOTION_API_KEY=<your-notion-integration-token>

## Deployment
Deployed on Google Cloud Run

