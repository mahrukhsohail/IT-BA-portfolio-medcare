# MedCare Patient Portal — BA Portfolio Project

> **Simulated case study** | Business Requirements Document · User Stories · Process Flow  
> Role: Independent Business Analyst | Domain: HealthTech | March 2026

---

## What this project is

A business analysis simulation for **MedCare Regional Health System (MRHS)** — a fictional nonprofit healthcare network serving 450,000 patients.

The project addresses a real-world problem pattern: low patient portal adoption driving unsustainable call centre volume, combined with a regulatory compliance deadline (U.S. 21st Century Cures Act).

This is a portfolio artifact demonstrating end-to-end BA practice — from problem framing to structured requirements to testable user stories.

---

## Business problem (in plain English)

- Only **18% of patients** actively use the existing patient portal (built 2011)
- The remaining 82% call the clinic — generating **4,200 inbound calls per day**
- Average wait time to receive a lab result by phone: **17+ minutes**
- Regulatory deadline: same-day electronic access to patient records required by Q4 2026

**Goal:** Replace the legacy portal with a HIPAA-compliant, Epic-integrated patient portal that patients actually use.

---

## What I produced

| Artifact | Description | Tool |
|---|---|---|
| Business Requirements Document (BRD) | Problem statement, stakeholder register, 5 business requirements (MoSCoW), KPIs, constraints, scope | Google Docs → exported .docx |
| User Stories (3) | Patient-facing stories with GIVEN-WHEN-THEN acceptance criteria, sprint assignment, story points | Structured for Jira |
| AS-IS / TO-BE Swimlane | Process flow showing current manual state vs future portal state across 3 swim lanes | draw.io |

---

## Artifacts

- [`MedCare_BRD_UserStories_v1.0.docx`](./MedCare_BRD_UserStories_v1.0.docx) — Full BRD and User Stories document
- [`AS_IS_TO_BE_Swimlane.png`](./MedCare_AS-IS_TO-BE_swimlane.svg) — Process flow diagram *(screenshot from draw.io)*

---

## Key decisions I made as BA

**Why these 5 requirements?**  
I prioritised based on two filters: (1) what is legally mandated — the 21st Century Cures Act forced lab result access as a hard MUST; (2) what drives the biggest measurable pain — appointment booking and secure messaging directly reduce the 4,200 daily calls.

**Why MoSCoW over a simple list?**  
Stakeholders need to understand trade-offs when scope is challenged. MoSCoW makes that conversation explicit — mobile app and pharmacy integration were consciously moved to Phase 2, not forgotten.

**Why GIVEN-WHEN-THEN acceptance criteria?**  
It removes ambiguity between BA, developer, and QA. "The system shall display results" is untestable. "GIVEN I am logged in, WHEN I navigate to Lab Results, THEN I see results sorted most recent first" is a pass/fail test. That precision reduces rework.

---

## Stakeholders mapped

| Stakeholder | Role | Influence | Interest |
|---|---|---|---|
| Dr. Angela Wei (CMIO) | Sponsor | Very High | High |
| Patients (450,000) | Primary users | Low | Very High |
| IT / Epic Admins | Integration | High | Medium |
| Legal & Compliance | Regulatory | High | High |
| Call Centre Team | Process impacted | Low | High |

---

## Tools used / referenced

| Phase | Tool |
|---|---|
| Documentation | Google Docs, Microsoft Word |
| Process modelling | draw.io |
| User story management | Jira (format-ready) |
| Collaboration | Google Drive, SharePoint (real project) |
| Reporting | Confluence (real project) |

---

## About this project

This is a self-initiated portfolio project completed as part of my transition into a Junior Business Analyst role in the Netherlands. All company names, data, and scenarios are fictional and created for learning and demonstration purposes.

**Background:** MSc IT Project Management · Experience in project coordination and requirements elicitation · Currently based in Zwolle, NL

---

*Portfolio project by Mahrukh Sohail| (https://www.linkedin.com/in/mahrukh-sohail) | March 2026*
