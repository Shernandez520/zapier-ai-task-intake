# zapier-ai-task-intake
📬 AI Task Intake Automation (Zapier • No-Code)
A lightweight workflow that automatically converts actionable emails into structured task data using Zapier’s free tier.
This project demonstrates clear automation logic, operational workflow design, and the fundamentals needed for AI-enabled process automation.
⭐ Overview
Many teams receive tasks by email, but inboxes are unstructured and hard to track.
This automation solves that by:
Watching Gmail for emails containing task-related keywords
Extracting relevant information
Logging each task into a structured Google Sheet
This creates visibility, reduces cognitive load, and forms a foundation for more advanced AI-driven workflow automation.
🧠 Problem
Task requests arrive in email with no structure, no categorization, and no tracking.
Operations teams waste time manually logging tasks or, worse, lose visibility entirely.
🎯 Goal
Create an automation that:
Identifies actionable emails
Extracts structured data
Logs the information to a central source of truth
Works entirely on free-tier tools
Demonstrates clean automation design for portfolio purposes
🛠 Tools Used
Zapier (Free Tier)
Gmail
Google Sheets
⚙️ Workflow Logic
Trigger
App: Gmail
Event: New Email Matching Search
Search Query:
subject:task OR subject:"action needed" OR subject:"to do"
Action
App: Google Sheets
Event: Create Spreadsheet Row
Fields Mapped:
Google Sheet Column	Zapier Field
Task	Subject
Sender	From Name
Email	From Email
Date	Date
📄 Output Example (Google Sheet)
Task	Sender	Email	Date
New onboarding task	John Doe	john@company.com	2025-12-04
Action needed: contract file	Maria Lee	maria@company.com	2025-12-05
🚀 Impact
Eliminates manual task logging
Reduces operational bottlenecks
Creates searchable, structured task data
Demonstrates automation capability without premium tools
Shows foundational skill for AI workflow and automation engineering
📸 Screenshots
All screenshots are stored in the /screenshots folder:
Zap Overview
Gmail Trigger Setup
Google Sheets Action Setup
Google Sheet Output
🔮 Future Enhancements
Task priority detection via subject-line parsing
AI-generated summaries
Slack notifications
Auto-tagging workflow branches
Integration with Notion or Jira
📝 License
MIT License — free to use, modify, and share.
