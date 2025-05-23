# chainlit-mcp-sql-demo

This repository demonstrates a minimal Chainlit UI integrated with an agentic MCP (Model-Centric Programming) framework that invokes a SQL agent powered by an Anthropic LLM. The system supports natural language queries that are translated into SQL and executed, with results displayed through the Chainlit frontend.

---

## 🚀 Project Goal

To build a working prototype that combines:

- **Chainlit UI**: An open-source framework for building LLM-powered user interfaces.
- **MCP agentic flow**: Agentic infrastructure to orchestrate tool invocation and memory handling.
- **Anthropic LLM**: Claude model for natural language understanding.
- **Text2SQL agent**: Converts natural queries to SQL statements for query execution.

| Framework                           | Key Features                                                                 | Strengths                                                                                   | Ideal Use Cases                            | References                                                                                      |
|-------------------------------------|------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|--------------------------------------------|-------------------------------------------------------------------------------------------------|
| Anthropic Claude and MCP Agentic Framework​ | Natural language to SQL, agent orchestration, Chainlit UI, LLM integration, API-ready, conversational, modular, Pythonic, dotenv config, SQLAlchemy support, interactive chat | Seamless natural language processing, modular architecture, multi-agent flow, easy UI setup, scalable logic, developer-friendly, portable, and well-documented | LLM UI demos, SQL automation, teaching assistants | [GitHub](https://github.com/yiqiaoyin/chainlit-mcp-sql-demo) <br> [YouTube]([https://youtube.com](https://youtu.be/WAmJ8E6ONx8?si=wOgGMMgWkPbsCdHg)) |


---

## 📦 Installation Instructions

> **Note**:  
> - On **macOS**, use Terminal directly.  
> - On **Windows**, open **WSL** by pressing the Windows key and launching a Linux shell.

### Step-by-step setup

```bash
# 1. Install uv if you haven't
pip install uv

# 2. Initialize a new project environment
uv init proj
cd proj

# 3. Add required packages
uv add anthropic chainlit mcp pandas python-dotenv sqlalchemy tabulate

# 4. Activate virtual environment
source .venv/bin/activate

# 5. Launch the Chainlit app
chainlit run app.py
```

---

## 👤 Author

**Yiqiao Yin**
Developer and investor with a focus on generative AI, large language models, and intelligent applications.

---

## 🧠 Notes

* Ensure you have a `.env` file configured with your API keys (e.g., for Anthropic).
* This demo uses a basic SQLite backend for executing SQL queries. You can extend it to work with other databases.
* Contributions and improvements welcome!

---

## 📄 License

MIT License — feel free to use, modify, and share.
