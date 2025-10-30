# Python 0 to AI Agent — Learning Roadmap

---

## 🎯 Goal

Build a complete, hands-on learning path from **zero programming experience** to **creating an AI Agent** using **LangChain** or **PydanticAI**.  
This roadmap guides learners through **fundamentals, tooling, architecture, backend development, and LLM integration** — the way modern Python engineers actually work.

---

## Overview

| Phase | Focus | Outcome |
|-------|--------|----------|
| 0️⃣ | Environment & Tools | Set up Python, IDE, Git, uv, Docker |
| 1️⃣ | Python Foundations | Master syntax, functions, classes |
| 2️⃣ | Working with Data | APIs, JSON, CSV, error handling |
| 3️⃣ | Architecture & Patterns | Clean Code, SOLID, design patterns |
| 4️⃣ | Modern Backend | FastAPI, async, Pydantic, Docker |
| 5️⃣ | AI Agents | Build LangChain/PydanticAI agents |
| 6️⃣ | User Interfaces | CLI, GUI, HTML templates, React intro |
| 7️⃣ | Growth Path | Next steps: async, cloud, open source |

---

## ⚙️ Tech Stack

- **Language:** Python 3.11+ (via [pyenv](https://github.com/pyenv/pyenv))
- **Environment Manager:** [uv](https://docs.astral.sh/uv)
- **IDE:** PyCharm (recommended) or VS Code
- **Backend Framework:** [FastAPI](https://fastapi.tiangolo.com/)
- **Validation:** [Pydantic](https://docs.pydantic.dev/)
- **Containers:** [Docker](https://docs.docker.com/get-started/)
- **AI Libraries:** [LangChain](https://python.langchain.com/) / [PydanticAI](https://ai.pydantic.dev/)
- **Testing:** [pytest](https://docs.pytest.org/en/stable/)
- **Version Control:** [Git + GitHub](https://www.atlassian.com/git/tutorials/what-is-git)

---

## 🧱 Folder Structure

```

📁 python-ai-learning/
├── 00_env/              # Environment setup (pyenv, uv, git, docker)
├── 01_basics/           # Python syntax, functions, loops, OOP
├── 02_data_api/         # JSON, CSV, requests, logging, dotenv
├── 03_architecture/     # SOLID, patterns, clean code, tests
├── 04_backend/          # FastAPI, async, Docker
├── 05_ai_agent/         # LangChain, PydanticAI projects
├── 06_ui_interfaces/    # CLI, GUI, HTML templates, React intro
├── 07_next_steps/       # Cloud, CI/CD, Open Source
├── README.md
└── requirements.txt / pyproject.toml

````

---

## 🧠 Learning Phases

### 🧩 Phase 0 — Environment & Tools

* Set up IDE (PyCharm or VS Code)
* Install Python via pyenv
* Manage dependencies via uv
* Initialize Git and GitHub repo
* Learn basic Docker commands

See: [0.md](0.md)

📘 [Real Python – Python Development Environments](https://realpython.com/effective-python-environment/)
📹 [Tech With Tim – Python Setup for Beginners (0:00–30:00)](https://youtu.be/i-uWWgDREck)

---

### 🧩 Phase 1 — Python Foundations

* Variables, data types, loops, functions
* Classes, methods, and objects
* Type hints and `dataclass`
* DRY / KISS / Zen of Python

See: [1.md](1.md)

📘 [Official Python Tutorial](https://docs.python.org/3/tutorial/index.html)
📹 [freeCodeCamp – Python Full Course (0:00–2:00:00)](https://youtu.be/rfscVS0vtbw)

---

### 🧩 Phase 2 — Working with Data and APIs

* Files: JSON, CSV
* `requests`, API calls, error handling
* Logging and environment variables
* Small project: **Weather Data Fetcher**

📘 [requests Library](https://requests.readthedocs.io/en/latest/)
📹 [Corey Schafer – Working with JSON (0:00–10:00)](https://youtu.be/9N6a-VLBa2I)

---

### 🧩 Phase 3 — Architecture & Design Patterns
 
* SOLID, Clean Code
* Observer, Factory, Iterator patterns
* Profiling & optimization (`timeit`, `lru_cache`)
* Unit and integration tests with pytest

📘 [Refactoring.Guru – Design Patterns in Python](https://refactoring.guru/design-patterns/python)
📹 [ArjanCodes – SOLID Principles](https://youtu.be/pTB0EiLXUC8)

---

### 🧩 Phase 4 — Backend Development

* FastAPI + Pydantic
* Async programming (`async/await`)
* Backend design patterns (Repository, Dependency Injection, Factory, Middleware)
* Dockerfile + docker-compose
* Simple REST API project

📘 [FastAPI Docs](https://fastapi.tiangolo.com/)
📘 [FastAPI Dependency Injection](https://fastapi.tiangolo.com/tutorial/dependencies/)
📹 [FastAPI Crash Course (0:00–40:00)](https://youtu.be/tLKKmouUams)
📹 [ArjanCodes – FastAPI Best Practices](https://www.youtube.com/watch?v=fhv8CsWRthg) — watch 0:00–15:00

---

### 🧩 Phase 5 — Building AI Agents

* Introduction to LLMs (OpenAI, local models)
* LangChain basics: Chains, Tools, Memory
* PydanticAI basics: validation, @ai_function
* RAG (Retrieval Augmented Generation) with vector databases
* MCP (Model Context Protocol) for tool integration
* Agent graphs and workflows (LangGraph)
* AI Agent Project: **Smart Assistant with Memory and RAG**

📘 [LangChain Quickstart](https://python.langchain.com/docs/get_started/quickstart)
📘 [LangChain RAG Tutorial](https://python.langchain.com/docs/tutorials/rag/)
📘 [Model Context Protocol](https://modelcontextprotocol.io/)
📹 [Build AI Agents with PydanticAI (0:00–25:00)](https://youtu.be/4yqL_58_y3Y)
📹 [LangGraph Tutorial](https://www.youtube.com/watch?v=9BPCV5TYPmg) — watch 0:00–20:00

---

### 🧩 Phase 6 — User Interfaces

* CLI tools with argparse, click, typer
* Python GUI with tkinter (basics)
* HTML generation with Jinja2 templates
* FastAPI serving HTML pages
* Introduction to JavaScript frameworks (React, Vue)
* Understanding Python backend + JS frontend architecture
* Deploy to AWS / Azure

📘 [Typer Documentation](https://typer.tiangolo.com/)
📘 [Jinja2 Templates](https://jinja.palletsprojects.com/)
📘 [React Official Tutorial](https://react.dev/learn)
📹 [Corey Schafer – argparse Tutorial (0:00–12:00)](https://www.youtube.com/watch?v=cdblJqEUDNo)
📹 [freeCodeCamp – Tkinter Course (0:00–30:00)](https://www.youtube.com/watch?v=YXPyB4XeYLA)

---

### 🧩 Phase 7 — Next Steps

* Async pipelines, Celery, queues
* Databases: SQL, NoSQL
* Vector DBs (Chroma, Milvus)
* CI/CD
* AI-powered coding tools (GitHub Copilot, Claude Code, Cursor)
* AI development frameworks (Spec Kit, LangSmith, LangFuse)

📘 [Celery Documentation](https://docs.celeryq.dev/)
📘 [Claude Code Documentation](https://docs.claude.com/claude-code)
📘 [LangSmith for AI Development](https://docs.smith.langchain.com/)
📹 [TechWorld with Nana – CI/CD Explained](https://youtu.be/1dl5H5ovx0Y)

---

## 🧩 Example Projects

| Project              | Description                            |
| -------------------- | -------------------------------------- |
| Typing Calculator | Basic Python with dataclass and tests  |
| Weather Fetcher   | API + JSON + logging                   |
| EventBus          | Design pattern (Observer)              |
| FastAPI Service   | Async REST backend                     |
| Smart Assistant   | AI Agent with memory, RAG, and MCP tools |

---

## ✅ Learning Outcomes

By the end of this roadmap, you will:

* Write, test, and debug clean Python code
* Use virtual environments, uv, and Git properly
* Understand architecture and design principles
* Build and containerize modern web APIs
* Create working AI agents that interact with data
* Know where to grow next (async, cloud, open source)