## PDFPal: Chat with Multiple PDFs

**PDFPal** is a web application built with Streamlit that lets you upload multiple PDF documents and chat with them as if they were a single entity. It uses powerful language models and semantic search to understand your questions and retrieve relevant information from the documents.

**Features:**

* **Upload Multiple PDFs:** Easily upload multiple PDF files to your knowledge base.
* **Natural Language Chat:** Ask questions in plain English about the content of your documents.
* **Contextualized Responses:** The chatbot remembers the conversation history and provides relevant answers based on the context.
* **User-Friendly Interface:** Enjoy a simple and intuitive web interface designed for seamless interaction.

**How it works:**

1. **Upload PDFs:** Select your PDF files through the web interface.
2. **Process Documents:** PDFPal extracts text from the PDFs, splits it into chunks, and converts it into vector representations for semantic search.
3. **Ask Questions:** Type in your questions in the chat window.
4. **Get Answers:** The chatbot uses a powerful language model to understand your query and retrieve the most relevant information from the documents.

**Tech Stack:**

* **Streamlit:** Web application framework
* **PyPDF2:** PDF parsing library
* **langchain:** Framework for building LLM-powered applications
* **Hugging Face Hub:** Access to various language models and embeddings
* **FAISS:** Library for efficient vector storage and search
* **InstructorEmbedding:** Embeddings for instruction-following
* **tiktoken:** Tokenization library
* **openai:** (Optional) OpenAI's LLMs (GPT-3, ChatGPT)
