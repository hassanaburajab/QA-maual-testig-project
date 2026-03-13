# 🍊 OrangeHRM Functional Testing Project

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Test Cases](https://img.shields.io/badge/Test%20Cases-152-blue)
![Modules](https://img.shields.io/badge/Modules-8-green)
![Phase](https://img.shields.io/badge/Phase-5%20%E2%80%93%20Test%20Summary-brightgreen)

> Functional testing project for [OrangeHRM Live Demo](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login) — covering ESS User and Admin modules across 8 functional areas.

---

## 👥 Team

| Name | Role |
|---|---|
| Mamoun Suboh | Project Manager |
| Afnan Kharoof | QA Lead |
| Abdullah Muhaisen | QA Engineer |
| Abdulhakeem Sakhel | QA Engineer |
| Qusay Terawi | QA Engineer |
| Hasan Aburajab | QA Engineer |

---

## 🔗 Project Links

| Tool | Link |
|---|---|
| 🐛 Jira Board | [OrangeHRM_Functional_Testing – Jira](https://twitchsak3r.atlassian.net/jira/software/projects/SAKER/summary?atlOrigin=eyJpIjoiZWQ4MDU4NDJkYTNmNDY4N2IxMTI1NzY0YmMzZDE4ZTUiLCJwIjoiaiJ9) |
| 🧪 Zephyr Test Cycle | [Zephyr Essential – Test Cycle](https://twitchsak3r.atlassian.net/projects/SAKER?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.thed.zephyr.je__main-project-page#!/v2/testCases?projectId=10066) |
| 📋 Jira Sprint | [Sprint 1 – OrangeHRM Functional Testing](https://twitchsak3r.atlassian.net/jira/software/projects/SAKER/boards/34/backlog) |
| 🌐 Application Under Test | [opensource-demo.orangehrmlive.com](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login) |


---

## 🌍 Test Environment

| Property | Value |
|---|---|
| Platform | Web |
| OS | Windows 10 |
| Browsers | Chrome (latest), Firefox (latest), Edge (latest) |
| Admin Credentials | `Admin` / `admin123` |
| ESS Credentials | `John Doe` / `John@123` |

---

## 📁 Repository Structure

```
OrangeHRM-Functional-Testing/
│
├── 📄 README.md                        ← You are here
├── 📄 Test_Plan.pdf                    ← Full test plan document
├── 📄 SRS.pdf                          ← Software Requirements Specification
│
├── 📂 Test_Cases/
│   ├── Test_Cases_for_OrangeHRM.xlsx   ← Master test cases file (all 8 modules)
│   ├── 3_ESS_User_Login.csv
│   ├── 3.1_Personal_Details.csv
│   ├── 3.2_Job_Info.csv
│   ├── 3.3_Qualifications.csv
│   ├── 4.1_User_Management.csv
│   ├── 4.2_Job_Configuration.csv
│   ├── 4.3_Organization.csv
│   └── 4.4_Admin_Qualifications.csv
│
├── 📂 Bug_Reports/
│   └── Bug_Report.pdf                  ← Completed
│
├── 📂 RTM/
│   └── RTM.xlsx                        ← Requirements Traceability Matrix
│
└── 📂 Test_Summary/
    └── Test_Summary_Report.pdf         ← Completed
```

---

## 🗂️ Project Phases

### ✅ Phase 1 — Requirements Analysis
- Read and analyzed the SRS document
- Identified all functional modules in scope
- Created Jira board: `OrangeHRM - Functional Testing`
- Board columns: `To Do` → `In Progress` → `Blocked` → `Testing` → `Done`

---

### ✅ Phase 2 — Test Plan
- Defined test objectives, scope, approach, schedule, and risks
- Documented roles & responsibilities for all team members
- Set entry/exit criteria for test execution

📎 [`Test_Plan.pdf`](./Test%20Plan.pdf)

**Schedule:**

| Task | Duration | Start | End |
|---|---|---|---|
| Test Case Design | 2 Days | 09-Mar-26 | 10-Mar-26 |
| Test Data Preparation | 1 Day | 09-Mar-26 | 09-Mar-26 |
| Test Execution | 2 Days | 10-Mar-26 | 11-Mar-26 |
| Bug Report | 1 Day | 11-Mar-26 | 11-Mar-26 |
| RTM | 1 Day | 11-Mar-26 | 11-Mar-26 |
| Test Summary Report | 1 Day | 12-Mar-26 | 12-Mar-26 |

---

### ✅ Phase 3 — Test Cases Design
- Designed **152 test cases** across 8 modules
- Followed standard template: ID, Summary, Preconditions, Test Data, Steps, Expected Result
- Uploaded all test cases to **Zephyr Essential** in Jira

📎 [`Test_Cases_for_OrangeHRM.xlsx`](./Test_Cases/Test_Cases_for_OrangeHRM.xlsx)

**Coverage:**

| Module | Req. ID | Test Cases |
|---|---|---|
| ESS User Login | 3 | 10 |
| Personal Details | 3.1 | 34 |
| Job Info | 3.2 | 8 |
| Qualifications (ESS) | 3.3 | 23 |
| User Management | 4.1 | 21 |
| Job Configuration & Management | 4.2 | 21 |
| Organization | 4.3 | 19 |
| Admin Qualifications | 4.4 | 16 |
| **Total** | | **152** |

---

### ✅ Phase 4 — Test Execution
- Executed all 152 test cases in **Zephyr Essential**
- Logged bugs in **Jira** and linked them to failed test cases
- Tracked execution progress via Jira Sprint Board

**Deliverables:**
- 📄 Bug Report — [`Bug_Reports/Bug_Report.pdf`](./Bug_Reports/Bug_Report.pdf) ✅
- 📄 📊 RTM — [`RTM/RTM.xlsx`](./RTM/RTM.xlsx) ✅

---

### ✅ Phase 5 — Test Summary
- Final test summary report generated after full execution

📎 [`Test_Summary/Test_Summary_Report.pdf`](./Test_Summary/Test_Summary_Report.pdf) ✅

---

## 📋 In Scope

**My Info Module (ESS View)**
- Personal Details, Photograph, Contact Details, Emergency Contacts, Dependents
- Immigration, Job (view only), Salary (hidden from ESS), Report To, Qualifications, Membership

**Admin Module**
- User Management: Create, edit, delete, search users, assign roles, enable/disable accounts
- Job Module: Job Titles, Pay Grades, Employment Status, Job Categories, Work Shifts
- Organization Module: General Information, Locations, Structure
- Qualifications Configuration: Skills, Education, License Types, Languages, Memberships

## 🚫 Out of Scope
- UI / visual design and layout testing
- API testing
- Performance and load testing
- Backup and recovery testing
- Localization and language settings
- Database testing
  
---

## 🐛 Bug Tracking

All bugs found during execution are logged in **Jira** and linked to their corresponding test case in Zephyr.

Bug severity levels used:

| Severity | Description |
|---|---|
| 🔴 Critical | System crash or complete feature failure |
| 🟠 Major | Feature broken but workaround exists |
| 🟡 Minor | Minor issue, low impact |
| 🟢 Trivial | Cosmetic or very low priority |

---

## ⚠️ Risks & Mitigations

| Risk | Mitigation |
|---|---|
| Requirements not clearly defined | Re-review SRS, raise to QA Lead or PM |
| Demo environment instability / data resets | Record evidence immediately, re-create test data each session |
| Shared environment — data from other testers | Use unique identifiable test data names |
| Incomplete coverage due to time constraints | Prioritize critical and high-severity test cases first |
