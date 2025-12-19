# 🐞 Bug Reports

## Overview

This folder contains documented software defects discovered during manual QA testing. Each bug report is written as a separate Markdown file and includes key details to help developers understand, reproduce, and fix the issue. These reports support communication across teams and improve overall product quality.

---  

## Structure

- Each bug is stored in an individual `.md` file
- File names follow the format: `DEF-<ID>-<short-description>.md`
- Reports cover metadata, reproduction steps, expected and actual results, and related resources

---

## Available Bug Reports

| Defect ID | Title                                                                 | Status                  |
|-----------|------------------------------------------------------------------------|--------------------------|
| [BR-001](BR-001-status-not-updated.md) | Status request do not change             | Selected for Development |
| [BR-002](BR-002-wrong-notification.md) | Software notifications do not work correctly | Selected for Development |
| [BR-003](BR-003-invalid-document-upload.md) | Document upload validation is not working correctly        | Selected for Development |

---

## 🗂️ Bug Report Field Descriptions

| Field               | Description                                                             |
|---------------------|-------------------------------------------------------------------------|
| **Defect ID**       | Unique identifier for the issue, e.g., `DEF-217`                        |
| **Title**           | Brief summary of the bug                                                |
| **Status**          | Current progress: Open, Triaged, In Progress, Fixed, Closed             |
| **Severity**        | Impact on product functionality: Minor, Major, Critical                 |
| **Priority**        | Urgency for fixing: Low, Medium, High                                   |
| **Environment**     | Platform or configuration where the bug occurred                        |
| **Reproduction Steps** | Step-by-step instructions to reproduce the issue                 |
| **Expected Result** | What the system should have done                                        |
| **Actual Result**   | What the system did instead                                             |
| **Screenshots/Logs**| Supporting evidence (if available)                                      |
| **Related Test Cases** | Links to relevant manual or automated tests                        |
| **Reported On**     | Date the bug was documented                                             |
| **Reported By**     | Name or ID of the QA analyst who filed the bug                         |
| **Assignee**        | Person responsible for fixing the issue                                 |
---
