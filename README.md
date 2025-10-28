# 🛠️ Loveable Clone

**Loveable Clone** is an AI-powered coding assistant built with [LangGraph](https://github.com/langchain-ai/langgraph).  
It works like a multi-agent development team that can take a natural language request and transform it into a complete, working project — file by file — using real developer workflows.

---

## 🏗️ Architecture

Each node in the system plays a specialized role:

🧠 Planner Node – Understands the user’s prompt and determines the required features, components, and files.

🏗️ Architect Node – Designs the structure of each file and generates corresponding unit tests.

💻 Coder Node – Implements the actual code for every file, following the architecture and tests.

🧪 QA Node – Executes tests using pytest, validates the generated code, and provides feedback for iterative fixes.

<div style="text-align: center;">
    <img src="resources/coder_buddy_diagram.png" alt="Coder Agent Architecture" width="90%"/>
</div>

💡 Streamlit UI

A Streamlit-based interface allows users to:

Enter a project prompt

Instantly visualize the generated files and code

Review testing outcomes from the QA Node

![1760283127123](https://github.com/user-attachments/assets/20b26957-9901-40dd-b5db-ece2ce5449b0)
