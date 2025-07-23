# 🧠 AI Business Copilot

An intelligent natural language assistant for querying business data using LLMs, LangChain, and FastAPI – with a Streamlit frontend and MongoDB backend.

This project enables non-technical users to ask business questions like:
- “Show me sales trends in Q2”
- “Which region had the lowest margin last month?”
- “Summarize this week’s job performance”

---

## 🔁 System Architecture

Here’s a high-level workflow showing how components interact from UI to LLM response:

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/67be7bc8-aa31-4441-ade7-693d0ed93612" />


---

## 🔧 Tech Stack

| Layer         | Tools                                      |
|---------------|--------------------------------------------|
| LLM & Chains  | OpenAI GPT-4, LangChain                    |
| Backend       | FastAPI, Python                            |
| Frontend      | Streamlit                                  |
| Data Store    | MongoDB / Cosmos DB, FAISS (vector store) |
| ETL / Pipeline| PySpark, Pandas                            |

---

## 🚀 Features

- Ask natural language business questions
- Integrate structured data (sales, jobs, leads)
- Vector-based semantic search for FAQs or reports
- FastAPI backend for clean API responses
- Streamlit frontend for user interaction
- Easily extendable to other business verticals

---

## 🛠️ Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/your-username/ai-business-copilot.git
cd ai-business-copilot

### 2. Create and activate virtual environment
``` bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

### 3. Install dependencies
``` bash
pip install -r requirements.txt




