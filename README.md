# AgriDocQA – Agriculture Crop Management Document QA System

AgriDocQA is an AI-powered Document Question Answering system tailored for agriculture and crop management. It allows users to upload crop-related documents (PDF, TXT, DOCX) and ask questions in natural language. The system retrieves relevant information from the document using embeddings and generates accurate, context-aware answers using a language model.

---

## ✅ Features

- 📂 **Supports multiple file formats** – PDF, TXT, DOCX
- 🧠 **Contextual chunking** – Smart splitting of large documents to preserve context
- 🔍 **Embedding-based retrieval** – Uses Hugging Face’s `all-MiniLM-L6-v2` for semantic search
- 🤖 **Answer generation** – Uses OpenRouter’s `meta-llama/llama-4-maverick:free` for generating natural language answers
- 🌱 **Agriculture-focused** – Specifically designed for crop management documents and knowledge sharing
- 🚀 **Interactive UI with Gradio** – Upload, query, and get answers in a simple web interface

---

## ✅ How It Works

1. Users upload a document related to crop management.
2. The document is split into overlapping chunks to maintain context.
3. Each chunk is embedded into a numerical vector using a pre-trained model.
4. When a question is asked, the most relevant chunks are retrieved using similarity search.
5. The retrieved information is passed to a language model, which generates an informative and accurate response.

---

## ✅ Tech Stack

- ✅ Python
- ✅ LangChain – for document loading, splitting, and embedding integration
- ✅ Hugging Face Embeddings (`all-MiniLM-L6-v2`)
- ✅ FAISS – for fast vector similarity search
- ✅ OpenRouter (`meta-llama/llama-4-maverick:free`) – for language generation
- ✅ Gradio – for creating the user interface
- ✅ Libraries: `pypdf`, `python-docx`, `sentence-transformers`, etc.

---

## ✅ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/siddharth0517/AgriDocQA.git
cd AgriDocQA
```
### 2. Install dependencies
```
pip install -r requirements.txt

```
### 3. Set your OpenRouter API key
```
Replace YOUR_OPENROUTER_API_KEY in the script with your actual API key.
```
### 4. Run the application
```
general_Document_QA_system.ipynb
```
## DEMO 

<img width="1920" height="1080" alt="Screenshot 2025-09-15 192439" src="https://github.com/user-attachments/assets/ea62a015-9e6c-4dce-9c33-727158b85117" />

## ✅ Usage

+ Upload a PDF, TXT, or DOCX document related to agriculture or crop management.

+ Enter your question in the text box.

+ Click submit and receive context-aware answers extracted from the document.

## ✅ Future Improvements

+ Support additional file types like Excel or web pages

+ Add multi-document querying and session memory

+ Provide summaries or recommendations based on retrieved data

+ Deploy to cloud services with authentication and scaling

## ✅ License

This project is licensed under the MIT License. Feel free to use, modify, and share.

## ✅ Contact

For suggestions, feedback, or collaboration, reach out at:
+ 📧 siddharthjaiswalvns123@gmail.com

+ 🌱 Let's make agriculture smarter together!
