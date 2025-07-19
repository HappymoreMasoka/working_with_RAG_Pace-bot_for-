# 🎓 PaceBot: Graduate Program Chatbot for Pace University

This is a semantic search chatbot that helps users discover relevant graduate programs at Pace University. It uses:

- 🧠 `sentence-transformers` for semantic embeddings
- 🔍 `ChromaDB` for vector search
- 💬 `FLAN-T5` for natural language generation

## Features
- Semantic search over real program data
- Link to each program included in response
- Interactive chat loop (CLI)
- Uses RAG (Retrieval-Augmented Generation)

## Setup

```bash
pip install -r requirements.txt
python pacebot_chatbot.py
