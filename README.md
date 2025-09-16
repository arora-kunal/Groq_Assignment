# AI/ML Developer Internship Assignment – Conversation Management & Classification

## Overview
This project implements two tasks using the **Groq API (OpenAI SDK compatible)**:

1. **Conversation Management with Summarization**
2. **JSON Schema Classification & Information Extraction**

The objective is to demonstrate handling long conversational history, periodic summarization, truncation strategies, and structured data extraction from user chats.

---

## Features

### Task 1: Conversation Management & Summarization
- Maintains a **running history** of user–assistant messages.
- Supports **truncation by**:
  - Number of turns
  - Token count (approximate)
  - Word count
  - Character count
- **Summarization logic**:
  - Summarizes history after every *k* user turns.
  - Replaces older history with a summary + last few turns.
- Demonstrations:
  - **Demo 1:** Shows truncation (turns, tokens).
  - **Demo 2:** Shows summarization after every 3rd turn.

### Task 2: JSON Schema Classification & Extraction
- Defines a **JSON schema** to extract user details:
  - Name
  - Email
  - Phone
  - Location
  - Age
- Uses **OpenAI Function Calling (Groq API)** for structured outputs.
- Validates outputs against the schema using `jsonschema`.

---
