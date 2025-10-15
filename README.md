# 🚀 AI Product Launch Intelligence Agent

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-green)

**A streamlined AI intelligence hub for Go-To-Market (GTM) & Product-Marketing teams** — designed to turn scattered public-web data into **concise, evidence-backed launch insights**.

Built with **Streamlit + Agno (GPT-4o) + Firecrawl**, this app helps you stay ahead of competitors, decode market sentiment, and track launch KPIs — all in one clean dashboard.

---

## 🧠 Overview

Three coordinated AI agents work together like your internal GTM strike team:

| Tab | What You Get |
|-----|---------------|
| **Competitor Analysis Agent** | Evidence-backed breakdowns of rivals’ latest launches — positioning, differentiators, pricing cues, and channel mix |
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
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Add API Keys

Create a `.env` file in the root folder:

```bash
OPENAI_API_KEY=sk-************************
FIRECRAWL_API_KEY=fc-************************
```

or paste the keys securely in the sidebar when running the app.

### 4️⃣ Run the App

```bash
streamlit run product_launch_intelligence_agent.py
```

Open your browser → [http://localhost:8501](http://localhost:8501)

---

## 🕹️ How to Use

1. Enter API keys in the sidebar (or use `.env`)  
2. Input a **company / product / hashtag**  
3. Pick a tab → click **Analyze**  
4. Wait a few seconds while the agents coordinate  
5. Review:
   - ✅ Summary bullets (top-level insights)  
   - 📊 Expanded deep-dive (tables, callouts, metrics)

---

## 🤖 How It Works

Each analysis type triggers a **specialized AI agent**, coordinated by an Agno Team:

| Agent | Role |
|--------|------|
| **Product Launch Analyst** | Evaluates competitive positioning, strategy, and differentiation |
| **Market Sentiment Specialist** | Analyzes social media chatter and consumer perception |
| **Launch Metrics Specialist** | Tracks adoption rates, press coverage, and performance signals |

Agents collaborate asynchronously, merging findings into one structured Markdown report.

---

## 🌐 Integrations

- 🔥 [Firecrawl API](https://firecrawl.dev) — for async web crawling  
- 🧠 [Agno Framework](https://github.com/agno-llm) — multi-agent orchestration  
- 🖥️ [Streamlit](https://streamlit.io) — for clean, interactive UI  

---

## 🧭 Ideal For

- Product Marketing & GTM Teams  
- Competitive Intelligence Analysts  
- Founders tracking category growth  
- Growth & Strategy Professionals  

---

## 🧰 Example Output

> **Company Analyzed:** Notion AI  
>
> **Summary:**  
> - 🚀 Strong cross-channel buzz after latest AI assistant update  
> - ⚖️ Positioning focuses on "creative flow" — not raw speed  
> - 💬 Sentiment: 78% positive mentions around UI polish & pricing fairness  
> - 📈 Estimated +20% traffic surge post-launch  

---

