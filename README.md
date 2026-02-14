# 🗣️ Text to SQL Chatbot

Welcome to the **Text to SQL Chatbot** project!  
This project is designed to bridge the gap between **non-technical users** and **SQL databases** by enabling users to ask questions in **natural language** and automatically converting them into **SQL queries** to retrieve results from a database.

This solution helps organizations make data access easier, faster, and more inclusive—without requiring SQL knowledge.
<img width="1024" height="490" alt="image" src="https://github.com/user-attachments/assets/7031a8c4-722e-4d41-b646-851c8917c5c1" />

---

## 📚 Table of Contents
- [📖 Project Overview](#-project-overview)
- [🎯 Problem Statement](#-problem-statement)
- [🔧 Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🗼 Architecture](#-architecture)
- [🛠️ Installation](#️-installation)
- [🚀 Usage](#-usage)
- [📊 Evaluation](#-evaluation)
- [📝 Future Work](#-future-work)
- [📄 License](#-license)

---

## 📖 Project Overview

In many organizations, valuable data is stored in SQL databases, but non-technical team members often struggle to access it due to a lack of SQL knowledge. This project solves that problem by providing a **chatbot interface** that allows users to query databases using **plain English**.

The chatbot interprets natural language queries, converts them into valid SQL queries using a **Large Language Model (LLM)**, executes them on a database, and returns the results in an easy-to-understand format.

This project is applicable across multiple domains, including:
- Healthcare
- Retail
- Finance
- Education
- Business Analytics

---

## 🎯 Problem Statement

- Non-technical users cannot easily query SQL databases  
- Writing SQL requires technical expertise  
- Business users depend heavily on data teams for simple queries  

**Solution:**  
A chatbot that allows users to interact with databases using natural language instead of SQL.

---

## 🔧 Features

- **Natural Language to SQL Conversion**  
  Converts user questions into accurate SQL queries using NLP and LLMs

- **Database Interaction**  
  Connects seamlessly to MySQL databases to execute generated SQL queries

- **User-Friendly Responses**  
  Returns query results in readable, natural language format

- **End-to-End Workflow**  
  Covers data preparation, database querying, and response generation

- **Scalable Design**  
  Can be extended to support multiple databases and LLMs

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Database:** MySQL  
- **LLM:** Google Gemini / Other LLMs  
- **Data Source:** Excel / CSV files  
- **Libraries & Tools:**  
  - Pandas  
  - SQLAlchemy / MySQL Connector  
  - LangChain (or equivalent LLM framework)

---

## 🗼 Architecture

The system follows a modular architecture:

1. **Data Source**  
   Raw data stored in Excel or CSV files

2. **Database Layer**  
   Data is loaded into a MySQL database for structured querying

3. **LLM Processing Layer**  
   Converts natural language input into SQL queries

4. **Query Execution Layer**  
   Executes SQL queries against the database

5. **Output Parser**  
   Formats the results and presents them in a user-friendly way
