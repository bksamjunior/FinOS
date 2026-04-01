# FinOS
FinOS — A cloud-native personal finance system built with Python and PostgreSQL, designed to automate transaction tracking, enforce double-entry accounting, and provide scalable financial insights.

# FinOS – Financial Operating System

FinOS is a cloud-based personal finance system designed to replace spreadsheets and rigid budgeting apps with a scalable, automated, and developer-controlled architecture.

The project focuses on building a "Single Source of Truth" for financial data using a PostgreSQL database, Python-based data pipelines, and a lightweight analytics interface.

---

## 🚀 Motivation

Traditional personal finance tools fall into two categories:

- **Consumer apps (YNAB, Mint)**  
  → Easy to use but closed, inflexible, and opaque  

- **Spreadsheets (Excel, Google Sheets)**  
  → Flexible but fragile, error-prone, and not scalable  

FinOS aims to combine the strengths of both:
- Full control and transparency
- Automation and scalability
- Strong data integrity

---

## 🧠 Core Concepts

### 1. Double-Entry Accounting
Every transaction is recorded with at least two entries (debit and credit), ensuring:
- Accurate tracking of assets and liabilities
- Correct handling of transfers (e.g. credit card payments)
- Financial consistency (no “missing money”)

---

### 2. Single Source of Truth
All financial data is stored in a centralized PostgreSQL database:
- No duplicated logic
- No spreadsheet inconsistencies
- Reliable long-term analysis

---

### 3. Automated Data Pipeline
Transactions are:
1. Ingested (CSV or API)
2. Cleaned and normalized
3. Categorized (rules → ML)
4. Stored in structured tables

---

### 4. Layered Architecture

- **Storage** → PostgreSQL (financial core)
- **Backend** → FastAPI (logic + processing)
- **Frontend** → Streamlit (dashboard)
- **ML Layer** → scikit-learn / Gemini 

---

## ⚙️ MVP Features

- CSV transaction import
- PostgreSQL-based ledger
- Double-entry transaction system
- Basic categorization (rule-based)
- Financial dashboard (Streamlit)

---

## 🛠️ Tech Stack

- Python (FastAPI, Pandas)
- PostgreSQL (Supabase)
- Streamlit (UI)
- SQLAlchemy (ORM)
- GitHub Codespaces (development)

---

## ☁️ Cloud Architecture

FinOS is designed to run fully in the cloud:

- Code → GitHub  
- Dev Environment → GitHub Codespaces  
- Database → Supabase  
- Backend → Render  
- Frontend → Streamlit Cloud  

This allows development without relying on local machine performance.

---

## 🔐 Security Principles

- Environment variables for secrets (.env)
- Input validation at API level
- Planned: Row-Level Security (PostgreSQL)

---

## 📈 Future Direction

- Bank API integration (Plaid / Open Banking)
- Machine learning categorization
- Multi-user architecture
- Student-focused fintech features (gamification & social accountability)

---

## 📚 Learning Focus

This project is also a learning system covering:
- Backend engineering (FastAPI)
- Database design (PostgreSQL, normalization)
- Financial systems (double-entry accounting)
- Data pipelines and ETL
- Cloud deployment

---

## ⚠️ Status

🚧 Currently in MVP development phase  
Focus: Core data model + ingestion pipeline

---

## 👤 Author

Built as part of a long-term effort to design scalable systems combining software engineering, finance, and data intelligence.
