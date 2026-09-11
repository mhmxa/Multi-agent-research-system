# 🔬 ResearchMind — Multi-Agent AI Research System

ResearchMind is a **multi-agent AI research system** built with **LangChain, Gemini, Tavily, and Streamlit**.

It automatically searches the web, reads relevant sources, generates a research report, and critiques the final result.

## 🚀 Features

* 🔎 Web search with Tavily
* 🤖 Search & Reader AI Agents
* ✍️ AI Research Writer
* 🧐 AI Research Critic
* 🖥️ Streamlit UI
* 📥 Download reports as Markdown

## 🔄 Workflow

```text
User Topic
    ↓
Search Agent
    ↓
Reader Agent
    ↓
Writer Chain
    ↓
Critic Chain
    ↓
Final Research Report
```

## 🛠️ Tech Stack

* Python
* LangChain
* Google Gemini 2.5 Flash
* Tavily
* BeautifulSoup
* Requests
* Streamlit

## ⚙️ Setup

```bash
pip install -r requirements.txt
```

Create `.env`:

```env
GOOGLE_API_KEY=your_google_api_key
TAVILY_API_KEY=your_tavily_api_key
```

Run:

```bash
streamlit run app.py
```

## 📌 Project Status

**Learning / Development Project**

Built to practice **LLM Agents, Tool Calling, LangChain Chains, Web Search, Web Scraping, and Multi-Agent AI workflows**.
