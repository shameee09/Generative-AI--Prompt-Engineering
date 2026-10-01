# Generative AI – Prompt Engineering & LLM Applications

A hands-on Generative AI learning repository covering **Prompt Engineering, LLM APIs, Chatbots, Prompt Chaining, Moderation, Input Classification, Output Evaluation, and End-to-End AI System Development** using Python.

The repository contains practical experiments and implementations built while learning how Large Language Models can be integrated into real-world AI applications.

---

## 🚀 Overview

Generative AI enables AI systems to generate new content such as text, code, images, audio, and more.

This repository focuses mainly on **text-based Generative AI applications**, with an emphasis on:

- Prompt Engineering
- LLM API Integration
- Chatbot Development
- Structured Prompting
- Prompt Chaining
- Input Classification
- Content Moderation
- Product Information Retrieval
- Response Evaluation
- End-to-End LLM Systems

---

## 📚 Topics Covered

### 1. Prompt Engineering

Hands-on exploration of different prompting techniques:

- Role Prompting
- Persona Prompting
- XML Prompting
- JSON Prompting
- Few-Shot Prompting
- ReAct Prompting
- Tree of Thoughts
- Skeleton of Thoughts
- Prompt Chaining
- Dynamic Prompt Templates

The goal is to understand how prompt structure, context, examples, and constraints influence LLM responses.

---

### 2. Python-Based Prompting

Implemented prompts programmatically using Python to:

- Generate dynamic prompts
- Accept user input
- Send prompts to LLMs
- Process model responses
- Build reusable prompt templates

---

### 3. LLM API Integration

Worked with LLM APIs from Python applications.

Technologies explored:

- Gemini API
- OpenAI API concepts
- Python
- `google-genai`
- `python-dotenv`

Example workflow:

User Input
    ↓
Python Application
    ↓
LLM API
    ↓
Model Processing
    ↓
Generated Response

🤖 Chatbot Development

Built different chatbot implementations to understand how LLM-powered applications work.

Simple Chatbot

A basic chatbot that accepts user input and generates responses using an LLM.

Customized Chatbot

Implemented a chatbot with customized instructions and behavior using system prompts.

Service Assistant

Developed a more advanced customer-service chatbot using:

Gemini API
Prompt Engineering
Conversation Context
Product Information
Input Moderation
Output Moderation
Product/Category Classification
Response Evaluation
Panel UI

**Key Components**
Input Moderation

Checks whether the user's input should be processed before sending it to the main application.

Input Classification

Identifies relevant product categories and products from the user's question.

Product Information Retrieval

Retrieves relevant product information that can be provided as context to the LLM.

Prompt Chaining

Breaks the overall task into multiple LLM-powered steps instead of relying on a single prompt.

Response Generation

Gemini generates a customer-service response using:

System instructions
User question
Relevant product information
Conversation context
Output Moderation

The generated response is checked before being returned to the user.

Response Evaluation

A separate evaluation step checks whether the generated response sufficiently answers the customer's question.

