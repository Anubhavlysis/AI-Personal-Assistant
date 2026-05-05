## 🤖 AI Personal Assistant (n8n + Streamlit + LLM)
### 📌 Problem Statement

Managing daily activities like tasks, emails, expenses, and notes across multiple tools is inefficient and time-consuming. This project builds a unified AI-powered assistant that automates these workflows through a single conversational interface.

---

### 📁 Project Overview

This project integrates Streamlit + n8n + AI Agent to create an intelligent assistant capable of executing real-world operations:

User interacts via a chat-based UI (Streamlit)
Requests are sent to an n8n webhook
AI Agent processes intent using LLM
Tasks are routed to appropriate tools (Gmail, Calendar, Notes, etc.)
Response is returned back to the user

⚙️ Key Functionalities
✅ Task Management (Create, Update, Delete, Retrieve)
💰 Expense Tracking & Budget Logging
📧 Email Automation (Read, Send, Summarize)
📅 Calendar Event Management
📝 Notes Creation & Updates
🔎 Google Search Integration
🤖 Conversational AI Interface

--- 

## 📸 Sample Screenshots

### Streamlit Chat Interface

--- 

## 🔍 Key Insights (Technical)
* Demonstrates multi-tool AI orchestration using workflows
* Uses LLM-based intent recognition to dynamically trigger actions
* Shows integration of real-world APIs (Google services, Sheets, etc.)
* Implements stateful chat interaction using session memory

--- 

## 🧠 Business Impact
* Reduces manual effort by automating repetitive workflows
* Centralizes multiple tools into a single interface
* Improves productivity using AI-driven automation
* Demonstrates scalable architecture for real-world assistant systems

---

## 🏗️ System Architecture

User → Streamlit UI → n8n Webhook → AI Agent → Tool Routing → Response → UI

### n8n-Workflow

--- 

## 🛠 Tools & Technologies
Python (Streamlit)
n8n (Workflow Automation)
LLM (Google Gemini / Groq / Ollama)
Google Services (Gmail, Calendar, Sheets)

---
