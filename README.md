# 🤖 AI-Powered IT News Automation System

An intelligent automation system built with **n8n** that automatically collects, filters, analyzes, summarizes, and delivers important IT and technology updates directly to Gmail.

## 📌 Project Overview

Keeping up with the fast-changing technology world requires checking multiple platforms every day. This project automates that process by collecting updates from different technology sources and using Large Language Models (LLMs) to analyze and summarize the information.

The final output is delivered as a clean and easy-to-read IT news digest through Gmail.

## ⚙️ How It Works

Schedule Trigger

       ↓
       
Collect Latest News from RSS Sources

       ↓
       
Merge Multiple Data Sources

       ↓
       
Remove Duplicate News

       ↓
       
Process and Filter Relevant Updates

       ↓
       
AI Analysis using OpenAI & Google Gemini

       ↓
       
Merge AI Results

       ↓
       
Generate Final IT News Summary

       ↓
       
Send Summary to Gmail


News Sources

The workflow collects technology updates from:
GitHub
OpenAI
AWS
Microsoft

🧠 AI Models Used

OpenAI Chat Model
Google Gemini Chat Model

The AI models help analyze, organize, and summarize the collected technology updates into useful information.

🛠️ Technologies Used

n8n – Workflow Automation
OpenAI – AI Analysis
Google Gemini – AI Analysis
RSS Feeds – News Collection
Gmail – Automated Email Delivery

✨ Key Features

⏰ Automated scheduled execution
📰 Collects news from multiple IT sources
🔄 Merges data from different feeds
🗑️ Removes duplicate updates
🔍 Filters relevant information
🤖 Uses multiple LLMs for AI-powered analysis
📧 Sends a summarized IT news digest automatically to Gmail
☁️ Runs automatically through n8n Cloud

📂 Project Structure

AI-IT-News-Automation/
│
├── README.md
└── ai-it-news-automation.json

🚀 How to Use

Clone or download this repository.
Import ai-it-news-automation.json into your n8n workspace.
Configure your RSS sources.
Add your OpenAI and Google Gemini credentials.
Configure Gmail credentials.
Set your preferred schedule.
Test the workflow.
Activate/Publish the workflow.

🔒 Security

API keys, passwords, access tokens, and personal credentials are not included in this repository. Configure your own credentials after importing the workflow.

🔮 Future Improvements

Add more trusted IT and technology news sources
Add personalized news categories
Improve AI-based relevance filtering
Add web search capabilities for broader coverage
Create a dashboard for viewing daily IT updates
Add alternative notification channels such as WhatsApp or Telegram

📸 Workflow
--------------------------------------------------------------
👩‍💻 Author

Kiran Nadeem

BBIT Student | Exploring Artificial Intelligence, Automation & Cybersecurity
--------------------------------------------------------------

If you find this project useful, consider giving the repository a star!
