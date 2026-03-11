![GitHub Repo stars](https://img.shields.io/github/stars/Prashantpp6/n8n-ai-resume-summarizer?style=social)

# AI Resume Summarizer (n8n + Groq LLM)

An AI-powered workflow built using **n8n** and **Groq LLM** that automatically extracts resume text from **Google Drive**, summarizes it into concise bullet points using **Llama 3.1**, and sends the results to **Telegram**.

This project demonstrates how **Large Language Models (LLMs)** can be integrated with workflow automation platforms to build intelligent document-processing pipelines.

---

# 🚀 Project Overview

Recruiters and HR teams often spend significant time manually reviewing resumes.

This project demonstrates how **AI + workflow automation** can reduce that effort by automatically extracting insights from resumes and delivering summarized profiles instantly.

The system:

1. Downloads a resume from Google Drive
2. Extracts text from the document
3. Sends the text to the Groq LLM API
4. Generates structured bullet-point summaries
5. Sends the results directly to a Telegram bot

This automation shows how **AI agents can be integrated into workflow tools** to automate document analysis.

---

# ⚙️ Workflow Architecture

```
Manual Trigger
      ↓
Google Drive – Download Resume
      ↓
Extract Text from File
      ↓
Groq LLM (Llama 3.1) – AI Resume Summary
      ↓
Telegram Bot – Send Summary
```

---

# 📸 Workflow Preview

### n8n Workflow

![Workflow](screenshots/workflow.png)

### Telegram Output

![Telegram Output](screenshots/telegram-output.png)

---

# 🧠 Technologies Used

* **n8n** – Workflow automation platform
* **Groq API (Llama 3.1)** – Large Language Model for summarization
* **Google Drive API** – Resume storage and retrieval
* **Telegram Bot API** – Automated notification delivery
* **Node-based AI pipelines** – Workflow orchestration

---

# 🧩 AI Workflow Logic

1. Resume file is stored in **Google Drive**
2. **n8n workflow** downloads the document
3. Text extraction converts the document into raw text
4. **Groq Llama 3.1 LLM** analyzes the content
5. AI generates structured bullet-point insights
6. **Telegram bot** sends the summary to the user

---

# 🎥 Demo

This workflow automatically processes resumes and sends summarized insights to Telegram.

Automation pipeline:

```
Resume → AI Processing → Smart Summary → Telegram Notification
```

---

# 📂 Project Structure

```
n8n-ai-resume-summarizer
│
├── workflow
│   └── resume-summary-workflow.json
│
├── screenshots
│   ├── workflow.png
│   └── telegram-output.png
│
├── README.md
│
└── prashant-resume.txt
```

---

# 🔑 Setup Instructions

### 1️⃣ Install n8n

Install locally or use n8n cloud.

https://n8n.io/

### 2️⃣ Import Workflow

Import the file:

```
workflow/resume-summary-workflow.json
```

### 3️⃣ Configure Credentials

You need to configure:

* Google Drive API
* Groq API Key
* Telegram Bot Token

### 4️⃣ Replace API Key

Replace:

```
YOUR_GROQ_API_KEY
```

with your actual **Groq API key**.

### 5️⃣ Execute the Workflow

Trigger the workflow manually to process the resume and send the summary to Telegram.

---

# 📌 Example Output

The Telegram bot returns a summary like:

* Data analyst with strong SQL, Python, and Power BI skills
* Experience building business intelligence dashboards
* Completed projects in churn analysis and sales analytics
* Skilled in data modeling, Power Query, and DAX
* Strong analytical and problem-solving abilities

---

# 🎯 Use Cases

This project demonstrates practical applications of:

* AI-powered document processing
* Resume intelligence systems
* LLM integration into automation pipelines
* HR technology automation

It can be extended into more advanced systems such as:

* AI Resume Parser
* Job Matching Systems
* Automated Job Application Agents
* Resume Skill Extraction Systems

---

# 💡 Why This Project Matters

Organizations process thousands of resumes during recruitment.

This project shows how **AI and automation can reduce manual resume screening** by generating quick insights from candidate profiles.

It highlights skills in:

* AI workflow engineering
* LLM integration
* automation pipelines
* real-world business process automation

---

# ⭐ Future Improvements

Planned improvements for this project:

* AI skill extraction from resumes
* Resume-job matching system
* Automatic job application automation
* Vector database integration for resume search
* Resume ranking system using embeddings

---

# 👨‍💻 Author

**Prashant Singh Parmar**

🔗 LinkedIn
https://www.linkedin.com/in/prashant-singh-parmar/

💻 GitHub
https://github.com/Prashantpp6

---

This project is part of my portfolio demonstrating **AI automation, LLM integration, and workflow engineering**.
