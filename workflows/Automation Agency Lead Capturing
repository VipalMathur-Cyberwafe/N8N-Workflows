# 🤖 AI Lead Capture & Qualification System

An AI-powered lead capture and qualification workflow built with **n8n** and **Google Gemini**. The workflow automatically validates incoming leads, prevents duplicates, analyzes lead quality using AI, stores qualified leads, and notifies the sales team.

---

## 📌 Overview

Businesses receive numerous leads every day, but manually validating, qualifying, and prioritizing them consumes valuable time.

This workflow automates the entire process by:

- Validating incoming lead data
- Preventing duplicate entries
- Using AI to analyze lead quality
- Assigning lead priority
- Sending notifications
- Storing qualified leads

---

## 🚀 Features

- ✅ Webhook-based API endpoint
- ✅ Email validation
- ✅ Phone number validation
- ✅ Duplicate lead detection
- ✅ AI-powered lead qualification
- ✅ Lead scoring (0–100)
- ✅ Priority classification
- ✅ Budget analysis
- ✅ Industry identification
- ✅ Customer intent detection
- ✅ Sentiment analysis
- ✅ Recommended follow-up action
- ✅ Next follow-up date generation
- ✅ Google Sheets integration
- ✅ Customer confirmation email
- ✅ Internal Slack notification for high-priority leads
- ✅ Basic lead information stored separately for duplicate detection

---

# 🏗 Workflow Architecture

```
Webhook
    │
    ▼
Validate Input
    │
    ▼
Duplicate Check
    │
 ┌── Duplicate
 │       │
 │       ▼
 │  Return Response
 │
 ▼
Google Gemini AI
    │
    ▼
Parse JSON Response
    │
    ▼
Lead Score Decision
    │
 ┌──────────────┐
 │              │
 ▼              ▼
High Lead    Normal Lead
 │              │
 ▼              ▼
Slack       Google Sheets
 │              │
 └──────┬───────┘
        ▼
Customer Email
        │
        ▼
Store Lead Details
        │
        ▼
Webhook Response
```

---

# 🧠 AI Analysis

Google Gemini analyzes each lead and returns structured JSON containing:

- Lead Score
- Priority
- Budget Category
- Industry
- Customer Intent
- Urgency
- Sentiment
- Recommended Action
- Next Follow-up Date
- Summary

Example:

```json
{
  "lead_score": 91,
  "priority": "High",
  "budget": "High",
  "urgency": "Immediate",
  "industry": "Healthcare",
  "intent": "Purchase",
  "sentiment": "Positive",
  "recommended_action": "Call within 30 minutes",
  "next_follow_up": "2026-09-10",
  "summary": "Hospital requires an AI chatbot urgently."
}
```

---

# 📂 Tech Stack

- n8n
- Google Gemini
- Google Sheets
- Gmail
- Slack
- Data Tables
- Webhooks
- JavaScript (JSON Parsing)

---

# 📥 Sample API Request

```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "phone": "9876543210",
  "company": "ABC Hospital",
  "budget": "₹4,00,000",
  "description": "We need an AI chatbot for patient support."
}
```

---

# 📤 Sample AI Output

```json
{
  "lead_score": 95,
  "priority": "High",
  "budget": "High",
  "industry": "Healthcare",
  "urgency": "Immediate",
  "intent": "Purchase",
  "recommended_action": "Call immediately",
  "summary": "High-value healthcare lead looking for AI automation."
}
```

---

# ⚙ Workflow Logic

1. Receive lead via Webhook.
2. Validate email and phone number.
3. Check for duplicate leads.
4. Send lead details to Google Gemini.
5. Parse AI response.
6. Determine lead priority.
7. Store AI analysis in Google Sheets.
8. Notify sales team for high-priority leads.
9. Send confirmation email to the customer.
10. Store basic lead information for future duplicate checks.
11. Return success response.

---

# 📁 Repository Structure

```
AI-Lead-Capture-System/

│
├── README.md
├── workflow.json
└── screenshots/
      ├── workflow-overview.png
      ├── ai-analysis.png
      └── execution.png
```

---

# 🔐 Environment Variables

Configure the following credentials before running the workflow:

- Google Gemini API
- Gmail OAuth
- Slack Webhook
- Google Sheets Credentials

---

# 📸 Screenshots

Add screenshots of:

- Complete Workflow
- AI Output
- Google Sheets Result
- Slack Notification
- Email Notification
- Successful Execution

---

# 💡 Business Use Cases

- Digital Marketing Agencies
- SaaS Companies
- Hospitals
- Law Firms
- Educational Institutions
- Real Estate Agencies
- Consulting Businesses

---

# 📈 Future Improvements

- CRM Integration (HubSpot, Zoho, Salesforce)
- WhatsApp Notifications
- Dashboard & Analytics
- Spam Detection
- Phone-Based Duplicate Detection
- Automatic Follow-up Scheduling
- Multi-language Support
- Error Logging & Monitoring

---

# 👨‍💻 Author

**Vipul Mathur**

Aspiring AI Automation Engineer focused on building business automation solutions using n8n, AI, APIs, and modern workflow automation tools.

---

## ⭐ If you found this project useful, consider giving it a star!
