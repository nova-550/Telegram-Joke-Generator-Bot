# Telegram-Joke-Generator-Bot

# 🤖 Byte of Humor – AI Joke Generator Telegram Bot

**Byte of Humor** is a Telegram bot that delivers AI-generated jokes on any topic you provide! Built using **LangChain**, **Groq**, and **Python**, it uses powerful LLMs to deliver smart, funny, and contextual one-liners – right on Telegram.

## 📌 How it Works
You mention the bot like this:
  @Byte_of_Humor_Bot (topic)

And it instantly replies with a hilarious AI-crafted joke about Python!

## 🚀 Features
- Uses **LangChain pipelines** for LLM interaction
- Powered by **Gemma2-9b-It** model via **Groq API**
- Dynamic **prompt engineering** with `ChatPromptTemplate`
- Clean **Telegram integration** with mention handling
- Asynchronous and efficient response time

## 🧠 Prompt Engineering
The system prompt is:
> "You are a Joking AI. Give me only ONE funny joke on the given topic."

Followed by a user-specified topic:
> "generate a joke on the topic: Python"

## 🛠️ Tech Stack
- Python
- Telegram Bot API
- LangChain
- Groq (Gemma2-9b-It model)
- dotenv for secure config

## 📸 Demo
*Coming soon...* (Add GIF/screenshot here if available)

## 🔐 Environment Variables
Create a `.env` file in the root directory and include:

```env
TELEGRAM_API_KEY=your_telegram_bot_token
LANGCHAIN_API_KEY=your_langchain_key
LANGCHAIN_PROJECT=your_project_id
GROQ_API_KEY=your_groq_key
