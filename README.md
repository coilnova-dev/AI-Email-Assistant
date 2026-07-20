# 🤖 AI Email Assistant

An AI-powered email automation workflow built with **n8n** and **OpenAI**.

## 📌 Overview

This workflow automatically processes incoming emails using AI.

When a new email arrives, the assistant analyzes its content, classifies the request, and prepares an intelligent response, reducing manual work and improving response times.

## ✨ Features

- 📩 Detect new incoming emails
- 🤖 AI email analysis
- 🏷️ Automatic email classification
- ✍️ Generate draft replies
- 📧 Notify the business
- ⚡ Built with n8n automation

## 🛠️ Tech Stack

- n8n
- OpenAI API
- Gmail API
- JavaScript

---

## 🔄 Workflow

```text
Gmail Trigger
      ↓
OpenAI
      ↓
Classify Email
      ↓
IF
 ├── Quote Request
 │       ↓
 │  Generate Draft
 │       ↓
 │  Notify Business
 │
 └── Other
         ↓
     End
```

## 📂 Project Goal

Demonstrate how AI can automate customer email handling for small businesses, reducing response time and manual work.