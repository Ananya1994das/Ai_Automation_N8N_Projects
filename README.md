# Ai_Automation_N8N_Projects
A collection of real-world n8n workflow automation projects showcasing end-to-end process automation, API integrations, data processing, AI-powered workflows, and business process optimization. Includes workflow configurations, sample datasets, execution outputs, and project documentation.

# 📰 Daily AI News Automation
### *Your Daily Dose of AI News — Automated with n8n & AI*

![n8n](https://img.shields.io/badge/Automation-n8n-orange?style=for-the-badge&logo=n8n)
![AI](https://img.shields.io/badge/AI-Powered-blueviolet?style=for-the-badge&logo=openai)
![Email](https://img.shields.io/badge/Delivery-Email-red?style=for-the-badge&logo=gmail)
![Automation](https://img.shields.io/badge/Schedule-Daily%209%20AM-green?style=for-the-badge&logo=clockify)

## 🚀 Project Overview

Stay informed. Save time. Let AI do the reading!

This project automates daily AI news monitoring using **n8n and AI-powered summarization**.

Every morning at **9:00 AM**, the workflow fetches the top 5 AI-related news updates, processes each article using an AI model, and generates a concise 5–6 sentence summary designed for an approximately one-minute read.

The curated news digest is then delivered directly to my email inbox — keeping me updated on the latest AI developments without manually searching through multiple news sources.

## ⚙️ Workflow Architecture

| Stage | Process | Function |
|---|---|---|
| 01 | ⏰ Schedule Trigger | Starts automation daily at 9:00 AM |
| 02 | 🌐 News Retrieval | Fetches the top 5 AI-related news articles |
| 03 | 🔀 Split Out | Separates individual news articles |
| 04 | 🤖 AI Summarization | Generates concise 5–6 sentence summaries |
| 05 | 📧 Email Integration | Delivers the curated news digest to my inbox |

## ✨ Key Features

- 📰 Daily collection of the top 5 AI news updates
- 🤖 AI-powered article summarization
- 📖 5–6 sentence summaries for a one-minute reading experience
- ⏰ Fully automated delivery every morning at 9:00 AM
- 📩 Direct email delivery of curated news updates
- ⚡ Reduced manual research and information overload

## 🛠️ Tech Stack

- **Workflow Automation:** n8n
- **News Retrieval:** News Search / API Integration
- **AI Processing:** AI / Large Language Model (LLM)
- **Communication:** Email Integration
- **Scheduling:** n8n Schedule Trigger

## 📁 Repository Structure

```text
daily-ai-news-automation/
│
├── workflow.json
├── README.md
├── sample_output.md
│
└── screenshots/
    ├── workflow-overview.png
    ├── execution-result.png
    └── email-output.png
```

## 🚀 Getting Started

1. Clone or download this repository.
2. Import `workflow.json` into your n8n instance.
3. Configure the required news source and AI credentials.
4. Set up your email integration.
5. Configure the daily schedule for 9:00 AM.
6. Execute the workflow and verify email delivery.

## 🎯 Project Objective

To build an intelligent news-monitoring system that combines **AI-powered summarization and workflow automation** to make daily learning faster, easier, and more accessible.

---

⭐ *An automation project demonstrating how Generative AI can transform everyday information consumption into a streamlined, intelligent workflow.*




# 💼 AI-Powered Job Search Automation
### *Automating Job Discovery with n8n, Gemini AI & Google Sheets*

![n8n](https://img.shields.io/badge/Automation-n8n-orange?style=for-the-badge&logo=n8n)
![Google Gemini](https://img.shields.io/badge/AI-Gemini-blue?style=for-the-badge&logo=googlegemini)
![Google Sheets](https://img.shields.io/badge/Storage-Google%20Sheets-green?style=for-the-badge&logo=googlesheets)
![JSON](https://img.shields.io/badge/Format-JSON-lightgrey?style=for-the-badge&logo=json)

## 🚀 Project Overview

Finding relevant job opportunities can be time-consuming. This project automates the job discovery and information-processing process using **n8n and Generative AI**.

The workflow retrieves job listings through Google Jobs Search, processes individual records using Gemini AI, structures the extracted information, and automatically stores the results in Google Sheets.

## ⚙️ Workflow Architecture

| Stage | Node | Function |
|---|---|---|
| 01 | ⏰ Schedule Trigger | Initiates automated job searches |
| 02 | 🔎 Google Jobs Search | Retrieves relevant job listings |
| 03 | 🔀 Split Out | Separates individual job records |
| 04 | 🤖 Gemini AI | Processes job information using AI |
| 05 | 📝 Edit Fields | Structures the extracted information |
| 06 | 📊 Google Sheets | Appends or updates job records |

## ✨ Key Features

- 🔄 Automated job search and data collection
- 🤖 AI-powered job information processing
- 📂 Individual record extraction and transformation
- 📊 Structured data management using Google Sheets
- ⏰ Scheduled workflow execution
- ⚡ Reduced manual effort in job information tracking

## 🛠️ Tech Stack

- **Workflow Automation:** n8n
- **AI Integration:** Google Gemini
- **Data Retrieval:** Google Jobs Search
- **Data Storage:** Google Sheets
- **Data Format:** JSON

## 📁 Repository Structure

```text
n8n-job-search-automation/
│
├── workflow.json
├── README.md
├── sample_output.csv
│
└── screenshots/
    ├── workflow-overview.png
    ├── execution-result.png
    └── google-sheets-output.png
```

## 🚀 Getting Started

1. Clone or download this repository.
2. Import `workflow.json` into your n8n instance.
3. Configure the required API integrations and credentials.
4. Connect your Google Sheets account.
5. Configure the search parameters and schedule.
6. Execute the workflow and verify the results.

## 🎯 Project Objective

To demonstrate how **workflow automation and Generative AI** can simplify job discovery, automate information processing, and create a structured job-tracking system.

---

⭐ *An automation project exploring the practical application of AI-driven workflows and intelligent data management.*
