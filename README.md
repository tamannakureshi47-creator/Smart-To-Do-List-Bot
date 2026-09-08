#  Smart To Do List Bot

An AI-powered **Smart To Do List Bot** built using **n8n, Telegram, OpenAI, and Google Sheets**.

This automation allows users to manage their daily tasks directly through Telegram. Users can create, view, complete, and delete tasks using simple natural-language messages.

---

##  Features

-  Manage tasks directly through Telegram
-  AI-powered task understanding using OpenAI
-  Create new tasks
-  Get/View existing tasks
-  Mark tasks as completed
-  Delete tasks
-  AI Agent understands natural-language commands
-  Google Sheets used for task storage
-  Fully automated workflow using n8n
-  Real-time task management

---

##  Technologies Used

| Technology | Purpose |
|-----------|---------|
| **n8n** | Workflow automation |
| **Telegram Bot API** | User interaction |
| **OpenAI** | AI-powered task understanding |
| **Google Sheets** | Task database/storage |
| **AI Agent** | Processes user requests |

---

##  Workflow

```text
User
  │
  ▼
Telegram Trigger
  │
  ▼
AI Agent
  │
  ├── OpenAI Chat Model
  │
  ├── Create Task → Google Sheets
  │
  ├── Get Task → Google Sheets
  │
  ├── Complete Task → Google Sheets
  │
  └── Delete Task → Google Sheets
  │
  ▼
Send Telegram Response
```
<img width="2848" height="1116" alt="Smart To Do List" src="https://github.com/user-attachments/assets/14618074-4b64-4d65-8a3f-7effe98973f2" />
