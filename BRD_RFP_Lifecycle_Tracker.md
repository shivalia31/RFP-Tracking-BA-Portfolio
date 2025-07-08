# 📄 BRD: RFP Lifecycle Tracker – Business Analyst Portfolio Project

---

## 1. Project Title
**RFP Lifecycle Tracker** – JIRA & Power BI Integrated Workflow for Proposal Management

---

## 2. Background
Organizations dealing with high volumes of Requests for Proposals (RFPs) often face inefficiencies in tracking, prioritizing, and responding to them. This project simulates the RFP process from intake to submission and reporting using a structured backlog (JIRA-style) and a Power BI dashboard for visualization and insights.

---

## 3. Business Objective
To create a centralized and efficient system for managing RFPs across various departments (Sales, Business Analysis, Technical, Design, and Proposal Management), while enabling real-time performance tracking and data-driven decision-making.

---

## 4. Scope

**In Scope**:
- Creating and managing user stories representing RFP lifecycle stages
- Simulating workflows and statuses (To Do, In Progress, Review, Done)
- Tracking task attributes like priority, story points, created/resolution dates
- Visualizing key performance indicators (KPIs) and trends in Power BI

**Out of Scope**:
- Integration with actual JIRA software
- External client or tool-based submission mechanisms

---

## 5. Stakeholders

| Role             | Stakeholder     | Responsibility                                      |
|------------------|------------------|------------------------------------------------------|
| Business Analyst | Myself           | Requirement gathering, documentation, dashboard creation |
| Sales Team       | Simulated        | Initiate RFP requests                                |
| Technical Team   | Simulated        | Provide solution architecture                        |
| Proposal Manager | Simulated        | Review and finalize submission                       |
| Designer         | Simulated        | Prepare diagrams and visuals                         |

---

## 6. Requirements

### 📝 Functional Requirements

| ID  | Description                                                    | Priority |
|-----|----------------------------------------------------------------|----------|
| FR1 | System must allow users to log new RFPs                        | High     |
| FR2 | BA should assign story points and assignees                    | High     |
| FR3 | Each RFP should pass through various statuses (To Do → Done)   | High     |
| FR4 | System must capture Created Date and Resolution Date           | High     |
| FR5 | Dashboard should show RFPs by status, assignee, epic           | High     |
| FR6 | Dashboard should calculate average turnaround time             | Medium   |
| FR7 | Dashboard should allow filtering by assignee, epic, date       | Medium   |

### 🔒 Non-Functional Requirements

| ID   | Description                                         | Priority |
|------|-----------------------------------------------------|----------|
| NFR1 | Data must be structured and reusable (Excel format) | High     |
| NFR2 | Dashboard should load in under 5 seconds            | Medium   |

---

## 7. Assumptions
- All user stories are tracked manually (not synced with actual JIRA)
- Resolution dates are simulated for demo purposes
- The dashboard will be shared via `.pbix` or screenshots

---

## 8. Success Criteria
- A fully functional and visually informative Power BI dashboard
- Complete JIRA-style backlog in Excel with clean fields
- Documentation of process, requirements, and visuals

---

## 9. Deliverables
- `RFP_JIRA_Portfolio_Final.xlsx` (backlog)
- `RFP_Dashboard.pbix` (Power BI file)
- `README.md` (project overview)
- `BRD_RFP_Lifecycle_Tracker.md`

---

## 10. Timeline

| Phase                  | Timeline   |
|------------------------|------------|
| Backlog & Planning     | Day 1 – 2  |
| Power BI Dashboard     | Day 3 – 4  |
| Documentation & Upload | Day 5      |
