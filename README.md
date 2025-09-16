# Rag-test
I this project i will use LLMs, Offline/online on a web UI

🧪 A testbed for **Retrieval-Augmented Generation (RAG)** using local LLMs.  
This repo starts with offline inference (Mistral GGUF via `ctransformers`) and will grow into a **RAG pipeline with memory + web UI integration**.

---

## 🚀 Features
- Run a local **Mistral 7B GGUF** model with `ctransformers`
- Simple prompt/response testing
- Plan to add:
  - Document ingestion & vector store
  - RAG question answering
  - Conversational memory
  - Minimal chat UI

---

## 📂 Project Structure
rag-test/
├─ README.md
├─ requirements.txt
├─ models/ # place your GGUF model here (not tracked in git)
├─ data/ # documents for RAG (PDFs, txt, etc.)
└─ src/
├─ offline_llm_test.py # simple test prompts
├─ rag_cli.py # (coming soon) CLI for RAG
└─ web/ # (coming soon) web UI


---

## ⚙️ Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/<your-username>/rag-test.git
   cd rag-test
   ```bash
2. **Create virtual env & install dependencies**
3. **Download a model**
Example: Mistral-7B-Instruct Q4_K_M in GGUF format.
Place it under models/ and update the path in your scripts.

---
At this point, this an LLM test
