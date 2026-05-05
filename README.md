# AI Finance Expense Automation System

## Project Overview
This project demonstrates an end-to-end automated expense management system built using no-code and analytics tools. It integrates Google Forms, Google Sheets, n8n workflow automation, and Power BI to create a real-time financial tracking and decision-making system.

The solution eliminates manual expense tracking, reduces processing time, and provides instant visibility into organizational spending.

---

## Business Problem
Traditional expense management systems rely heavily on:
- Manual data entry
- Email approvals
- Spreadsheet tracking
- Delayed reporting

This results in:
- Increased errors
- Slow reimbursements
- Lack of real-time insights
- Poor financial decision-making

---

## Solution
This system automates the entire workflow:

1. Employee submits expense via Google Form  
2. Data is captured in Google Sheets  
3. n8n triggers workflow automatically  
4. Email notification sent to finance team  
5. Data available for dashboard analysis in Power BI  

---

## Tools and Technologies Used
- Google Forms (Data Input)
- Google Sheets (Data Storage)
- n8n (Workflow Automation)
- Gmail (Email Notifications)
- Microsoft Power BI (Dashboard & Analytics)

---

## Workflow Architecture
The system follows this pipeline:

Google Form → Google Sheets → n8n Workflow → Email Notification → Power BI Dashboard

---

## Project Structure

Finance-Automation-Project/
│
├── n8n_workflow/
│ └── expense_automation_workflow.json
│
├── ppt/
│ └── expense_tracker_presentation.pptx
│
├── screenshots/
│ ├── form_view.png
│ ├── sheet_data.png
│ ├── workflow_diagram.png
│ └── email_notification.png

---

## Screenshots

### 1. Google Form Interface
![Google Form](screenshots/form_view.png)

---

### 2. Google Sheet Data Capture
![Google Sheet](screenshots/sheet_data.png)

---

### 3. n8n Workflow Architecture
![n8n Workflow](screenshots/workflow_diagram.png)

---

### 4. Email Notification Output
![Email Notification](screenshots/email_notification.png)

---

## Key Features
- Automated expense data capture
- Real-time workflow triggering using n8n
- Instant email alerts to finance team
- Centralized expense tracking
- Scalable integration with dashboards

---

## Business Impact
- Reduced manual effort and errors
- Faster expense processing
- Improved transparency in spending
- Real-time financial insights
- Better budgeting and control

---

## Real-World Applications
This type of system is used in:
- Corporate finance departments
- Shared service centers
- Consulting firms
- Startups automating operations

---

## How to Run the Project
1. Create Google Form for expense submission  
2. Link responses to Google Sheets  
3. Build n8n workflow using Google Sheets Trigger  
4. Configure Gmail node for notifications  
5. Connect data to Power BI for dashboard  

---

## Future Enhancements
- Approval workflow integration  
- Fraud detection using AI models  
- Budget threshold alerts  
- Role-based dashboards  
- Integration with ERP systems  

---

## Conclusion
This project demonstrates how AI and automation can transform traditional finance operations into intelligent, real-time systems that support strategic decision-making.

---

## Author
MBA Finance Student | AI in Finance Practitioner
Nancy
