# Jira Cloud Agile QA Portfolio Project

## Project Overview
This repository documents a hands-on manual testing project executed within a sandbox Jira Software environment. The goal was to establish full requirement traceability, manage an active Scrum sprint lifecycle, and practice production-level defect reporting for an E-Commerce system.


##  Agile Project Architecture
- **Epic:** User Login, Registration, and Account Security Module (`SCRUM-5`)
- **User Story:** As a registered user, I want to successfully log into my account using valid credentials (`SCRUM-6`)
- **Sprint Management:** Enforced project timelines by mapping requirement backlogs into an active 2-week Scrum Sprint container (`SCRUM Sprint 2`).

---

##  Defect Reporting & Traceability
During functional testing of the login authentication criteria, a severe system regression was identified. A comprehensive, production-grade defect report was generated to ensure clear communication with the development team:

- **Defect Ticket ID:** `SCRUM-7`
- **Summary:** `[Bug] [Login] - 500 Internal Server Error displayed when submitting valid credentials`
- **Traceability Link:** Configured an explicit `is blocked by` relationship, mapping the defect ticket directly as a blocker to the parent User Story (`SCRUM-6`).

###  Production Bug Report Layout
```text
[Environment]
OS: Windows 11 / Browser: Chrome v131
URL: https://ecommerce-practice.com

[Steps to Reproduce]
1. Navigate to the login page.
2. Enter registered test email "qa_intern@test.com" and password.
3. Click the "Sign In" button.

[Expected Result]
User is successfully authenticated and redirected to the Account Dashboard.

[Actual Result]
The application crashes with a blank white screen displaying: "500 Internal Server Error".
```

##  QA Sign-off & Hygiene
Demonstrated professional test communication by adding active status updates directly to core cards:
* Documented precise environment parameters and execution block summaries in core task history notes.
* Enforced strict testing hygiene by keeping core requirements blocked in the QA queue until formal verification sweeps passed.
