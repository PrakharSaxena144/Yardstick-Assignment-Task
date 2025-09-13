# 🚀 Yardstick Assignment – Groq API (Colab Notebook)

**Author:** Prakhar Saxena  
**Repo:** [Yardstick-Assignment-Task](https://github.com/PrakharSaxena144/Yardstick-Assignment-Task)  

This repository contains my submission for the Yardstick selection assignment.  
The work is implemented in **Google Colab** using the **Groq API (OpenAI SDK compatible)** without any frameworks.  

---

## 📑 Contents
- `YardstickAssign.ipynb` → Main notebook with **Task 1** & **Task 2**.

---

## 📝 Task 1: Managing Conversation History with Summarization
- Implemented a **conversation tracker** that:
  - Stores user–assistant messages.
  - Supports **truncation** by last N messages or length.
  - Performs **periodic summarization** (after every k-th run).
- Demonstrations included:
  - Multiple conversation samples.
  - Summarization outputs after set intervals.

---

## 📝 Task 2: JSON Schema Classification & Information Extraction
- Designed a **JSON schema** to extract:
  - `name`, `email`, `phone`, `location`, `age`.
- Used **OpenAI-style function calling** on Groq API for structured JSON output.
- Validated extracted outputs using `jsonschema`.
- Demonstrated with **3 sample chats**.

---

## ⚙️ Requirements
- Python 3.10+
- Google Colab (preferred)
- Libraries:
  ```bash
  pip install openai jsonschema
