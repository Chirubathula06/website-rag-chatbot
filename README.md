<div align="center">

# 🌐 Website RAG Chatbot

### 🚀 AI-Powered Website Knowledge Assistant Built with n8n + OpenAI + Qdrant

<img src="https://img.shields.io/badge/n8n-Workflow%20Automation-orange?style=for-the-badge&logo=n8n" />
<img src="https://img.shields.io/badge/OpenAI-GPT--4o-green?style=for-the-badge&logo=openai" />
<img src="https://img.shields.io/badge/Qdrant-Vector%20Database-red?style=for-the-badge" />
<img src="https://img.shields.io/badge/RAG-Semantic%20Search-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/AI-Website%20Assistant-purple?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />

---

### 🧠 Turn Any Website into an AI Chatbot

This project allows users to chat with website content using **Retrieval-Augmented Generation (RAG)** and semantic search.

Instead of manually searching through web pages, users can now interact with website knowledge using AI-powered conversations. 🚀

</div>

---

# 🌟 Overview

This project is an advanced **Website RAG AI Assistant** built using:

- 🤖 OpenAI GPT Models
- 🧠 Semantic Search
- 🌐 Website Crawling
- 📚 Qdrant Vector Database
- ⚡ n8n Workflow Automation
- 💬 AI Agent Systems
- 🔍 Retrieval-Augmented Generation (RAG)

The system crawls websites, extracts content, converts it into vector embeddings, stores it inside Qdrant, and allows users to ask AI questions directly from website knowledge.

---

# 🔥 Features

# ✅ AI Website Knowledge Chatbot

- Crawl entire websites automatically
- Extract and clean website content
- Generate semantic embeddings
- Store knowledge inside Qdrant
- Ask questions directly from website data
- AI responds using retrieved website context

---

# ✅ Hallucination-Safe AI Responses

Unlike generic AI chatbots:

✔ AI answers ONLY from crawled website content  
✔ Prevents hallucinated answers  
✔ Uses retrieval-based semantic grounding  

---

# ✅ Fully Automated RAG Pipeline

This workflow automates:

```text
Website Crawling
        ↓
Content Extraction
        ↓
Chunk Processing
        ↓
OpenAI Embeddings
        ↓
Qdrant Vector Storage
        ↓
Semantic Search
        ↓
GPT Response Generation
```

---

# 📂 Repository Structure

```text
website-rag-chatbot/
│
├── Knowledge_ingestion.json
├── Website_Knowledge_Bot.json
├── Website Knowledge Chat UI.json
└── README.md
```

---

# ⚙️ Workflows Included

# 1️⃣ Knowledge Ingestion Workflow

## Purpose

Crawls websites and converts web content into searchable embeddings.

---

## Responsibilities

✅ Crawl website pages automatically  
✅ Extract clean content from pages  
✅ Process and split text into chunks  
✅ Generate OpenAI embeddings  
✅ Store vectors inside Qdrant  
✅ Build website knowledge collections  

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Firecrawl | Website Crawling |
| JavaScript | Data Processing |
| OpenAI Embeddings | Semantic Search |
| Qdrant | Vector Storage |
| n8n | Workflow Automation |

---

# 2️⃣ Website Knowledge Bot Workflow

## Purpose

Handles user questions and retrieves answers directly from website knowledge.

---

## Responsibilities

✅ Accept user questions  
✅ Generate semantic embeddings  
✅ Search Qdrant vector database  
✅ Retrieve relevant website chunks  
✅ Inject context into GPT  
✅ Generate grounded AI responses  
✅ Prevent hallucinated answers  

---

## Technologies Used

| Technology | Purpose |
|---|---|
| GPT-4o Mini | AI Response Generation |
| Semantic Search | Knowledge Retrieval |
| Qdrant | Vector Search |
| AI Agent | Intelligent Responses |
| Prompt Engineering | Hallucination Reduction |

---

# 3️⃣ Website Knowledge Chat UI Workflow

## Purpose

Provides a frontend/chat interface for interacting with website knowledge.

