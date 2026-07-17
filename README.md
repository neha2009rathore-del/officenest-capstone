# OfficeNest 🌿

**Sustainable Office Supplies & Corporate Gifting — Powered by AI & Workflow Automation**

OfficeNest is a business website and automation platform for a sustainable office-supplies and corporate-gifting company. It combines a modern, responsive website with AI-driven customer engagement (voice agent, chatbot, sentiment analysis) and backend workflow automation (n8n) to handle enquiries, calls, invoicing, and reporting with minimal manual effort.

## 🔗 Links

- **Live Website:** [Add your Bolt/deployed URL here]
- **Demo Video:** [Add your video link here]
- **Project Documentation:** `/docs/OfficeNest_Documentation.docx`
- **Architecture Diagram:** `/docs/OfficeNest_Architecture_Diagram.png`
- **Presentation (PPT):** `/docs/OfficeNest_Capstone.pptx`

## 💡 About

A one-stop platform supplying eco-friendly office essentials and curated corporate gifts to businesses that value sustainability and brand image — with a buying experience powered end-to-end by AI.

**Target customers:** HR & Admin teams, eco-conscious startups, companies sourcing corporate gifts for events and onboarding.

**Unique Value Proposition:**
- 100% sustainable, certified sourcing
- AI Voice Agent answers every call instantly
- Automated sentiment-based service recovery
- Same-day automated invoicing

## ✨ Features

- Modern, responsive UI with dynamic background and animated interactions
- Products/Services, Target Customers, and USP sections
- Contact page with business email, phone number, and contact form
- CTA buttons: Contact Us, Book a Demo, Get a Quote, Schedule a Call

## 🤖 AI Integration

- AI Voice Agent — answers inbound calls, collects enquiry details
- AI Chatbot — engages visitors and qualifies leads
- AI Email Assistant — auto-acknowledges enquiries
- AI Sentiment Analysis — classifies calls as Positive/Neutral/Negative
- AI Lead Qualification — scores and prioritizes enquiries

## ⚙️ Backend Automation (n8n)

| Workflow | Function |
|---|---|
| Email Automation | Auto-acknowledges emails, stores enquiries |
| Call Analytics | Logs call data & sentiment to Google Sheets |
| Analytics Reporting | Emails daily performance report to admin |
| Invoice Automation | Generates & sends invoice on payment |

n8n workflow export files are in `/workflows`.

## 🛠️ Tech Stack

- **Frontend:** Bolt (Bolt.new)
- **Automation:** n8n
- **AI:** Voice Agent, Sentiment Classification, Chatbot
- **Data:** Google Sheets
- **Communication:** Email + Telephony integration

## 📁 Repo Structure

```
├── website/          # Frontend source (from Bolt)
├── workflows/         # n8n workflow JSON exports
├── docs/              # Documentation, PPT, architecture diagram
└── README.md
```

## 📌 Status

Website and UI: ✅ Complete
Contact form: ✅ Complete
n8n ↔ website integration: 🔄 In progress
AI Voice Agent live connection: 🔄 In progress

## 🎓 Capstone Project

Built as part of a Capstone Project demonstrating web development, AI integration, and workflow automation for a business-ready digital solution.
