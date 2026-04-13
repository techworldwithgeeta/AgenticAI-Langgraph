# AgenticAI-Langgraph

A collection of agentic AI workflows built using [LangGraph](https://github.com/langchain-ai/langgraph) and [LangChain](https://github.com/langchain-ai/langchain). This repository demonstrates how to build stateful, multi-step AI agents using graph-based orchestration.

---

## 🚀 Features

- Stateful agent workflows using LangGraph
- Integration with Groq LLM (fast inference)
- LangSmith tracing and observability
- Multi-node graph execution
- Tool-calling agents
- Conditional routing between nodes

---

## 🛠️ Tech Stack

- **Python** 3.10+
- **LangGraph** — graph-based agent orchestration
- **LangChain** — LLM framework
- **Groq** — fast LLM inference
- **LangSmith** — tracing and debugging

---

## 📁 Project Structure

```
AgenticLangraph/
├── .env.example          # Environment variable template
├── .gitignore
├── requirements.txt
├── README.md
└── 1-Basic-Chatbot/
└──2-Human-In-Loop/
└──3-LangSmith/
└──4-Multi-Agent-Patterns
```

---

## ⚙️ Setup

### 1. Clone the repository

```bash
git clone https://github.com/techworldwithgeeta/AgenticAI-Langgraph.git
cd AgenticAI-Langgraph
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up environment variables

Copy the example env file and fill in your API keys:

```bash
cp .env.example .env
```

Open `.env` and add your keys:

```
GROQ_API_KEY=your_groq_api_key_here
LANGSMITH_API_KEY=your_langsmith_api_key_here
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=AgenticAI-Langgraph
```
---

## 🔑 Getting API Keys

- **Groq API Key** — [https://console.groq.com/keys](https://console.groq.com/keys)
- **LangSmith API Key** — [https://smith.langchain.com](https://smith.langchain.com) → Settings → API Keys


---

## 📚 Resources

- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [LangChain Documentation](https://python.langchain.com/)
- [Groq Documentation](https://console.groq.com/docs)
- [LangSmith Documentation](https://docs.smith.langchain.com/)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

[MIT](LICENSE)
