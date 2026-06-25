# 📚 Smart Study Generator Agent

> **An AI-powered Smart Study Assistant built using LangFlow, IBM watsonx.ai, IBM Granite Models, and Retrieval-Augmented Generation (RAG).**

![Project Banner](assets/banner.png)

---

# 📖 Overview

The **Smart Study Generator Agent** is an AI-powered educational assistant that helps students transform scattered study materials into structured, personalized learning resources.

Students can upload lecture notes, PDFs, textbooks, or research papers, and the system automatically generates:

* 📄 Smart Summaries
* 📝 Revision Notes
* 🧠 Flashcards
* ❓ MCQs & Practice Quizzes
* 📅 Personalized Study Plans
* 💬 AI-powered Question Answering

The project uses **Retrieval-Augmented Generation (RAG)** with **IBM Granite Foundation Models** to provide accurate, context-aware responses based on uploaded documents.

---

# 🎯 Problem Statement

### Problem Statement No. 13 – Smart Study Generator Agent

Students today face an overwhelming amount of information spread across lecture notes, textbooks, research papers, YouTube tutorials, and online resources.

Traditional study tools only provide static notes or flashcards and fail to adapt to individual learning needs.

The Smart Study Generator Agent addresses these challenges by providing an intelligent AI-powered study companion capable of understanding uploaded documents, retrieving relevant information, and generating personalized study content.

---

# 🚀 Features

✅ Upload PDF, DOCX, TXT study materials

✅ AI-powered document understanding

✅ Intelligent document summarization

✅ Flashcard generation

✅ MCQ & Quiz generation

✅ Personalized study plan generation

✅ Question Answering using uploaded notes

✅ Retrieval-Augmented Generation (RAG)

✅ Context-aware responses

✅ Interactive AI Study Assistant

---

# 🛠️ Technology Stack

| Technology                           | Purpose                      |
| ------------------------------------ | ---------------------------- |
| LangFlow                             | Visual AI Workflow Builder   |
| IBM watsonx.ai                       | AI Foundation Model Platform |
| IBM Granite 4.0 H Small              | Large Language Model         |
| IBM Granite Embedding Model          | Semantic Embeddings          |
| Retrieval-Augmented Generation (RAG) | Context-aware Retrieval      |
| Chroma Vector Database               | Vector Storage               |
| Knowledge Base                       | Document Retrieval           |
| Python                               | Backend Runtime              |

---

# 🏗️ System Architecture

```text
                             Student
                                │
                Upload PDF / Ask Questions
                                │
                                ▼
                         LangFlow Workflow
                                │
                                ▼
                           Read File
                                │
                                ▼
                           Split Text
                                │
                                ▼
                    IBM Granite Embedding Model
                                │
                                ▼
                     Chroma Vector Database
                     (Knowledge Base / RAG)
                                │
                    Retrieve Relevant Chunks
                                │
                                ▼
                      IBM watsonx.ai
                    IBM Granite Foundation Model
                                │
                                ▼
                  Smart Study Generator Agent
                                │
        ┌─────────────┬─────────────┬─────────────┐
        │             │             │             │
     Summary     Flashcards      MCQs      Study Plan
        │
        ▼
                     Chat Output
```

---

# 🔄 Workflow

1. Student uploads study material.
2. Read File extracts document content.
3. Text is divided into smaller chunks.
4. IBM Granite Embedding Model generates vector embeddings.
5. Embeddings are stored in the Chroma Knowledge Base.
6. RAG retrieves the most relevant content.
7. IBM Granite Foundation Model generates intelligent responses.
8. Smart Study Agent produces personalized study resources.

---

# 🤖 Role of Agentic AI

Unlike traditional chatbots, the Smart Study Generator functions as an intelligent **Agentic AI** system.

The AI agent autonomously:

* Understands uploaded documents
* Retrieves relevant knowledge using RAG
* Generates summaries
* Creates revision notes
* Builds flashcards
* Generates quizzes
* Creates personalized study plans
* Answers contextual questions

The agent continuously adapts to the student's learning needs, making learning more interactive and efficient.

---

# 💡 Novelty & Uniqueness

* Agentic AI-powered learning assistant
* Retrieval-Augmented Generation (RAG)
* Context-aware responses using uploaded documents
* Automated study resource generation
* Personalized learning experience
* Intelligent exam preparation
* Built using IBM Granite Foundation Models
* Visual AI workflow using LangFlow

---


---

# 📸 Screenshots

### LangFlow Workflow

```
screenshots/workflow.png
```

### Chat Output

```
screenshots/output.png
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Smart-Study-Generator-Agent.git
```

Move into the project

```bash
cd Smart-Study-Generator-Agent
```

Install LangFlow

```bash
pip install langflow
```

Start LangFlow

```bash
langflow run
```

Open

```
http://localhost:7860
```

Import the Smart Study Generator Flow.

Configure:

* IBM watsonx.ai API Key
* IBM Project ID
* IBM Endpoint

---

# 🧪 Sample Prompts

* Summarize the uploaded notes.
* Explain Artificial Intelligence.
* Generate 10 MCQs.
* Create revision flashcards.
* List important exam topics.
* Create a 7-day study plan.
* Explain Machine Learning.
* What are the advantages of AI?

---

# 📈 Future Enhancements

* 🎤 Voice-based interaction
* 🖼️ OCR for handwritten notes
* 🌐 Multi-language support
* 📊 Student progress dashboard
* 📈 Performance prediction
* 🧠 Concept map generation
* 📱 Mobile application
* ☁️ Cloud deployment

---

# 👨‍💻 Author

**Prit Vyas**

Assistant Professor | MERN Stack Developer | AI Enthusiast

---

# 🙏 Acknowledgements

* IBM SkillsBuild
* IBM watsonx.ai
* IBM Granite Foundation Models
* LangFlow Community
* Chroma Database

---

# 📄 License

This project is developed for educational and research purposes as part of the **IBM SkillsBuild University Engagement Program**.

---

⭐ If you found this project useful, don't forget to **Star ⭐ the repository**.
