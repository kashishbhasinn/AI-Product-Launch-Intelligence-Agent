# 🚀 AI Product Launch Intelligence Agent

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-green)
![License](https://img.shields.io/badge/License-MIT-black)

**A streamlined AI intelligence hub for Go-To-Market (GTM) & Product-Marketing teams**, designed to turn scattered public-web data into **concise, evidence-backed launch insights**.

Built with **Streamlit + Agno (GPT-4o) + Firecrawl**, this app helps you stay ahead of competitors, decode market sentiment, and track launch KPIs, all in one clean dashboard.

---

## 🧠 Overview

Three coordinated AI agents work together like your internal GTM strike team:

| Tab | What You Get |
|-----|---------------|
| **Competitor Analysis Agent** | Evidence-backed breakdowns of rivals’ latest launches - positioning, differentiators, pricing cues, and channel mix |
| **Market Sentiment Agent** | Consolidated social chatter & review themes, split by 🚀 *positive* and ⚠️ *negative* drivers |
| **Launch Metrics Agent** | Publicly available KPIs — adoption numbers, press coverage, and qualitative “buzz” indicators |

---

## 💡 Key Features

- 🔑 **Secure Key Input:** Add OpenAI & Firecrawl keys in the sidebar (`type="password"`)
- 🧩 **Coordinated Multi-Agent Workflow:**  
  - 🎯 *Product Launch Analyst* – GTM strategist  
  - 💬 *Market Sentiment Specialist* – consumer perception expert  
  - 📈 *Launch Metrics Specialist* – performance analyst  
- ⚡ **Quick Keyboard Shortcuts:** Trigger analyses with `J / K / L`  
- 📑 **Auto-Formatted Markdown Reports:**  
  - Summary bullets → Deep dive with tables & recommendations  
- 🔍 **Transparent Source Logs:** Every report includes crawled or searched URLs  

---

## 🛠️ Tech Stack

| Layer | Details |
|--------|----------|
| **Data** | Firecrawl async search + crawl API |
| **Agents** | Agno Team (GPT-4o) with FirecrawlTools |
| **UI** | Streamlit (wide-layout, tabbed interface) |
| **LLM** | OpenAI GPT-4o |

---

## ⚙️ Quick Start

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/product-launch-intelligence-agent.git
cd product-launch-intelligence-agent
