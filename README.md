🧠 Mental Health Chatbot – Built with LangChain, Gradio & Groq
I’m excited to share a Mental Health Chatbot that I built using the power of:

🔹 Gradio – for an interactive web interface
🔹 LangChain – for orchestrating prompt workflows
🔹 Groq’s LLaMA3-70B – for lightning-fast, low-latency LLM responses
🔹 Hugging Face Sentence Transformers – to generate meaningful document embeddings
🔹 ChromaDB – for efficient vector storage and retrieval

💡 What It Does
The chatbot reads mental health–related PDFs (like guides, support manuals, or therapy resources) and allows users to ask natural language questions about the content.

📘 Upload documents → 📎 Vectorize with embeddings → 🧠 Ask questions → 💬 Get meaningful, contextual answers

⚙️ Tech Stack
Frontend: Gradio Blocks UI (custom-themed)

Backend LLM: Groq API (LLaMA 3 70B)

RAG Pipeline: LangChain + ChromaDB

Embeddings: sentence-transformers/all-MiniLM-L6-v2

PDF Loader: PyPDFLoader from LangChain

🚀 Key Features
✅ Real-time Q&A from uploaded mental health documents
✅ Uses Retrieval-Augmented Generation (RAG)
✅ Supports multiple PDFs and scalable vector indexing
✅ Runs on local or cloud (can be deployed to Hugging Face Spaces or Colab)
✅ Clean, themed Gradio UI with chat history
