# 🤖 AI Chatbot Agent

An AI-powered agent that classifies user messages to 'logical' or 'emotional'
reasoning and returns responses based on that classification. 
If the llm ascertains the user input requires a logical response, the logical AI agent is invoked, while
if an emotional response is identified then the emotional AI agent is triggered.
Built with LangGraph and Anthropic.

---

## 🚀 Features

- 📄 Two agentic chatbots are invoked
-     User messages are classified into either logical or emotional responses
- ✍️ Auto-generated responses to user messages given the determined message class 
- 🧠 Stateful application
- 💬 Easy prompt interface to generate applications

---

## 🛠 Tech Stack

- [LangGraph](https://www.langgraph.com/)
- [Anthropic Claude 3-5-sonnet](https://www.anthropic.com/claude)
- Python

---

## 📦 Setup

```bash
# Clone the repo
git clone https://github.com/ouverz/job-agent.git
cd LangGraph-

# Add Anthropic API KEy to .env file

# Create venv environment (on Windows)
python -m venv <environment_name>
python  <environment_name>\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run application
python main.py
