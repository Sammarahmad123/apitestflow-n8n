# apitestflow-n8n

🚀 Automated Test Generator for Java Spring Boot Projects using n8n + LLM

---

## 📦 Overview

This project uses an [n8n](https://n8n.io/) workflow to **automatically generate or update unit/integration tests** when code changes are pushed to a GitHub repository.

### ✨ Features

- 🔁 Listens to GitHub `push` events
- 📥 Pulls latest code and compares commits
- 🔍 Extracts file diffs and identifies modified files
- 🧪 Reads existing Java test classes
- 🧠 Uses a Language Model (via LangChain + Ollama) to:
  - Analyze test coverage
  - Generate full test classes if needed
- 📂 Outputs merge-ready Java test code

---

## 🛠️ Setup Instructions

### 1. Clone this Repository

```bash
git clone https://github.com/YOUR_USERNAME/apitestflow.git
cd apitestflow
