# 🤖 AI Support Ticket Auto-Triage System

An AI-powered customer support automation workflow built with **n8n and OpenAI**. The system analyzes incoming customer support tickets, determines their priority, recommends an appropriate action, stores the results in Google Sheets, and sends automated email notifications for high-priority tickets.

## 🔄 Workflow

```text
Webhook
   ↓
Edit Fields
   ↓
OpenAI
   ↓
Format Ticket
   ↓
Google Sheets
   ↓
IF
   ↓
Gmail
