# MIRA-Ai
# 🌙 MIRA – Mental Insight & Reflection Agent

MIRA is a poetic journaling AI agent designed to gently guide users through emotional exploration.  
Built using **n8n**, **Azure OpenAI (GPT-4o)**, and a **custom UI**, MIRA provides real-time reflective questions and affirmations.

---

## ✨ What Makes MIRA Unique?

Unlike traditional mental health bots, MIRA doesn’t just respond — she reflects with you.

✅ Always provides:
- 🪞 A deep **reflection question** based on user’s emotion or message  
- 🧘 A poetic **affirmation** to support emotional wellbeing

✅ Beautiful frontend (hosted via GitHub Pages)  
✅ No login, no prompts — just talk, and she reflects.

---

## 🧠 Tech Stack

| Layer         | Tech Used                         |
|---------------|------------------------------------|
| Agent Logic   | n8n workflow automation            |
| Language Model| Azure OpenAI GPT-4o                |
| Frontend UI   | HTML + CSS (Figma-inspired)        |
| Hosting       | GitHub Pages + n8n Public Webhook  |

---

## 🌐 How It Works

🔗 **Public Webhook URL**:  
https://lalitya31.app.n8n.cloud/workflow/V5PgMKzRGM4Bb5zl

📨 You send a message (like “I feel stuck”)  
MIRA responds with:
```json
{
  "reflection": "🪞 Reflection: What is one small action you can take right now to regain momentum?",
  "affirmation": "🧘 Affirmation: Even stillness is part of the journey."
}
