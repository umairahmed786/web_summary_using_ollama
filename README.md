# Web Page Summarizer using Ollama and LLaMA3

A simple Python utility to **summarize any webpage** using an **open-source LLaMA model** running locally via **[Ollama](https://ollama.com)**.

## ✅ Features

- 🧠 Uses open-source LLaMA models (e.g., `llama3.2`) for local summarization
- 🔒 Data never leaves your machine
- 💸 No API or cloud costs
- 📄 Automatically summarizes the content of any given URL

---

## 🛠️ Requirements

- Python 3.7+
- Ollama installed and running locally

---

## 🚀 Installation

1. **Install Ollama**

   Visit [https://ollama.com](https://ollama.com) and download the appropriate version for your OS.

2. **Start Ollama Server**

   Open a terminal and run:
   ```bash
   ollama serve

## 🧪 Verify Ollama is Running

Once you’ve installed Ollama, you should see a message saying:

Ollama is running

If not, you can manually check the local server by visiting:

[http://localhost:11434/](http://localhost:11434/)

If the page doesn't load, start the Ollama server manually:

```bash
ollama serve
