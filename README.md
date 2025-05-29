<<<<<<< HEAD
# Multi-Agent Retrieval-Augmented Generation (RAG) API

This project implements a simple Retrieval-Augmented Generation (RAG) backend API using FastAPI and PostgreSQL. It exposes endpoints that accept natural language questions, generate corresponding SQL queries based on a fixed schema, execute them asynchronously against a PostgreSQL database, and return results in JSON format.

---

## Features

- Async connection pooling to PostgreSQL via `asyncpg`.
- Placeholder agent logic to map questions to SQL queries on `customers` and `orders` tables.
- API endpoints:
  - `POST /ask`: Accepts a JSON question, returns SQL results and a synthesized answer.
  - `GET /test`: Simple test query to fetch rows from the `customers` table.
- Designed as a backend API service (no built-in frontend UI).

---

## Requirements

- Python 3.8+
- PostgreSQL database with schema and sample data loaded (see **Database Setup**)
- Required Python packages (see `requirements.txt`)

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Aryan1334/multiagent-rag.git
cd multiagent-rag/multiagent-rag
=======
# Multi-Agent RAG System (Updated with Web UI)

This project is an updated version of the Multi-Agent Retrieval-Augmented Generation system for natural language querying of a PostgreSQL database. 

## New Features

- Web-based UI with a simple form to ask questions
- Interactive query results displayed on the same page
- Backend built with FastAPI, using Jinja2 templates for rendering
- PostgreSQL connection pooling with asyncpg
- Basic natural language to SQL query generation (demo-level)

## Running the Project

1. Create and activate a Python virtual environment
2. Install dependencies: `pip install -r requirements.txt`
3. Start the FastAPI server: `uvicorn main:app --reload`
4. Open your browser at `http://localhost:8000` and start querying!

## Example Queries

- "Show me customers"
- "Show recent orders"

---

(Then keep your original README content for the rest)

>>>>>>> e4e0a24 (Update main.py and README)