---

## Features

✅ Chat-style interface  
✅ User-friendly AI interaction  
✅ Real-time responses  
✅ Website-based AI assistant experience  

---

# 🧩 Complete System Architecture

```text
                ┌────────────────────┐
                │    Website URL     │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Website Crawling   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Content Extraction │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │   Text Chunking    │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ OpenAI Embeddings  │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Qdrant Vector DB   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │    User Question   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │  Semantic Search   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Relevant Web Data  │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ GPT-4o AI Response │
                └────────────────────┘
```

---

# 💡 Example Questions Users Can Ask

```text
"What services does this company provide?"
```

```text
"Summarize this website in simple terms"
```

```text
"What technologies are mentioned on the website?"
```

```text
"Explain the pricing information"
```

```text
"What products are available?"
```

---

# 🛠 Tech Stack

<div align="center">

| Technology | Usage |
|---|---|
| n8n | Workflow Automation |
| OpenAI API | AI Processing |
| GPT-4o Mini | AI Responses |
| OpenAI Embeddings | Semantic Search |
| Qdrant | Vector Database |
| Firecrawl | Website Crawling |
| JavaScript | Data Processing |
| RAG Architecture | Retrieval Pipeline |
| AI Agent Systems | Intelligent Responses |

</div>

---

# 📥 Setup Instructions

# Step 1 — Clone Repository

```bash
git clone https://github.com/yourusername/website-rag-chatbot.git
```

---

# Step 2 — Import Workflows into n8n

Import:

```text
Knowledge_ingestion.json
Website_Knowledge_Bot.json
Website Knowledge Chat UI.json
```

---

# Step 3 — Configure Credentials

Add your:

- OpenAI API Key
- Qdrant Credentials
- Firecrawl API Key

---

# Step 4 — Run Website Ingestion

Execute:

```text
Knowledge_ingestion.json
```

This workflow will:

✅ Crawl website pages  
✅ Extract website content  
✅ Generate embeddings  
✅ Store vectors inside Qdrant  

---

# Step 5 — Start Asking Questions

Execute:

```text
Website_Knowledge_Bot.json
```

Ask questions directly from website knowledge.

---

# Step 6 — Launch Chat UI

Execute:

```text
Website Knowledge Chat UI.json
```

Interact with the website knowledge assistant through a chatbot interface.

---

# 🔐 Security

## This repository does NOT contain:

❌ API Keys  
❌ Secrets  
❌ Tokens  
❌ Credentials  

Please configure your own credentials inside n8n before execution.

---

# 🎯 Key Learnings

This project helped me understand:

✅ Retrieval-Augmented Generation (RAG)  
✅ Website crawling and scraping  
✅ Semantic search systems  
✅ Vector databases and embeddings  
✅ AI workflow orchestration  
✅ Knowledge-grounded AI systems  
✅ Prompt engineering  
✅ Hallucination-safe AI design  
✅ Context-aware response generation  

---

# 🚀 Future Improvements

- Multi-website collections
- Website update synchronization
- OCR support
- Hybrid semantic + keyword search
- Multi-user support
- Authentication system
- Advanced memory handling
- Streaming AI responses
- Citation-based answers
- Real-time website indexing

---

# 🌍 Real-World Applications

## 🏢 Company Knowledge Assistant

Turn company websites into searchable AI assistants.

---

## 🛒 E-Commerce AI Assistant

Allow users to query products and pricing using AI.

---

## 📚 Documentation Chatbot

Chat with technical documentation instantly.

---

## 🎓 Educational Website Assistant

Learn from educational websites interactively.

---

# 📸 Project Vision

> AI should not only generate answers.
>
> It should retrieve trusted knowledge
> from real sources
> and provide context-aware responses.

This project demonstrates how websites can be transformed into intelligent AI assistants using RAG architecture, semantic search, and workflow automation.

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
🚀 Contribute improvements  
💬 Share feedback  

---

<div align="center">

# 🚀 Building Real-World AI Systems One Project at a Time

</div>

---

# 📜 License

MIT License
