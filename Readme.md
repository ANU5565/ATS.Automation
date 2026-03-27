
# 🚀 AI-Powered ATS Workflow (n8n)

An automated Applicant Tracking System (ATS) built using n8n and AI to analyze resumes, generate scores, and send structured evaluation emails to candidates.

---

## 📌 Features

- 📄 AI-based resume analysis  
- 📊 Compatibility rating (1–10)  
- 🎯 ATS score (out of 100)  
- ✅ Interview recommendation  
- 📧 Automated email responses  
- ⚡ End-to-end workflow automation  

---

## 🛠️ Tech Stack

- n8n (Workflow Automation)  
- OpenAI / LLM (Resume Analysis)  
- Gmail API (Email Sending)  
- HTML (Email Formatting)  

---

## 🔄 Workflow Overview

1. Candidate submits resume via form  
2. n8n captures submission data  
3. AI analyzes resume against job description  
4. Output is structured into JSON format  
5. Email is automatically sent with ATS report  

---

## 📷 Sample Output

```json
{
  "compatibility_rating": "8/10: Strong technical match with AI/automation projects.",
  "ats_score": "85/100",
  "recommendation": "Interview: Strong alignment with role requirements.",
  "summary": "Candidate has strong skills in Python, Django, and AI projects."
}
