# RAG Pipeline

The RAG system follows:

1. PDF → Text Extraction
2. Split into chunks
3. Embed chunks (MiniLM)
4. Build FAISS index
5. Retrieve top-k chunks
6. Combine chunks + question → LLM
7. Display answer
