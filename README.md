<h1 align="center">
  <br>
  <img src="https://github.com/user-attachments/assets/14fff5bd-2e19-4a42-ba56-80dd91d3c60b" alt="LeadQualiAI Logo" width="60">
  <br>
  LeadQualiAI
  <br>
</h1>

<h4 align="center">An AI-powered lead qualification system that automates scoring, scraping, and CRM integration.</h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#system-workflow">System Workflow</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#future-improvements">Future Improvements</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-success.svg" alt="Project Status">
  <img src="https://img.shields.io/badge/ai-lead_scoring-blue" alt="AI Lead Scoring">
  <img src="https://img.shields.io/badge/automation-n8n-orange" alt="n8n Automation">
  <img src="https://img.shields.io/badge/crm-airtable-blueviolet" alt="Airtable CRM">
</p>

LeadQualiAI is an intelligent automation system that transforms raw lead data into actionable business insights. By combining web scraping, AI-driven analysis, and automated CRM workflows, it evaluates business credibility, budget potential, and digital presence to deliver instant lead scores.

🔗 **Live Demo:** [LeadQualiAI Web App](https://your-lovable-app-url.com)

> ⚠️ **Note:** The backend workflow runs locally via n8n. The demo works only when the workflow is active.

---

## ✨ Key Features

- **🤖 AI-based Lead Scoring:** Automatically categorizes leads as **Hot**, **Warm**, or **Cold** based on a multi-factor analysis.
- **🌐 Website Data Extraction:** Scrapes lead websites to gather contextual data for a more informed evaluation.
- **🔄 Automated Airtable CRM Integration:** Seamlessly creates new records or updates existing ones in your Airtable base.
- **🆔 Returning Lead Detection:** Identifies returning leads and intelligently updates their information and score, preventing duplicates.
- **📧 Email Notification System:** Sends automated, customizable email alerts for high-priority (Hot) leads.
- **⚡ Real-time Response:** Provides instant feedback to the user on the frontend, creating a responsive user experience.

---

## 🧠 System Workflow

The entire process is automated, running from the moment a user submits a form to the final database update and user notification.

**Form Submission → Webhook → Validation → Website Scraping → AI Scoring → Airtable Update → Response**

1. **Form Submission:** User submits lead details via web application
2. **Webhook Trigger:** Submission triggers n8n automation workflow
3. **Validation & Scraping:** Input data is validated and lead's website is scraped for insights
4. **AI Scoring:** LLM analyzes data to evaluate lead quality based on credibility, budget, and digital presence
5. **CRM Update:** Lead information and score are stored or updated in Airtable
6. **Real-time Response:** Results are returned instantly to the frontend

---

## 🛠️ Tech Stack

| Category | Technology |
| -------- | ---------- |
| **Frontend** | [Lovable](https://lovable.dev/) (SaaS-focused UI builder) |
| **Automation** | [n8n](https://n8n.io/) (Workflow automation platform) |
| **Database/CRM** | [Airtable](https://airtable.com/) (Cloud-based database and CRM) |
| **AI/LLM** | OpenAI API / Local LLM (for lead scoring and data analysis) |
| **Web Scraping** | HTTP Request & HTML Extract nodes within n8n |
| **Connectivity** | Webhooks for real-time data transfer |

---

## 📸 Screenshots

### 🔹 Lead Input Form
*[Screenshot placeholder - Add your form screenshot here]*

### 🔹 AI Qualification Result
*[Screenshot placeholder - Add your results screenshot here]*

### 🔹 n8n Workflow Automation
*[Screenshot placeholder - Add your workflow screenshot here]*

### 🔹 Airtable CRM
*[Screenshot placeholder - Add your Airtable screenshot here]*

---

## 🎯 What This Project Demonstrates

- **End-to-end Workflow Automation:** A complete automation pipeline connecting frontend, scraping tools, AI, and database
- **AI-Driven Decision Making:** Practical application of Large Language Models (LLMs) for business logic and classification
- **Real-time System Integration:** Seamless communication between various services to provide instant user feedback
- **Practical Use of Webhooks and APIs:** Demonstrates event-driven architecture and system integration

---

## 🔮 Future Improvements

- **☁️ Cloud Deployment:** Deploy the n8n workflow to a cloud instance for 24/7 public availability
- **📊 Enhanced UI/UX & Dashboard:** Build a more sophisticated dashboard with lead analytics, scoring trends, and pipeline metrics
- **📈 Lead Tracking & Reporting:** Add features to track lead interactions over time and generate automated reports
- **🧠 Advanced Scraping:** Incorporate more robust scraping logic to handle JavaScript-heavy sites and extract deeper insights

---

## ⭐ Project Goal

To showcase how the convergence of **AI** and **workflow automation** can revolutionize common business processes. This project demonstrates a tangible path to reducing manual effort, increasing efficiency, and enabling faster, data-driven decisions in lead qualification and sales operations.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 🙏 Acknowledgements

- [Lovable](https://lovable.dev/) for the rapid frontend development
- [n8n](https://n8n.io/) for the powerful, open-source automation platform
- [Airtable](https://airtable.com/) for the flexible, cloud-based database
- [OpenAI](https://openai.com/) for the AI models powering lead scoring
