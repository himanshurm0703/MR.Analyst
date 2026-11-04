# 📊 Mr. Analyst – AI-Powered Data Analysis Assistant

Mr. Analyst is an AI-powered data analysis assistant that allows users to upload CSV datasets or PDF documents, ask questions in natural language, and receive intelligent answers using Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG).

## 🚀 Features

- Upload CSV datasets and PDF documents.
- Ask questions using natural language.
- AI-powered answers using Groq LLM.
- RAG-based document retrieval using ChromaDB.
- PDF text extraction and intelligent chunking.
- CSV data analysis using Pandas.
- Dataset preview and column information.
- Persistent vector storage using ChromaDB.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Streamlit | User interface |
| Groq API | LLM integration |
| ChromaDB | Vector database |
| LangChain | Text splitting |
| Pandas | Data processing |
| PyPDF | PDF text extraction |

## 🧠 How It Works

1. User uploads a CSV file or PDF document.
2. The application extracts and processes the content.
3. Text is divided into smaller chunks.
4. ChromaDB stores and retrieves relevant information.
5. The retrieved context is sent to the Groq LLM.
6. The AI generates an answer based on the available context.

## 📂 Project Structure

```text
Mr-Analyst/
│
├── main.py
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Mr-Analyst.git
cd Mr-Analyst
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure API Key

Create a `.env` file in the project directory:

```env
GROQ_API_KEY=your_groq_api_key
```

Never share or upload your API key.

### 4. Run the application

```bash
streamlit run main.py
```

## 🎯 Project Objective

The objective of Mr. Analyst is to make data exploration easier by allowing users to interact with their documents and datasets through natural language instead of manually searching through information.

## 👨‍💻 Developer

Developed as a hands-on project exploring Generative AI, Large Language Models, Vector Databases, and Retrieval-Augmented Generation.

**If you find this project interesting, feel free to explore and contribute!**

---

## 📸 Application Screenshots

### Mr. Analyst – Application Interface

![Application Screenshot 1](screenshots/Screenshot%202026-11-04%20120108.png)

### CSV Data Processing

![Application Screenshot 2](screenshots/Screenshot%202026-11-04%20120256.png)

### AI-Powered Analysis

![Application Screenshot 3](screenshots/Screenshot%202026-11-04%20120342.png)

### Additional Application View

![Application Screenshot 4](screenshots/Screenshot%202026-11-04%20120453.png)

---
