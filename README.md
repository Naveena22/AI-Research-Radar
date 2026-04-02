# 🚀 AI Research Radar (n8n Automation)

An automated AI news intelligence system built using n8n.

## 🔥 What It Does
- Fetches latest AI news from Hacker News API
- Uses OpenAI to summarize and score importance
- Logs insights into Google Sheets
- Sends a daily email digest at 7 AM

## 🧠 Tech Stack
- n8n (workflow automation)
- OpenAI API (GPT-4o-mini)
- Google Sheets API
- Gmail API

## ⚙️ Workflow Steps
1. Schedule trigger (daily 7 AM)
2. Fetch AI news (Hacker News API)
3. Filter top 5 stories
4. AI summarization + scoring
5. Parse structured response
6. Store in Google Sheets
7. Send email digest

## 📸 Screenshots
(Add screenshots of your workflow here)

## 🚀 How to Use
1. Import the JSON into n8n
2. Add your credentials:
   - OpenAI API key
   - Google Sheets
   - Gmail
3. Activate the workflow

## 💡 Use Cases
- AI trend tracking
- Daily research automation
- Tech intelligence dashboards

## 👩‍💻 Built By
(Your Nam