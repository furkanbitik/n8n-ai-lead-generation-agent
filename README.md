# 🕵️‍♂️ AI Lead Generation Agent (Google Maps & Serper)

![Workflow Screenshot](image_7581da.png)

## 🚀 Project Overview
This represents an experimental **AI Agent** built with **n8n** that automates the B2B lead generation process.

Instead of manually searching for potential clients on Google Maps or LinkedIn, this agent:
1.  Takes a niche/industry request via Chat (e.g., "Find coffee shops in London").
2.  Uses **Serper.dev** (Google Search API) to scrape real-time business data.
3.  Processes the data using **OpenAI (GPT-4o/GPT-3.5)**.
4.  Automatically saves verified leads into **Google Sheets**.

## 🛠️ Tech Stack
* **Orchestration:** [n8n](https://n8n.io/)
* **AI Brain:** OpenAI GPT-4o / GPT-3.5 Turbo
* **Search Tool:** Serper.dev (Google Search & Maps API)
* **Database:** Google Sheets
* **Memory:** n8n Simple Memory (Context Awareness)

## 🚧 Status & Roadmap
This project is currently a **Proof of Concept (PoC)** running locally.
I am sharing this open-source to gather feedback and ideas for further development.

**Current Ideas for V2:**
- [ ] Add email enrichment (finding contact emails automatically).
- [ ] Integrate CRM (HubSpot/Salesforce) instead of Google Sheets.
- [ ] Implement a WhatsApp notification triggers.

## 📦 How to Use
1.  Import `lead-gen-workflow.json` into your n8n instance.
2.  Set up your **OpenAI** and **Serper.dev** API keys.
3.  Connect your **Google Sheets** account.
4.  Start chatting with the agent!

---
*Open to contributions and suggestions! Feel free to open an issue or PR.*
