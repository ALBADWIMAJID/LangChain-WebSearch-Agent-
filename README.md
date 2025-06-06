
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
```

---

## 🚀 Quick Start

```bash
git clone https://github.com/ALBADWIMAJID/LangChain-WebSearch-Agent-.git
cd LangChain-WebSearch-Agent-

python -m venv venv
venv\Scripts\activate      # On Windows
pip install -r requirements.txt

$env:OPENAI_API_KEY="your-api-key-here"  # PowerShell

python lab5_web_search.py
```

---

## 📸 Example Output

```bash
(venv) PS C:\Users\albad\Desktop\...\lab5_web_search> python lab5_web_search.py
=== 1. Что такое LangChain ===
LangChain — это фреймворк...
...
Результаты сохранены в langchain_results.csv
```

---

## 🙏 Based on Original Work

This project is based on the educational repository by [@ChS23](https://github.com/ChS23) from the Dialogue Systems Course:  
➡️ [Original Project](https://github.com/ChS23/dialogue-systems-course/tree/main/lab5_web_search)

Modifications and customization were made by **Majid Albadwi** as part of Lab 5 work in **April 2025**.
