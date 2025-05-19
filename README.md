![carbon (2)](https://github.com/user-attachments/assets/127c6eb8-3696-4ee3-a025-e0112674d5f5)

# 🤖 AI Agent with LangGraph, Gemini & Web Search

An intelligent ReAct-style AI Agent powered by **Gemini 2.0 Flash**, capable of handling real-world queries, performing live web searches, and maintaining conversational context using LangGraph memory.

---

## ✨ Features

- 🔮 **Google Gemini Integration** via LangChain
- 🔍 Live web search support with **Tavily**
- 🧠 Persistent memory across threads using **LangGraph Checkpointer**
- 💬 Agent-powered reasoning and response
- ⚡ Streaming answers in real time

---

## 📁 Project Structure

```bash
.
├── agent/                   # Agent logic and tool integration
├── examples/                # Example usage flows
├── memory/                  # Memory configuration and thread management
├── .env                     # Environment variables (API keys, etc.)
└── main.py                  # Entry point to run and test the agent
```
## 🛠️ Setup Instructions
Clone the repository

Install dependencies 

Add your API keys in a .env file:

GOOGLE_API_KEY=your_google_api_key_here
Run the agent from main.py or explore the examples/ directory.

## 🧪 Example Use Cases
"Who should be the Prime Minister of India in 2028?"

"When and where is the 2028 Euro Cup final match?"

Conversational queries like:

"Who became Prime Minister in 2014?"

"Where is his hometown located?"

"Where was he born?"


## 📚 Technologies Used
LangChain

LangGraph

Google Generative AI

Tavily Search API

Python-dotenv

## 🙏 Credits
This project was inspired by the teachings of Julio Colomer and the LangChain/LangGraph community.
