# HireFlow AI 🚀

### Agentic Recruitment & Onboarding Automation Platform

HireFlow AI is an AI-powered multi-agent recruitment platform that automates the complete hiring lifecycle—from job creation and candidate sourcing to assessments, interviews, hiring decisions, and onboarding.

The platform combines Agentic AI, RAG (Retrieval-Augmented Generation), workflow orchestration, and human-in-the-loop approvals to help organizations reduce manual effort, improve hiring efficiency, and scale recruitment operations.

---

## 🎯 Problem Statement

Organizations spend significant time and resources on repetitive recruitment tasks such as:

* Creating Job Descriptions
* Campus & Candidate Outreach
* Resume Screening
* Assessment Creation & Evaluation
* Interview Scheduling
* Candidate Evaluation
* Offer Management
* Onboarding

These processes are often manual, time-consuming, and prone to inconsistencies, resulting in delayed hiring and increased HR workload.

---

## 💡 Solution

HireFlow AI automates the end-to-end recruitment process using specialized AI agents orchestrated through workflow automation.

The system can:

* Generate Job Descriptions
* Discover & Engage Campuses
* Parse and Evaluate Resumes
* Generate Assessments
* Conduct AI-Assisted Interviews
* Schedule Interviews
* Recommend Hiring Decisions
* Generate Offer Letters
* Manage Onboarding Workflows

Human approval checkpoints ensure transparency, governance, and control throughout the process.

---

## ✨ Key Features

* AI Job Description Generator
* Automated Campus & Candidate Outreach
* Resume Parsing & Candidate Ranking
* AI-Powered Candidate Evaluation
* RAG-Based Interview Question Generation
* AI-Generated MCQ, Coding & Written Assessments
* Automated Test Evaluation
* Interview Scheduling & Coordination
* AI Interview Assistant
* Human-in-the-Loop Approval Workflow
* Candidate Recommendation Engine
* Offer Letter Generation
* Onboarding Automation
* Recruitment Analytics Dashboard
* Audit Logs & Explainable AI Decisions

---

## 🏗️ Architecture

The platform is built around a LangGraph-powered Agent Orchestrator that coordinates multiple AI agents:

* Hiring Intelligence Agent
* JD Generation Agent
* Campus Discovery Agent
* Outreach Agent
* Resume Intelligence Agent
* Assessment Agent
* AI Interview Agent
* Decision Agent
* Offer Agent
* Onboarding Agent

---

## 🛠️ Tech Stack

### Frontend

* React
* Tailwind CSS

### Backend

* FastAPI
* Python
* SQLAlchemy

### AI & Agent Framework

* LangGraph
* LangChain
* Nexus API

### Models (via Nexus API)

* Gemini 2.5 Flash
* GPT-4.1 Nano
* Whisper-1
* Gemini 2.5 Flash TTS

### Database & RAG

* SQLite / PostgreSQL
* ChromaDB
* Sentence Transformers

### Integrations

* Gmail API
* Google Calendar API
* Google Meet API
* Twilio

---

## 🔑 Nexus API

This project uses **Nexus API** as the unified AI gateway.

Environment Variables:

```env
NEXUS_API_KEY=your_api_key
NEXUS_BASE_URL=https://apidev.navigatelabsai.com

TEXT_MODEL=gemini-2.5-flash
FALLBACK_MODEL=gpt-4.1-nano

VOICE_MODEL=gemini-2.5-flash-tts
TRANSCRIPTION_MODEL=whisper-1
```

---

## 🔄 High-Level Workflow

Hiring Request
→ JD Generation
→ Campus Discovery
→ Outreach
→ Student Registration
→ Resume Parsing
→ Candidate Scoring
→ Assessment Generation
→ Assessment Evaluation
→ Interview Scheduling
→ AI/Human Interviews
→ Hiring Decision
→ Offer Generation
→ Onboarding

---

## 🎯 Vision

To build a fully autonomous AI Recruitment Operating System capable of managing the complete hiring lifecycle through collaborative AI agents while maintaining transparency, explainability, compliance, and human oversight.
