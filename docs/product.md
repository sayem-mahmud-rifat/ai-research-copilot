# AI Research Copilot

## Vision

AI Research Copilot is an AI-powered assistant that helps researchers read, organize, search, compare, and understand scientific literature from a personal collection of research papers.

---

## Target Users

* Undergraduate researchers
* Master's students
* PhD students
* Professors

---

## Problem

Researchers spend significant time searching through PDFs, taking notes, comparing methods, and locating important information across multiple papers.

Current LLMs answer questions but do not provide a persistent, searchable knowledge base for a personal literature collection.

---

## Solution

Allow users to upload research papers and interact with them using AI.

The application will extract text, index papers, generate embeddings, and answer questions with citations from the uploaded documents.

---

## Version 1 Features

* Upload PDF
* Extract text
* Store documents
* Semantic search
* Ask questions about uploaded papers
* Display cited source passages

---

## Future Features

* Literature review generation
* Compare two papers
* Timeline of research
* Citation graph
* Export notes
* Multi-user support

---

## Technology

Frontend:

* Streamlit

Backend:

* FastAPI

AI:

* Gemini API

Database:

* ChromaDB

Language:

* Python

Deployment:

* Streamlit Community Cloud

---

## Success Criteria

Within five minutes, a new user should be able to:

1. Upload a paper.
2. Ask a question.
3. Receive an answer with citations.

