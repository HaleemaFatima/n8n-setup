# 🔥 My Complete n8n Setup Journey

> A fully documented, beginner friendly guide to building a real AI automation system with n8n 

[![Live Site](https://img.shields.io/badge/Live%20Site-View%20Now-ff6b35?style=for-the-badge&logo=github)](https://YOUR-USERNAME.github.io/n8n-journey)
[![Made with n8n](https://img.shields.io/badge/Built%20with-n8n-7c3aed?style=for-the-badge)](https://n8n.io)
[![AI Powered](https://img.shields.io/badge/AI-Groq%20%2F%20LLaMA-06b6d4?style=for-the-badge)](https://groq.com)

---

## 📖 What This Is

This repo contains a **single-file HTML website** documenting my complete n8n automation setup journey — from zero to a fully working AI-powered workflow that:

- ⏰ Triggers on a daily schedule
- 📅 Checks Google Calendar for conflicts
- 🌤️ Fetches live Karachi weather via OpenWeatherMap
- 📊 Reads running routes from a Google Sheets database
- 🤖 Uses a Groq-powered LLaMA AI agent to make a decision
- 📧 Sends a personalized Gmail recommendation automatically

Everything is explained in beginner-friendly language with every error documented and every fix recorded.

---

## 🗂️ Repo Structure

```
n8n-journey/
├── index.html        ← The entire website (single file, no dependencies)
└── README.md         ← This file
```

No build tools. No npm. No frameworks. Just one HTML file — open it in a browser or deploy it anywhere.

---

## 🚀 Live on GitHub Pages

 **site is live** at:
   ```
   https://haleemafatima.github.io/n8n-setup/
   ```
   
---

## ⚙️ What's Covered in the Site

| Section | Description |
|---|---|
| Core Concepts | n8n, APIs, OAuth, Credentials, Nodes, AI Agents |
| Final Workflow | Step-by-step breakdown of the Karachi Running Assistant |
| Tools Used | Schedule Trigger, Groq, Simple Memory, Calendar, Weather, Sheets, Gmail |
| Commands | n8n startup commands, Google Cloud setup |
| Errors & Fixes | 10 real errors with root causes and solutions |
| Learnings | Technical and professional takeaways |
| Business Uses | Real client automation use cases |
| Growth Summary | Before vs. after |

---

## 🛠️ Tech Stack

| Tool | Role |
|---|---|
| **n8n** | Automation platform |
| **Groq (LLaMA 3.1)** | AI reasoning model |
| **Google Calendar API** | Schedule checking |
| **OpenWeatherMap API** | Live weather data |
| **Google Sheets API** | Routes database |
| **Gmail API** | Sending recommendations |
| **OAuth 2.0** | Secure Google authentication |
| **HTML / CSS / JS** | The website itself (zero dependencies) |

---

## 📌 Key Lessons Learned

- **Google APIs are separate switches** — each one must be enabled individually
- **OAuth needs exact URLs** — one wrong character breaks authentication
- **AI tool names must match exactly** — prompt names and node names must be identical
- **Real projects require debugging** — errors are normal, not failures

---

## 📁 Files to Keep Safe

If you're replicating this setup, make sure to back up:

- `workflow.json` — exported from n8n
- Your AI agent system prompt
- Groq API key
- OpenWeatherMap API key
- Google Cloud Client ID & Client Secret

---

## 🙌 Closing

> *"Today I didn't just study automation. I built automation."* 🔥

Built in Karachi, Pakistan.
