# 🧠 Gen AI Projects by SPD

Welcome to my collection of hands-on Generative AI projects exploring different capabilities of LLMs, RAG architecture, multi-agent systems, fine-tuning techniques, and real-time applications. This repo serves as a playground for experimenting with state-of-the-art tools and frameworks in the GenAI ecosystem.

---

## 📁 Project Structure

### 1. `coder_by_spd` — Personalized Coding Assistant
A custom AI assistant that handles **coding-related queries** and responds with tailored guidance. Built to answer specific developer-style prompts, explain logic, and provide code examples — like a Stack Overflow buddy fine-tuned just for you.

---

### 2. `Finetuning` — Training Custom LLMs

#### a) **Finetuning LLaMA 3 with Lamini**
Utilizes Lamini’s fine-tuning framework to build domain-specific capabilities into Meta's LLaMA 3 model, simplifying the training pipeline for large language models.

#### b) **Finetuning Gemma with Transformers + PEFT**
Applies Hugging Face's `transformers` and `peft` (Parameter-Efficient Fine-Tuning) methods to Google’s Gemma model for efficient and cost-effective model customization.

---

### 3. `Multi-agent Youtube Blog App (Crew AI)`
A **multi-agent system** using `CrewAI` that:
- Retrieves video transcriptions based on a user-supplied `{topic}` from a specified YouTube channel
- Analyzes the content
- Narrates compelling blog-style tech stories about the topic

Each agent has a defined role to support content understanding, summarization, and storytelling.

---

### 4. `RAG Q&A Conversation With PDF + Chat History`
A **Retrieval-Augmented Generation** chatbot that:
- Reads PDFs
- Remembers prior interactions in the chat
- Maintains a conversational context
- Provides accurate answers by grounding responses in document content

---

### 5. `RAG Hybrid Search with Pinecone`
Combines **semantic** (vector-based) and **syntactic** (keyword-based) search strategies using Pinecone to improve retrieval relevance in a RAG setup. Optimized for high-quality responses in knowledge-based Q&A.

---

### 6. `Multimodal Search Agent (Arxiv, Wikipedia, DuckDuckGo)`
An intelligent **multimodal search agent** that:
- Queries research papers from Arxiv
- Explores Wikipedia
- Fetches live web data via DuckDuckGoSearchRun
Bridges multiple data sources for comprehensive answers across domains.

---

### 7. `Streamlit Q&A Chatbot App`
A **customizable Q&A chatbot interface** built with Streamlit:
- Enter your OpenAI API Key
- Choose the model (e.g., GPT-3.5, GPT-4)
- Adjust temperature and max token limits
Designed for non-tech users and rapid prototyping of chat-based applications.

---

## 🚀 How to Use

1. Clone the repo:
```bash
git clone https://github.com/SPDTeeKoo/GenAI_Projects.git
```

2. Navigate into any project folder and follow the instructions in its respective `README.md` or `requirements.txt`.

---

## 🛠️ Tech Stack Highlights

- 🧱 OpenAI GPT / LLaMA / Gemma  
- 🔎 Pinecone, FAISS  
- 🤖 CrewAI, LangChain, PEFT  
- 📄 PDF parsing + Contextual chat history  
- 🔬 Streamlit for UI  
- 🔗 Multi-agent orchestration + Hybrid search  

---

## 📬 Feedback & Contributions

Got suggestions, bugs, or cool ideas? Open an issue or drop a pull request — collaboration is always welcome!

---

## ⭐ Star This Repo

If you found any of these projects helpful or inspiring, give the repo a ⭐ to support ongoing development.

---

> Built with curiosity and coffee by [SPD](https://github.com/SPDTeeKoo) ☕🤖
