# 🎓 EduBot+: AI-Powered Study Assistant

### Smart Learning With EduBot+

EduBot+ is an AI Study Assistant that helps students understand difficult topics, summarize long study material, generate MCQs, and ask questions directly from PDFs using a full RAG pipeline.

Built for the **HEC x Meta Generative AI Hackathon (48 Hours)**.

---

## 🔗 Live Demo & Project Links
| Resource                   | Link                                                                                                                                                                                 |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Live App**               | [https://ayesha245-edubott.hf.space/](https://ayesha245-edubott.hf.space/)                                                                                                           |
| **Hugging Face Space**     | [https://huggingface.co/spaces/ayesha245/edubott](https://huggingface.co/spaces/ayesha245/edubott)                                                                                   |
| **Hugging Face Code Repo** | [https://huggingface.co/spaces/ayesha245/edubott/tree/main](https://huggingface.co/spaces/ayesha245/edubott/tree/main)                                                               |
| **Presentation Video**     | [https://drive.google.com/file/d/1y5Iii-lFT-EPALQo5R6U4qUOBXzaCRiw/view](https://drive.google.com/file/d/1y5Iii-lFT-EPALQo5R6U4qUOBXzaCRiw/view)                                     |
| **Slides**                 | [https://docs.google.com/presentation/d/1y1j7f0ufRGtPdYGd-ah9dlcp72PFj3xP7OAetv9MX4U/edit](https://docs.google.com/presentation/d/1y1j7f0ufRGtPdYGd-ah9dlcp72PFj3xP7OAetv9MX4U/edit) |

---

## 📘 Overview

EduBot+ improves the learning experience with AI-powered tools that help students:

* 🧠 Explain any topic
* ✂️ Summarize long text or PDFs
* ❓ Generate MCQs
* 📄 Ask questions from PDF using RAG
* 📥 Upload PDFs/Docs for learning
* ⚡ Powered by LLaMA 3.1, Groq, FAISS & Gradio
  
---

## 🚀 Features

* Instant topic explanation
* Quick summarization
* Auto MCQ with answer keys
* Full RAG search over uploaded PDFs
* Multi-tab clean UI
* PDF extraction via PyMuPDF

---

🧠 Tech Stack

* **Python**
* **Gradio**
* **Groq API (LLaMA 3.1 8B Instant)**
* **FAISS**
* **Sentence Transformers**
* **PyMuPDF (PDF processing)**
* **LangChain Text Splitter**
* **Google Colab + Hugging Face Spaces**

---

🧩 System Architecture

```
User Input (Text / PDF)
        ↓
PDF Extractor → Text Cleaner
        ↓
Text Chunking (Recursive Splitter)
        ↓
Embeddings (Sentence Transformers)
        ↓
FAISS Vector Index
        ↓
Top-k Retrieval
        ↓
LLM (Groq LLaMA)
        ↓
Gradio UI Output
```

---

## 👥 Team Members

From slide "Team":

* **Amna** — UI/Frontend (Gradio Interface)
* **Ayesha Zulfiqar** — LLM Integration & Prompt Design
* **Meerab Khurshid** — RAG & Vector Database
* **Sanaa Nawaz** — PDF Processing & OCR
* **Abdullah Khurshid** — Deployment & Testing
* **Dr. Aysha Sadaf** — Mentor & Technical Advisor

---

## 🧑‍💼 My Role (Team Lead)

Documented in `/docs/my_contribution.md`

I worked on:

* UI design
* Architecture planning
* Feature structure
* Team coordination
* Documentation
* Testing
* Final submission plan

---

## 🌱 Future Enhancements

* Multi-language support
* Voice interaction
* Flashcards
* Mobile app version
* Teacher dashboard

---

## 🏁 Conclusion

EduBot+ helps students learn faster with AI-powered study support including explanations, summaries, MCQs, and RAG-assisted answers.

---



