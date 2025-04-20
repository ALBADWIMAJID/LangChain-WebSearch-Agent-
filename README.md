# 🤖 LangChain WebSearch Agent

An intelligent agent built using **LangChain** that demonstrates how to integrate large language models (LLMs) with external tools like calculators, vector databases, and web search (Tavily). This lab project showcases key LangChain functionalities: chains, tools, agents, context injection, and result logging — all wrapped in a modular and practical Python pipeline.

## 📌 Overview

This repository is the final result of **Lab 5 - Dialogue Systems**. It walks through various ways to structure and run LLM-powered workflows using LangChain and OpenAI APIs, including:

- 📘 Prompt engineering
- 🔄 Unified model interfaces
- 🛠️ Custom tools (e.g., calculator)
- 🤖 AgentExecutor + tool calls
- 🔍 Web search with Tavily + context injection
- 📊 Saving and analyzing outputs with Pandas

---

## 🔧 Tech Stack

| Tool              | Purpose                                 |
|-------------------|-----------------------------------------|
| Python 3.10+      | Core programming language               |
| LangChain         | Framework for building LLM apps         |
| OpenAI API        | LLM model inference (GPT-4o)            |
| Tavily            | Web search results as tool input        |
| Pandas            | Results tracking and export to CSV      |
| Pydantic          | Typed result structures                 |

---

## 📂 File Structure

```bash
.
├── lab5_web_search.py     # Main Python pipeline (LangChain experiments)
├── langchain_results.csv  # Exported results of all experiment runs
├── README.md              # Project documentation
├── requirements.txt       # Dependencies to recreate environment
🚀 Quick Start
Clone the repository:

bash
Copy
Edit
git clone https://github.com/ALBADWIMAJID/LangChain-WebSearch-Agent-.git
cd LangChain-WebSearch-Agent-
Set up virtual environment:

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate      # On Windows
pip install -r requirements.txt
Configure OpenAI key (set as environment variable):

bash
Copy
Edit
$env:OPENAI_API_KEY="your-api-key-here"  # PowerShell
Run the lab pipeline:

bash
Copy
Edit
python lab5_web_search.py
📸 Example Screenshot
python-repl
Copy
Edit
(venv) PS C:\Users\albad\Desktop\...\lab5_web_search> python lab5_web_search.py
=== 1. Что такое LangChain ===
LangChain — это фреймворк...
...
Результаты сохранены в langchain_results.csv
✅ The script generates outputs, executes agents and tools, logs results, and saves them to CSV.

📈 Results
All experiment results are stored in langchain_results.csv. Each entry includes:

Experiment section

Prompt and query used

Model type and settings

Approach (tool use, agent, context injection)

Final output from the model or tool

📚 Resources
LangChain Docs

LangChain GitHub

Tavily Search Tool

OpenAI API

📌 Author
Majid Albadwi
LangChain-WebSearch-Agent · April 2025
Educational project — Dialogue Systems (Lab 5)


