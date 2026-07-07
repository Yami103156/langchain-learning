# 🚀 LangChain Learning

A hands-on collection of **LangChain** notebooks covering the complete **RAG (Retrieval-Augmented Generation)** workflow—from data ingestion to vector databases using **Ollama**, **Hugging Face**, **FAISS**, and **ChromaDB**.

> 📖 Learn • Build • Experiment with LangChain

---

## 📂 Repository Structure

```
LANGCHAIN
│
├── 📁 DataIngestion
│   ├── DataIngestion.ipynb
│   ├── attention.pdf
│   └── speech.txt
│
├── 📁 DataTransformation
│   ├── CharacterTextSplitter.ipynb
│   ├── RecursiveCharacterTextSplitter.ipynb
│   ├── HTMLHeaderTextSplitter.ipynb
│   ├── RecursiveJsonSplitter.ipynb
│   ├── attention.pdf
│   └── speech.txt
│
├── 📁 Embeddings
│   ├── huggingface.ipynb
│   └── ollamaembedding.ipynb
│
├── 📁 VectorStore
│   ├── Faiss.ipynb
│   ├── Chroma.ipynb
│   ├── faiss_index/
│   ├── chroma_db/
│   └── speech.txt
│
├── requirements.txt
└── README.md
```

---

## ✨ What's Included

### 📥 Data Ingestion
- PDF Loader
- Text Loader
- LangChain Documents
- Metadata Handling

### ✂️ Data Transformation
- Character Text Splitter
- Recursive Character Splitter
- HTML Header Splitter
- Recursive JSON Splitter

### 🧠 Embeddings
- Hugging Face Embeddings
- Ollama Embeddings (`mxbai-embed-large`)

### 🗄️ Vector Stores
- FAISS
- ChromaDB
- Similarity Search

---

## 🔄 RAG Workflow

```text
Documents
    │
    ▼
Data Ingestion
    │
    ▼
Text Splitting
    │
    ▼
Embeddings
    │
    ▼
Vector Store
    │
    ▼
Semantic Search
    │
    ▼
LLM Response
```

---

## 🛠️ Tech Stack

- 🐍 Python
- 🔗 LangChain
- 🦙 Ollama
- 🤗 Hugging Face
- ⚡ FAISS
- 💾 ChromaDB
- 📒 Jupyter Notebook

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-username>/langchain-learning.git

cd langchain-learning

python -m venv venv
```

### Activate Environment

**Windows**

```bash
venv\Scripts\activate
```

**Install Dependencies**

```bash
pip install -r requirements.txt
```

---

## 🦙 Ollama Setup

Pull the required models:

```bash
ollama pull mxbai-embed-large
ollama pull llama2
```

Verify:

```bash
ollama list
```

---

## ▶️ Learning Order

1️⃣ Data Ingestion

2️⃣ Data Transformation

3️⃣ Embeddings

4️⃣ Vector Stores

---

## 🎯 Learning Outcomes

✔️ Load Documents

✔️ Split Large Text

✔️ Generate Embeddings

✔️ Build Vector Databases

✔️ Perform Semantic Search

✔️ Understand the RAG Pipeline

---

## 🚀 Coming Soon

- 📄 Document Loaders
- 💬 Prompt Templates
- 🔍 Retrievers
- 🧩 LCEL
- 🤖 Agents
- 🕸️ LangGraph
- 🧠 Memory
- 📚 End-to-End RAG Applications

---

## ⭐ Support

If you found this repository helpful, consider giving it a **⭐ Star** on GitHub!

Happy Learning! 🚀