OpenAI GPT-4.1 LLM-Powered Email Security Automation using n8n

Project Overview

Built an automated email security workflow using n8n and OpenAI GPT-4.1 LLM to analyze incoming emails, identify potential phishing indicators, route verdicts, send security alerts, and maintain SOC audit logs.

Technologies Used

* n8n
* OpenAI GPT-4.1 (LLM)
* Gmail
* Google Sheets

Implementation Steps

1. Workflow Creation — Created the n8n workflow AI Phishing Detection v1.0.
2. Email Ingestion — Configured Gmail polling to receive incoming emails every minute.
3. LLM Analysis Engine — Integrated OpenAI GPT-4.1 to analyze email content and generate a security verdict.
4. Verdict Router — Configured an IF node to route emails based on the SUSPICIOUS verdict.
5. Security Alert Notification — Configured email notifications for suspicious emails.
6. SOC Audit Logger — Integrated Google Sheets to record sender, subject, verdict, and detection time.
7. Workflow Testing — Tested the workflow and checked email analysis, notifications, and audit logging.
8. Automatic Execution — Configured the workflow for automatic email processing.

Privacy

Sensitive information has been hidden or redacted in the project screenshots where applicable.

Screenshots

* Workflow Pipeline
* Email Ingestion
* OpenAI GPT-4.1 Analysis Engine
* Verdict Router
* Security Alert Notification
* SOC Audit Logger
* Email Notification
* SOC Audit Logs in Google Sheets

Author

Yashwanth Cherukuri
