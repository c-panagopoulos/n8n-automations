# ⚙️ n8n Learning & Productivity Automations

A collection of real-world **n8n workflows** I use to support my web development learning, organize information, and automate decision-making around daily routines.  
All workflows are **self-hosted** and built as part of a broader personal productivity and learning system.

![n8n](https://img.shields.io/badge/n8n-automations-orange)
![OpenAI](https://img.shields.io/badge/OpenAI-integrated-blue)
![Self-Hosted](https://img.shields.io/badge/Self%20Hosted-Linux-green)

---

## 🧩 Workflows

### 📝 Learning Notes Automation
Automatically transforms handwritten notes into structured digital cards.

This workflow takes scanned handwritten notes, extracts their content using OpenAI Vision, and converts them into clean, tagged cards inside a digital board. It removes friction from note organization and makes revision significantly easier.

- **Typical time saved:** ~3 hours/week  
- **Tech:** n8n, OpenAI Vision API, Nextcloud Deck  
- **Concepts:** OCR, AI-assisted structuring, workflow orchestration  

➡️ [View Workflow](workflows/learning-notes-automation)

---

### 🤖 AI Daily Scheduler
AI-powered daily routine planning system that generates a realistic, non-overlapping schedule based on sleep quality and existing calendar events.

This workflow analyzes the user's calendar (ICS), sleep score, and daily constraints, then uses OpenAI to generate a structured study-first routine.  
The output is validated, normalized to ICS format, and automatically written back to the calendar.

Key design goals:
- Prioritize deep study sessions over entertainment
- Respect work buffers and fixed calendar events
- Avoid overlapping or unrealistic schedules
- Produce human-like, balanced daily plans

- **Tech:** n8n, OpenAI, ICS / CalDAV, Nextcloud Calendar  
- **Concepts:** AI decision systems, rule-based validation, time normalization, automation design  

➡️ [View Workflow](workflows/ai-daily-scheduler)

---

## 💻 My Setup

- Self-hosted on Linux (Intel N100 mini PC)  
- Docker-based services  
- n8n for automation orchestration  
- Nextcloud for file storage and calendar integration  

---

## ⭐ Why This Repo Exists
As a self-taught web developer balancing full-time work and structured learning, automation helps reduce cognitive load and eliminate repetitive tasks.

This repository serves two purposes:
1. Document workflows that genuinely improved my learning and productivity
2. Showcase real, practical automation projects built with modern tools

These are not demo workflows — they are systems I actively use and refine.

---

## 🗺️ Roadmap
- [x] Learning Notes Automation  
- [x] AI Daily Scheduler  
- [ ] Automatic Deck tag assignment  
- [ ] Additional learning-focused automations  

---

**Author:** Charalampos Panagopoulos  
🌐 [Website](https://c-panagopoulos.github.io/Personal-Website/)
