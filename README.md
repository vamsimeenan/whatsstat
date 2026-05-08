# 📊 WhatsStats

> **Intelligent WhatsApp Chat Analysis & Visualization Platform** — Transform raw chat exports into powerful insights, statistics, and visual analytics.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-red?style=for-the-badge&logo=streamlit&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge) ![License](https://img.shields.io/badge/License-Apache_2.0-green?style=for-the-badge)

---

## 📌 Overview

**WhatsStats** transforms raw WhatsApp `.txt` chat exports into meaningful insights and interactive dashboards. Using **Regex parsing**, **NLP**, **Pandas**, and **Streamlit**, it uncovers communication patterns, activity trends, emoji habits, and user behavior — all in one clean analytics platform.

Raw chat exports are unstructured and impossible to analyze manually. WhatsStats automates the entire pipeline from export to insight.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📈 Activity Analytics | Daily, monthly & hourly messaging trend analysis |
| 👥 User Tracking | Identify the most active participants in any chat |
| 📝 Word Frequency | Discover most commonly used words and phrases |
| 😂 Emoji Analytics | Track emoji usage and communication personality |
| ⏰ Time-Based Insights | Visualize peak chatting hours and active periods |
| 🌐 Interactive Dashboard | Clean, responsive Streamlit analytics interface |

---

## 🏗️ Architecture

WhatsApp Chat Export → Chat Preprocessing → Regex Text Parsing
→ NLP & Data Analysis → Statistical Insights
→ Visualization Layer → Streamlit Dashboard
---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| Python | Core Development |
| Pandas | Data Analysis |
| Regex | Text Parsing & Extraction |
| Matplotlib / Seaborn | Visualization & Statistical Graphs |
| Streamlit | Interactive Dashboard |

---

## 📂 Structure
WhatsStats/
├── data/
├── preprocessing/
├── analytics/
├── visualizations/
├── assets/
├── app.py
└── requirements.txt
---

## 🚀 Quick Start

```bash
# 1. Clone
git clone https://github.com/vamsimeenan/whatsstat.git
cd whatsstat

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate        # Mac/Linux
# venv\Scripts\activate         # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the dashboard
streamlit run app.py
```

> **How to export your chat:** WhatsApp → Chat → ⋮ Menu → Export Chat → Without Media → save the `.txt` file → upload to WhatsStats.

---

## 📊 Insights Generated

- ✅ Total message count & most active participant
- 📈 Daily, monthly & hourly activity trends
- 🔤 Most frequently used words
- 😂 Emoji usage breakdown
- ⏰ Peak chatting hours & communication patterns

---

## 🔮 Roadmap

- [ ] Sentiment analysis on messages
- [ ] AI-powered chat summarization
- [ ] Multi-language support
- [ ] Group vs. individual comparison analytics
- [ ] Exportable PDF reports
- [ ] Cloud deployment
- [ ] Advanced NLP insights

---

## 👨‍💻 Author

**Vamsi Meenan Ravuri** — Data Analytics • AI • Software Engineering

[![GitHub](https://img.shields.io/badge/GitHub-vamsimeenan-black?style=flat&logo=github)](https://github.com/vamsimeenan)

---

## 🤝 Contributing

Fork → create a branch → commit → open a Pull Request. All contributions welcome!

---

⭐ **Star** the repo if it helped • 🍴 **Fork** and build on it • 📜 Apache-2.0 License

*Because your chats deserve better than a `.txt` file. 💬*
