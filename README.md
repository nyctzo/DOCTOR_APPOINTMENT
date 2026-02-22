# DOCTOR_APPOINTMENT

# 🤖 AI-Powered Telegram Appointment Bot (n8n Automation)

An AI-driven Telegram chatbot built using **n8n** that automates appointment scheduling with intelligent function calling and calendar integration.

This project demonstrates workflow automation, AI agent integration, tool usage, and webhook-based event handling.

---

## 🚀 Features

- 📩 Telegram Bot Integration
- 🧠 AI Agent with Function Calling
- 📅 Google Calendar Integration
- ⏰ Date & Time Handling
- 🔄 Conflict Detection for Appointments
- 🛠 Modular n8n Workflow Architecture
- 🐳 Docker-Based Deployment
- 🌐 Webhook-based Real-time Triggering

---

## 🏗 System Architecture


The AI Agent:
- Understands user intent
- Checks appointment availability
- Prevents double booking
- Schedules events in Google Calendar
- Confirms booking details clearly

---

## 🛠 Tech Stack

- **n8n** – Workflow automation platform
- **Docker** – Containerized deployment
- **Telegram Bot API** – Messaging interface
- **OpenAI / OpenRouter / Ollama** – AI Model (function calling capable)
- **Google Calendar API** – Appointment scheduling
- **ngrok (development only)** – Secure public webhook tunneling

---

## 📦 Project Structure


---

## ⚙️ Setup Instructions

### 1️⃣ Install Docker

Download Docker Desktop and install.

---

### 2️⃣ Run n8n with Docker

```bash
docker run -it --rm -p 5678:5678 n8nio/n8n
