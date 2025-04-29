# ✨ Landing Page Email Auto-Responder with Slack Alerts (n8n)

This project is a **simple but powerful automation** built using [n8n](https://n8n.io), designed to streamline your lead capture and onboarding process. When a visitor signs up through your landing page, this workflow springs into action — sending a **personalized welcome email** and notifying your team instantly via **Slack**.

No more manual follow-ups. No more missed leads. Just seamless communication, every time.

---

## 🖼 Visual Snapshot

![Workflow Screenshot](screenshots/workflow-diagram.png)

---

## 🚀 What This Automation Does

- ✅ **Monitors** a Google Sheet for new email signups
- 📬 **Sends** a welcome email to the new subscriber
- 💬 **Posts** a Slack message with the signup details to your team
- 🔁 Runs automatically every few minutes — totally hands-free

---

## 🔧 How It Works

1. **Trigger:** Detects a new row in a Google Sheet
2. **Email:** Sends a personalized welcome email via Gmail (or any SMTP provider)
3. **Slack:** Posts the signup info to a specific Slack channel

Easy to plug in. Easy to extend. No code required.

---

## 🛠 Setup Instructions

1. Import the `.json` workflow into your n8n instance
2. Connect your credentials:
   - **Google Sheets**
   - **Gmail or SMTP**
   - **Slack API**
3. Customize the email copy and Slack message
4. Deploy or test locally

> Tip: Use the included visual diagram for a quick reference of the flow.

---

## 🧩 Tech Stack

- [n8n](https://n8n.io)
- Google Sheets
- Gmail (or any SMTP-compatible service)
- Slack API

---

## 🌱 Ideas to Expand

This automation is just a starting point. You can take it even further by:

- Enriching leads with services like Clearbit
- Triggering a **multi-step onboarding sequence**
- Syncing signups with **Notion, Airtable, or your CRM**

---

### Automate your first impression — and never miss a lead again.
