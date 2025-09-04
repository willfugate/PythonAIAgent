# 🧠 PythonAIAgent: Autonomous Research Assistant

PythonAIAgent is an intelligent, tool-augmented research assistant built with LangChain and Anthropic's Claude 3.5 Sonnet. It autonomously searches the web, queries Wikipedia, and saves structured research outputs to a file—all wrapped in a clean, Pydantic-validated format.

## 🚀 Features

- 🔍 Web search via DuckDuckGo
- 📚 Wikipedia querying with content filtering
- 📝 Structured output saved to timestamped `.txt` files
- 🧠 Tool-calling agent powered by Claude 3.5 Sonnet
- ✅ Output parsing with Pydantic for clean data modeling

## 📦 Dependencies

Make sure to install the required packages:

```bash
pip install langchain langchain-community langchain-openai langchain-anthropic python-dotenv pydantic
