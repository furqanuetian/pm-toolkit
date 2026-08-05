# PM Toolkit — Furqan Rehmat

**A curated collection of lightweight, engineering-focused templates, checklists, and practical guides for Technical Project Managers delivering embedded systems, industrial software, and complex engineering projects.**

All templates are written in Markdown, version-control friendly, and designed to be copied, customized, and used immediately.

---

## 🎯 Purpose

This toolkit is designed to help Technical Project Managers:

- **Initiate projects with confidence** — project charters, kickoff checklists, and stakeholder alignment
- **Track risks and dependencies** — RAID logs and requirements traceability
- **Run effective Agile ceremonies** — Sprint Planning templates aligned with the Scrum Guide
- **Maintain delivery quality** — Definition of Done checklists for embedded systems
- **Close projects effectively** — closure reports, lessons learned, and handover checklists

---

## ⚙️ Design Principles

Every template in this repository is designed to be:

- **Lightweight** — practical enough for day-to-day project delivery.
- **Vendor-neutral** — adaptable to Jira, Azure DevOps, GitHub, Notion, or Confluence.
- **Engineering-focused** — created for embedded systems, industrial software, and technical product teams.
- **Traceable** — designed to link naturally with related governance artifacts such as RAID Logs, Decision Logs, Change Requests, and Requirements Traceability Matrices.
- **Reusable** — written in Markdown for easy version control and customization.

Together, these principles balance practicality with disciplined project governance.

---

## 📦 What's Included

```text
Initiation
 ├─ Project Charter
 ├─ Stakeholder Register
 └─ Kickoff Checklist

Planning & Governance
 ├─ Communication Plan
 ├─ Resource Plan
 ├─ Sprint Planning
 ├─ Requirements Traceability
 ├─ Decision Log
 └─ Change Request Log

Execution
 ├─ Project Dashboard
 ├─ Definition of Done
 └─ RAID Log

Closure
 ├─ Lessons Learned Register
 └─ Project Closure Report
```

---

## 🔄 How the Templates Work Together

```text
Initiation
   │
   ▼
Planning
   │
   ▼
Execution
   │
   ├── Project Dashboard
   ├── Decision Log
   ├── RAID Log
   ├── Change Request Log
   └── Requirements Traceability
   │
   ▼
Lessons Learned Register
   │
   ▼
Project Closure Report
```

---

## 📂 Repository Structure

```text
pm-toolkit/
├── README.md
├── templates/
│   ├── project_charter.md
│   ├── stakeholder_register.md
│   ├── project_kickoff_checklist.md
│   ├── communication_plan.md
│   ├── resource_plan.md
│   ├── sprint_planning_agenda.md
│   ├── requirements_traceability_matrix.md
│   ├── decision_log.md
│   ├── change_request_log.md
│   ├── project_dashboard.md
│   ├── lessons_learned_register.md
│   ├── project_closure_report.md
│   ├── definition_of_done_checklist_embedded.md
│   └── raid_log_template.md
├── guides/
│   └── how_to_create_a_raid_log.md
└── examples/
    └── sample_raid_log.md
```

*(Only files that exist in this repository are listed above — this list is updated as new templates are added.)*

---

## 📋 Available Templates

### Initiation
| Template | Purpose |
|----------|---------|
| **Project Charter** | Formally authorize projects, define objectives, scope, stakeholders, constraints, and success criteria. |
| **Stakeholder Register** | Identify stakeholders, assess their influence, and define how to engage them. |
| **Project Kickoff Checklist** | Ensure every project starts with clear alignment, defined responsibilities, and agreed next steps. |

### Planning & Governance
| Template | Purpose |
|----------|---------|
| **Communication Plan** | Define how project information will be shared, with whom, and at what frequency. |
| **Resource Plan** | Identify team roles, required skills, allocation, and capacity constraints. |
| **Sprint Planning Agenda** | Facilitate Scrum-compliant Sprint Planning focused on the Sprint Goal and Sprint Backlog. |
| **Requirements Traceability Matrix** | Verify that every requirement is implemented, tested, and traceable. |
| **Decision Log** | Track key project decisions, including context, rationale, and outcomes. |
| **Change Request Log** | Track requested changes to scope, schedule, budget, or deliverables, and document their evaluation and approval. |

