💰 AI Finance Expense Automation System
<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Made%20With-n8n-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Powered%20By-AI-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Dashboard-Power%20BI-yellow?style=for-the-badge" />
</p>
<p align="center">
  <b>An end-to-end AI-powered expense automation system built with Google Forms, n8n, Google Sheets, and Power BI — enabling real-time financial tracking, intelligent workflow automation, and data-driven decision-making insights.</b>
</p>

📌 Table of Contents

Overview
Key Features
System Architecture
Tech Stack
Screenshots
Workflow
Getting Started
Use Cases
Project Structure
License


🔍 Overview
Managing business expenses manually is time-consuming and error-prone. This project automates the entire expense submission and approval lifecycle using AI and no-code/low-code tools. From form submission to Power BI dashboard visualization, every step is automated — saving hours of manual work and delivering real-time financial clarity.

✨ Key Features

📋 Smart Expense Submission — Employees submit expenses via a structured Google Form
⚙️ Automated Workflows — n8n orchestrates multi-step automation: data capture, categorization, and routing
🤖 AI-Powered Classification — Expenses are automatically categorized and flagged using AI logic
📊 Real-Time Dashboard — Power BI dashboard provides live financial insights and spend analysis
📧 Automated Email Notifications — Instant email confirmations and approvals sent to relevant stakeholders
🗂️ Centralized Data Storage — All records are stored and organized in Google Sheets for auditability


🏗️ System Architecture
Employee Submission
       │
       ▼
  Google Form  ──────────────────────────────────────────────┐
       │                                                      │
       ▼                                                      ▼
  n8n Workflow Engine                               Google Sheets (Storage)
  ┌─────────────────────┐                          ┌──────────────────────┐
  │ • Trigger on submit │                          │ • Raw expense data   │
  │ • AI categorization │  ──── updates ────────►  │ • Categorized logs   │
  │ • Approval routing  │                          │ • Approval status    │
  │ • Email dispatch    │                          └──────────────────────┘
  └─────────────────────┘                                     │
                                                              ▼
                                                    Power BI Dashboard
                                                   (Real-time Analytics)

🛠️ Tech Stack
ToolRoleGoogle FormsUser-facing expense submission interfacen8nWorkflow automation & orchestration engineGoogle SheetsCentralized data storage and loggingPower BIReal-time financial dashboard and analyticsAI (LLM)Expense classification and anomaly detectionGmail APIAutomated email notifications

📸 Screenshots
📝 Google Form — Expense Submission

Employees fill out a structured form with expense details, category, and supporting info.

Show Image

📄 Google Sheets — Automated Data Logging

All submitted expenses are automatically captured and structured in Google Sheets.

Show Image

⚙️ n8n — Workflow Architecture

The n8n workflow handles data routing, AI classification, approval logic, and email triggers.

Show Image

📧 Email Notification Output

Automated email sent to the submitter and approver upon successful expense submission.

Show Image

📊 Power BI Dashboard — Real-Time Financial Insights

A live Power BI dashboard visualizing expense trends, category breakdowns, and budget utilization.

Show Image

🔄 How It Works

Employee submits an expense via the Google Form (amount, category, date, description)
n8n triggers automatically upon form submission via Google Sheets webhook
AI classifies the expense into the correct category and checks for policy violations
Data is written to the structured Google Sheets expense log
Email notifications are dispatched to the submitter and finance approver
Power BI refreshes the dashboard with the latest data for real-time tracking


🚀 Getting Started
Prerequisites

Google Account (Google Forms + Sheets)
n8n (self-hosted or cloud)
Power BI Desktop or Power BI Service
Gmail API credentials (for email notifications)

Setup Steps

Clone the repository

bash   git clone https://github.com/nancygoel2302-alt/ai-finance-expense-automation-system-.git
   cd ai-finance-expense-automation-system-

Import the n8n workflow

Open your n8n instance
Navigate to Workflows → Import
Upload the workflow JSON file


Configure Google Sheets connection

Set up Google Sheets OAuth credentials in n8n
Update the Sheet ID in the workflow nodes


Set up email notifications

Add your Gmail credentials in n8n
Update the recipient email addresses in the Email node


Connect Power BI

Open powerbi_dashboard.pbix in Power BI Desktop
Refresh the data source pointing to your Google Sheet


Test the pipeline

Submit a test expense via the Google Form
Verify data flows through n8n → Sheets → Email → Dashboard




💼 Use Cases

Small & Medium Businesses — Automate expense reimbursement workflows
Finance Teams — Real-time visibility into team and department spending
Startups — Lightweight, low-cost alternative to enterprise expense tools
Consultants & Freelancers — Track and report client-billable expenses automatically


📁 Project Structure
ai-finance-expense-automation-system/
│
├── google_form.png              # Google Form UI screenshot
├── google_sheet.png             # Google Sheets data structure screenshot
├── n8n_architecture.png.jpeg    # n8n workflow diagram
├── email_output.png.jpeg        # Sample automated email output
├── powerbi_dashboard.png        # Power BI dashboard screenshot
├── README.md                    # Project documentation
└── LICENSE                      # License file

📄 License
This project is licensed under the terms specified in the LICENSE file.

<p align="center">
  Built with ❤️ by <a href="https://github.com/nancygoel2302-alt">nancygoel2302-alt</a>
</p>
<p align="center">
  ⭐ If you found this project helpful, please give it a star!
</p>
