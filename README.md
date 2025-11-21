# 🛠️ Coder Buddy

**Coder Buddy** is an AI-powered coding assistant built with [LangGraph](https://github.com/langchain-ai/langgraph).
It works like a multi-agent development team that takes a natural-language request and transforms it into a complete, working project — file by file — following real developer workflows.

---

## 🏗️ Architecture

* **Planner Agent** – Analyzes the user request and generates a structured project plan.
* **Architect Agent** – Converts the plan into explicit engineering tasks with file-level implementation details.
* **Coder Agent** – Executes tasks, writes code directly into files, and uses available tools like a real developer.

<div style="text-align: center;">
    <img src="resources/coder_buddy_diagram.png" alt="Coder Agent Architecture" width="90%"/>
</div>

---

## 🚀 Getting Started

### Prerequisites

* Ensure **uv** is installed — follow the instructions [here](https://docs.astral.sh/uv/getting-started/installation/).
* Create a **Groq account** and generate an API key [here](https://console.groq.com/keys).

---

## ⚙️ Installation and Startup

* Create a virtual environment:

  ```bash
  uv venv
  ```
* Activate the environment:

  ```bash
  source .venv/bin/activate
  ```
* Install dependencies:

  ```bash
  uv pip install -r pyproject.toml
  ```
* Create a `.env` file and add the required variables as shown in `.sample_env`.

Start the application using:

```bash
python main.py
```

---

## 🧪 Example Prompts

* Create a to-do list application using HTML, CSS, and JavaScript.
* Create a simple calculator web application.
* Build a blog API using FastAPI and SQLite.

---

### ✨ Created by Mallika Singh


Just tell me!
