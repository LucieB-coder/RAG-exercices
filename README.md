# RAG-exercices

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![LangChain](https://img.shields.io/badge/langchain-🚀-purple)](https://www.langchain.com/)
[![Status: Learning Project](https://img.shields.io/badge/status-in--progress-yellow)]()

## 📘 Overview

This repository is part of a professional training journey to gain hands-on experience building **Retrieval-Augmented Generation (RAG)** systems using **LangChain**, **FAISS**, and **other modern tools** (e.g. Graph/Smith).

The goal is to progressively explore more advanced and performant RAG pipelines, each building upon the previous.


### 🧱 What is RAG?

**Retrieval-Augmented Generation (RAG)** is an AI architecture that enhances a language model’s outputs by retrieving relevant external documents at inference time, instead of relying solely on pre-trained knowledge.


## 📂 Project Structure (More Coming Soon)

```plaintext
📁 rag-experiments/
├── 5_levels_of_RAG.ipynb # Step-by-step RAG pipeline exploration
├── README.md # This file
└── ... # Upcoming notebooks, tools, and utilities
```

## Rapid explanation of each notebook

### 🔹 `5_levels_of_RAG.ipynb`

It showcases **5 levels** of RAG sophistication, from naive retrieval to complex query decomposition.

## 🔍 RAG Levels in This Project

| Level | Description |
|-------|-------------|
| **1. Naive RAG** | Simple document retrieval + answer generation. |
| **2. Multi-Query RAG** | Reformulates queries to retrieve richer context. |
| **3. FAISS-based RAG** | Persistent, configurable vector index for scalable search. |
| **4. RRF (Reciprocal Rank Fusion)** | Combines multiple ranked retrievals for better precision. |
| **5. Query/Response Decomposition** | Breaks down complex questions into subqueries and merges answers. |

Each level is **documented in the notebook** (in french) with explanations and sample outputs.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Contributions

This repo is currently part of an individual learning journey, but ideas, suggestions, or collaboration proposals are welcome!
