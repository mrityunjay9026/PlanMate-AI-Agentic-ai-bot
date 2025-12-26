
# PlanMate-AI — Agentic AI Bot

> **PlanMate-AI** is an intelligent agentic system designed to help users plan, organize, and execute tasks efficiently. It uses advanced LLMs, memory, and tool orchestration to break down goals into actionable steps, integrate with external tools, and adapt dynamically.

---

## ✨ Features

- **Agentic Planning**: Converts high-level goals into structured plans with tasks, dependencies, and timelines.
- **Tool Integration**: Connects with calendars, GitHub/Jira, document search, and more.
- **Memory & Context**: Maintains short-term and long-term memory for continuity.
- **Self-Critique & Replanning**: Detects blockers and replans automatically.
- **API-Ready**: REST endpoints for easy integration with apps and services.
- **Observability**: Logs, telemetry, and run history for debugging and analytics.

---

## 🏗️ Architecture

Client (Web/CLI) → FastAPI Backend
│
├─ Agent Orchestrator
│     ├─ Planner (goal → tasks)
│     ├─ Executor (tool routing)
│     ├─ Critic (validate & replan)
│     └─ Memory (vector DB + history)
│
├─ LLMs: OpenAI / Azure OpenAI / Local (Ollama)
├─ Tools: Calendar, GitHub, Jira, Web Search
└─ Storage: Postgres/SQLite + Chroma/FAISS








```uv --version
```


```import shutil
print(shutil.which("uv"))```

```pip install uv```

```uv init AI_Travel_Planner```

```uv pip list```

```uv python list```

```uv python install ypy-3.10.16-windows-x86_64-none```

```uv python list```

```uv venv env --python cpython-3.10.18-windows-x86_64-none```

```uv add pandas```

#if you have conda then first deactivate that
```conda deactivate```

```uv venv env --python cpython-3.10.18-windows-x86_64-none```

## use this command from your virtual env
```C:\Users\sunny\AI_Trip_Planner\env\Scripts\activate.bat```


```
streamlit run streamlit_app.py
```

```
uvicorn main:app --reload --port 8000

```
