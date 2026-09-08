#  Smart To-Do List Bot

An AI-powered Telegram automation bot built with **n8n**, **OpenAI**, and **Telegram**.  
The bot is designed to automate task-related interactions and provide smart, AI-generated responses directly through Telegram.

This project demonstrates how workflow automation and AI can be combined to create a useful productivity assistant.

---

## 🚀 Features

-  AI-powered task assistance
-  Telegram-based interaction
-  OpenAI Chat Model integration
-  Automated workflow using n8n
-  Scheduled workflow execution
-  Automatic Telegram message delivery
-  Easy-to-customize automation workflow
-  Accessible directly from Telegram

---

##  Technologies Used

| Technology | Purpose |
|------------|---------|
| **n8n** | Workflow automation |
| **Telegram Bot API** | Send and receive messages |
| **OpenAI** | AI-powered response generation |
| **AI Agent** | Processes user/task-related requests |
| **Schedule Trigger** | Runs the workflow automatically |

---

## 🔄 Workflow Architecture

```text
                ┌──────────────────┐
                │  Schedule Trigger│
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │     AI Agent     │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ OpenAI Chat Model│
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Telegram Message │
                └────────┬─────────┘
                         │
                         ▼
                      👤 User
```
<img width="2848" height="1116" alt="Smart To Do List" src="https://github.com/user-attachments/assets/14618074-4b64-4d65-8a3f-7effe98973f2" />
