# Job Search Agent

The Job Search Agent is a tool that automates the job-hunting process.  
You provide the **job title** you want, and the agent will:  
1. Search for current openings online.  
2. Generate a structured job report (with descriptions, companies, and application links).  
3. Send the report directly to your email.  

---

## Features
- 🎯 **Targeted Search** – Enter the job title you’re looking for (e.g., `"Software Engineer"`).  
- 📊 **Job Report Generation** – Collects role, company, location, and application link.  
- 📧 **Email Delivery** – Sends the full report to your email automatically.  
- 🔄 **Repeatable Workflow** – Run it anytime with a new job title.  

---

## Tech Stack
- **Python** – Core implementation  
- **OpenAI Web Search** – For finding job postings  
- **Email Integration** – SendGrid for email notifications

---
4. The report is sent to the user’s email.  

---

## Installation
### env
- OPENAI_API_KEY=your_api_key_here
- EMAIL_USER=your_email@example.com
- EMAIL_PASS=your_password
- SENDGRID_API_KEY = your_api_key_here

