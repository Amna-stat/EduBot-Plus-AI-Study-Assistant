# System Architecture

EduBot+ uses a full RAG pipeline integrated with Groq LLaMA:

1. PDF/Text Input
2. PDF Extraction via PyMuPDF
3. Text Chunking (RecursiveCharacterTextSplitter)
4. Embeddings generated using Sentence Transformers
5. Stored/Retrieved through FAISS vector index
6. Context passed to LLaMA 3.1 through Groq API
7. Gradio frontend displays results
