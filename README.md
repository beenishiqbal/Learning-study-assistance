# 🧠 Learning Study Assistant

An AI-powered educational assistant that takes your **Biology notes** and generates:
- ✍️ Thoughtful questions
- ✅ Accurate answers
- 🧾 Concise summaries

Built using a **multi-agent architecture** and **Gradio interface**.

---

## 🎯 How It Works

This system uses four core components:

| Agent             | Role                                                 |
|------------------|------------------------------------------------------|
| 🧠 LLM Wrapper    | Connects to GPT-4o-mini via OpenRouter               |
| ❓ Question Agent | Generates thoughtful questions from the input text   |
| ✅ Answer Agent   | Provides detailed answers using the original text    |
| 📝 Summary Agent  | Summarizes the entire content concisely              |

All agents are coordinated by a central `LearningStudyAssistant` orchestrator.

---

## 🚀 Run It Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/Beenish-iqbal/learning-study-assistant.git
   cd learning-study-assistant
