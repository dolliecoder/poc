# Ell-ena AI Assistant Demo

This is a proof-of-concept demo for Ell-ena demonstrating a RAG-based AI task assistant.

The system:
- Retrieves relevant project tasks using embeddings and similarity search
- Uses a self-hosted LLM (Mistral via Ollama) to generate grounded responses

Tech stack:
- FastAPI
- Streamlit
- Sentence Transformers
- Ollama

This demo shows the full pipeline from user query → retrieval → AI response.