### Execution
| Template | Purpose |
|----------|---------|
| **Project Dashboard** | Single-page view of project health, delivery metrics, risks, and blockers. |
| **Definition of Done Checklist (Embedded)** | Maintain consistent quality standards for embedded and firmware development. |
| **RAID Log Template** | Track Risks, Assumptions, Issues, and Dependencies throughout the project lifecycle. |

### Closure
| Template | Purpose |
|----------|---------|
| **Lessons Learned Register** | Capture, track, and apply lessons from project experiences to improve future project delivery. |
| **Project Closure Report** | Document project outcomes, confirm completion, capture lessons learned, and formally close the project. |

---

## 📖 Guides & Examples

| Resource | Purpose |
|----------|---------|
| **How to Create a RAID Log** | Step-by-step guide for creating and maintaining an effective RAID log. |
| **Sample RAID Log** | Illustrative example showing how RAID items are documented in practice. |

---

## 📌 Why These Templates Exist

These templates are grounded in delivery work on embedded systems and industrial software for US-based clients. A few examples:

- **Project Charter** — Lightweight project authorization that aligns objectives, scope, and governance without bureaucracy.

- **Stakeholder Register** — Practical framework for identifying stakeholders, understanding their influence, and planning targeted engagement.

- **Communication Plan** — Clear communication channels, reporting cadences, and escalation paths.

- **Resource Plan** — Helps identify capacity constraints, skill gaps, and resource dependencies before they affect delivery.

- **Decision Log** — Lightweight audit trail for significant project decisions with context, alternatives, and rationale.

- **Change Request Log** — Systematic management of scope, schedule, and budget changes with impact evaluation and approval tracking.

- **Project Dashboard** — Single-page view for tracking blockers, delivery metrics, and project health — directly reflecting the dashboard redesign that reduced blocker resolution time by 66%.

- **Lessons Learned Register** — Continuous capture of observations and lessons to improve future project delivery.

- **Project Closure Report** — Structured closure that documents outcomes, captures lessons, and formalizes project completion.

- **RAID Log** — Informed by a case where NFC integration failures stalled a Hardware-in-the-Loop (HiL) test suite for three weeks due to a mismatch between legacy hardware and updated firmware protocols.

- **Requirements Traceability Matrix** — Informed by a case where a data-backed gap analysis exposed undefined communication protocols and missing payload specifications before they caused rework.

- **Definition of Done Checklist** — Informed by a case where a reverse-merge strategy resolved a V&V test suite issue without touching production code, avoiding an estimated 15-day schedule slip.

- **Sprint Planning Agenda** — Built around the Scrum Guide's three topics (Why, What, and How), refined while preparing for the PSM I certification.

**Read the complete project case studies in my [Notion Portfolio](https://glow-potential-c65.notion.site/Furqan-Rehmat-Portfolio-3873d6c3ef738044a9f0ddf11ce00c48).**

---

## 🚀 How to Use This Toolkit

1. Browse the templates, guides, and examples.
2. Copy the Markdown file you need.
3. Adapt it to your project or organization.
4. Integrate it into GitHub, Notion, Confluence, or your preferred documentation platform.
5. Share feedback or improvements via GitHub Issues.

---

## 🤝 Contributing

Found a bug or have a template to share?

1. Open an [Issue](https://github.com/furqanuetian/pm-toolkit/issues) to discuss your suggestion
2. Submit a Pull Request with your changes
3. Follow the existing template structure and formatting

All contributions are welcome — especially templates grounded in real-world technical project experience.

---

## 🛠️ Why I Built This

Many publicly available project management templates are either too generic for engineering teams or too heavyweight for day-to-day delivery. This toolkit focuses on lightweight, reusable artifacts that balance governance with practicality for embedded systems and industrial software projects.

This repository complements my [PSM I Study Repository](https://github.com/furqanuetian/psm1-study-guide) and will continue to grow with additional templates and guides.

---

## 🗺️ Roadmap

Planned additions:

- [ ] Release Readiness Checklist
- [ ] Technical Debt Register
- [ ] Integration Readiness Checklist
- [ ] Risk Response Plan

---

## 📬 Connect with Me

- [GitHub](https://github.com/furqanuetian)
- [Notion Portfolio](https://glow-potential-c65.notion.site/Furqan-Rehmat-Portfolio-3873d6c3ef738044a9f0ddf11ce00c48)

---

## 📄 License

MIT — use freely, credit where possible.

---

*Built by a PM, for PMs.*