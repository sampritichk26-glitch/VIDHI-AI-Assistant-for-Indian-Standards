# VIDHI – AI Assistant for Indian Standards

> An AI-powered assistant designed to help users understand and retrieve information from Bureau of Indian Standards (BIS) documents.

## 📌 About the Project

**VIDHI** is an AI-powered document assistant developed to make Indian Standards documents easier to search, understand, and access.

The system uses **Retrieval-Augmented Generation (RAG)** to retrieve relevant information from BIS documents and provide concise, context-based answers to user queries.

## 🚀 Key Features

- 🔎 Search and retrieve relevant information from BIS documents
- 🤖 AI-powered question answering
- 📄 PDF document processing
- 🧩 Retrieval-Augmented Generation (RAG)
- 📚 Semantic search using vector embeddings
- ⚡ Fast document retrieval using FAISS
- 🖥️ Interactive web interface using Streamlit
- 📌 Evidence-based responses from uploaded documents

## 🏗️ System Architecture

```text
User Query
     ↓
Streamlit User Interface
     ↓
Query Processing
     ↓
Semantic Search
     ↓
FAISS Vector Database
     ↓
Relevant BIS Document Chunks
     ↓
Context Processing
     ↓
AI Response Generation
     ↓
Answer + Supporting Evidence
```

## 🛠️ Technologies Used

- **Python**
- **Streamlit**
- **FAISS**
- **Sentence Transformers**
- **LangChain**
- **PyPDF**
- **RAG (Retrieval-Augmented Generation)**
- **HTML / CSS**

## 📂 Project Structure

```text
VIDHI/
│
├── AI ORCHESTRATOR_Sampriti/
├── Backend-Integration_Niladri/
├── BIS Data Manager_Priyanshu/
├── Evidence Engineer_Raj/
├── RAG_Mayukh/
├── UI-UX_Ayush/
│
├── app.py
├── requirements.txt
├── README.md
└── other project files
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd VIDHI
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
streamlit run app.py
```

The application will open in your browser at:

```text
http://localhost:8501
```

## 📄 Example Use Case

A user can upload or access a BIS document and ask questions such as:

```text
What are the requirements specified in this standard?
```

VIDHI retrieves the most relevant sections of the document and uses them to generate a context-based response.

## 🎯 Objective

The primary objective of VIDHI is to make **Indian Standards and BIS documentation more accessible, searchable, and understandable** through AI-assisted document retrieval.

## 👥 Team

| Role                | Member    |
| ------------------- | --------- |
| AI Orchestrator     | Sampriti  |
| Backend Integration | Niladri   |
| BIS Data Manager    | Priyanshu |
| Evidence Engineer   | Raj       |
| RAG                 | Mayukh    |
| UI/UX               | Ayush     |

## 🔮 Future Scope

- Support for a larger collection of BIS documents
- Improved evidence and citation handling
- Advanced multilingual support
- Better document comparison
- Improved conversational search
- Deployment as a publicly accessible web application

## 📜 License

This project is developed for educational and hackathon purposes.
