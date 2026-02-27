
# 🏗 Structured LLM Architecture (Groq + Python)

A modular Python-based LLM pipeline built using clean software engineering principles.

This project demonstrates how real-world AI systems are structured into layers instead of being written as a single script.

---

## 🎯 Objective

Design a structured LLM workflow:

```
User Input → Prompt Layer → LLM Layer → Post-Processing → Output
```

The goal is to build a scalable, maintainable, and production-style GenAI architecture.

---

## 🚀 Features

* 🧩 Modular AI pipeline design
* 🧠 Separation of concerns
* 📝 Prompt abstraction layer
* 🤖 Model invocation layer (Groq via LiteLLM)
* 🧹 Post-processing layer
* 🏗 Production-style architecture

---

## 🛠️ Tech Stack

* Python
* Groq API
* LiteLLM
* python-dotenv

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/PratheekshaSNaik/Structured_LLM_Architecture.git
cd Structured_LLM_Architecture
```

### 2. Install dependencies

Since no virtual environment is used, install globally:

```bash
python -m pip install -r requirements.txt
```

Or manually:

```bash
python -m pip install groq litellm python-dotenv
```

---

## 🔐 Setup Environment Variables

Create a `.env` file in the root directory:

```env
GROQ_API_KEY=your_key_here
MODEL_NAME=groq/llama-3.1-8b-instant
```

---

## 🚫 Important (Security)

Do NOT upload your `.env` file to GitHub.

Ensure `.env` is added to `.gitignore`:

```
.env
```

---

## ▶️ Run the Project

```bash
python pipeline.py
```

---

## 🏗 Architecture Overview

1️⃣ **Input Layer**
Handles user interaction and input validation.

2️⃣ **Prompt Layer**
Builds structured and reusable prompts.

3️⃣ **LLM Layer**
Invokes Groq models via LiteLLM.

4️⃣ **Post-Processing Layer**
Formats and cleans the model output.

5️⃣ **Pipeline Layer**
Orchestrates the complete workflow.

---

## 📁 Project Structure

```
Structured_LLM_Architecture/
│── input_layer.py
│── prompt_layer.py
│── llm_layer.py
│── post_processing.py
│── pipeline.py
│── requirements.txt
│── .env.example
│── README.md
```

---

## 🎓 Learning Outcomes

After completing this project, you will:

* Understand modular AI workflow design
* Separate prompt logic from model logic
* Build scalable LLM applications
* Apply production-level architectural thinking

---

## 🚀 Why This Matters

Real-world AI systems are **not single scripts**.

They are modular pipelines with:

* Input validation
* Prompt engineering
* Model abstraction
* Output processing
* Scalable orchestration

This project builds that engineering mindset.

---

## 🙌 Acknowledgements

* Groq for fast LLM inference
* LiteLLM for model abstraction
* Open-source community
---
