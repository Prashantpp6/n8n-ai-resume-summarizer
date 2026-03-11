# AI Resume Summarizer (n8n + Groq LLM)

An AI-powered workflow built using **n8n** and **Groq LLM** that automatically extracts resume text from Google Drive, summarizes it into concise bullet points, and sends the summary to Telegram.

---

## 🚀 Project Overview

This project demonstrates how AI and workflow automation can be combined to process resumes automatically.

The workflow:

1. Downloads a resume from Google Drive
2. Extracts text from the file
3. Sends the text to Groq LLM for summarization
4. Generates concise bullet-point insights
5. Sends the summary to a Telegram bot

This automation reduces manual resume analysis and shows how AI agents can be integrated into workflow tools.

---

## ⚙️ Workflow Architecture

Manual Trigger
↓
Google Drive – Download Resume
↓
Extract Text from File
↓
Groq LLM – AI Resume Summary
↓
Telegram – Send Summary

---

## 🧠 Technologies Used

* **n8n** – Workflow automation platform
* **Groq API** – Llama 3.1 model for AI summarization
* **Google Drive API** – Resume storage and retrieval
* **Telegram Bot API** – Notification delivery

---

## 📂 Project Structure

```
n8n-ai-resume-summarizer
│
├── workflow
│   └── resume-summary-workflow.json
│
├── README.md
│
└── screenshots
```

---

## 🔑 Setup Instructions

1. Install or open **n8n**
2. Import the workflow JSON file
3. Configure the following credentials:

   * Google Drive
   * Groq API Key
   * Telegram Bot
4. Replace the placeholder:

```
YOUR_GROQ_API_KEY
```

5. Execute the workflow

---

## 📌 Example Output

The Telegram bot returns a summary like:

* Data analyst with strong SQL, Python, and Power BI skills
* Experience building business intelligence dashboards
* Completed projects in churn analysis and sales analytics
* Skilled in data modeling, Power Query, and DAX
* Strong analytical and problem-solving abilities

---

## 🎯 Use Case

This project demonstrates practical applications of:

* AI workflow automation
* LLM integration into business pipelines
* Automated document processing

It can be extended into more advanced systems such as:

* AI Resume Parser
* Job Matching Systems
* Automated Job Application Agents

---

## 👨‍💻 Author

**Prashant Singh Parmar**

LinkedIn
https://www.linkedin.com/in/prashant-singh-parmar/

GitHub
https://github.com/Prashantpp6

---

## ⭐ Future Improvements

* AI skill extraction from resumes
* Resume-job matching system
* Automatic job application automation
* Vector database integration for resume search
