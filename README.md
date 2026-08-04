# PM Toolkit — Furqan Rehmat

A curated collection of practical templates, checklists, and guides for Technical Project Managers delivering embedded systems, industrial software, and complex engineering projects.

---

## 🎯 Purpose

This toolkit is designed to help Technical Project Managers:

- **Initiate projects with confidence** — project charters, kickoff checklists, and stakeholder alignment
- **Track risks and dependencies** — RAID logs and requirements traceability
- **Run effective Agile ceremonies** — Sprint Planning templates aligned with the Scrum Guide
- **Maintain delivery quality** — Definition of Done checklists for embedded systems
- **Close knowledge gaps** — practical guides and real-world examples

---

## 🎯 Design Principles

Every template in this repository is designed to be:

- **Lightweight** — practical enough for day-to-day project delivery.
- **Vendor-neutral** — adaptable to Jira, Azure DevOps, GitHub, Notion, or Confluence.
- **Engineering-focused** — created for embedded systems, industrial software, and technical product teams.
- **Traceable** — designed to link naturally with related governance artifacts such as RAID Logs, Decision Logs, Change Requests, and Requirements Traceability Matrices.
- **Reusable** — written in Markdown for easy version control and customization.

---

## 🧭 Toolkit Coverage

```text
Initiation
 ├─ Project Charter
 ├─ Stakeholder Register
 └─ Kickoff Checklist

Planning & Governance
 ├─ Sprint Planning
 ├─ Communication Plan
 ├─ Decision Log
 ├─ Change Request Log
 └─ Requirements Traceability

Execution
 ├─ Definition of Done
 └─ RAID Log

Closure
 └─ (Coming Soon)
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
│   ├── decision_log.md
│   ├── change_request_log.md
│   ├── sprint_planning_agenda.md
│   ├── requirements_traceability_matrix.md
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
| **Sprint Planning Agenda** | Facilitate Scrum-compliant Sprint Planning focused on the Sprint Goal and Sprint Backlog. |
| **Communication Plan** | Define how project information will be shared, with whom, and at what frequency. |
| **Requirements Traceability Matrix** | Verify that every requirement is implemented, tested, and traceable. |
| **Decision Log** | Track key project decisions, including context, rationale, and outcomes. |
| **Change Request Log** | Track requested changes to scope, schedule, budget, or deliverables, and document their evaluation and approval. |

### Execution
| Template | Purpose |
|----------|---------|
| **Definition of Done Checklist (Embedded)** | Maintain consistent quality standards for embedded and firmware development. |
| **RAID Log Template** | Track Risks, Assumptions, Issues, and Dependencies throughout the project lifecycle. |

---

## 📖 Guides & Examples

| Resource | Purpose |
|----------|---------|
| **How to Create a RAID Log** | Step-by-step guide for creating and maintaining an effective RAID log. |
| **Sample RAID Log** | Illustrative example showing how RAID items are documented in practice. |

---

## 📌 Real-World Context

These templates are grounded in delivery work on embedded systems and industrial software for US-based clients. A few examples:

- **Project Charter** — developed to provide a lightweight project authorization artifact that aligns business objectives, scope, stakeholders, and governance while remaining practical for technical delivery teams.

- **Stakeholder Register** — created to provide a practical framework for identifying stakeholders, understanding their influence and interest, and planning targeted engagement strategies that keep projects aligned with organizational priorities.

- **Communication Plan** — designed to establish clear communication channels, reporting cadences, and escalation paths that keep teams aligned and stakeholders informed throughout the project lifecycle.

- **Decision Log** — developed to provide a lightweight audit trail for significant project decisions, capturing context, alternatives, rationale, and traceability to other governance artifacts.

- **Change Request Log** — created to manage scope, schedule, and budget changes systematically, ensuring that every change is evaluated for impact, approved by the right authority, and traced back to governance decisions.

- **RAID Log Template** — informed by a case where NFC integration failures stalled a Hardware-in-the-Loop (HiL) test suite for three weeks due to a mismatch between legacy hardware and updated firmware protocols. Resolving it required a cross-team investigation, coordinated hardware procurement, and a clean code commit.

- **Requirements Traceability Matrix** — informed by a case where a client pushed to start development on incomplete requirements. A data-backed gap analysis exposed undefined communication protocols and missing payload specifications before they caused rework, preventing roughly two weeks of inefficient work while maintaining safety compliance.

- **Definition of Done Checklist** — informed by a case where an automated V&V test suite had fallen behind the main development branch, threatening a compliance milestone. A reverse-merge strategy resolved the issue without touching production code, avoiding an estimated 15-day schedule slip.

- **Sprint Planning Agenda** — built around the Scrum Guide's three topics (Why, What, and How) and the accountabilities they define, refined while preparing for the PSM I certification.

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

Future additions may include:

- [x] Stakeholder Register
- [x] Communication Plan
- [x] Decision Log
- [x] Change Request Log
- [ ] Resource Plan
- [ ] Lessons Learned Register
- [ ] Project Closure Report
- [ ] Embedded-specific templates (Release Readiness, Technical Debt Register, Integration Readiness, etc.)

---

## 📬 Connect with Me

- [GitHub](https://github.com/furqanuetian)
- [Notion Portfolio](https://glow-potential-c65.notion.site/Furqan-Rehmat-Portfolio-3873d6c3ef738044a9f0ddf11ce00c48)

---

## 📄 License

MIT — use freely, credit where possible.

---

*Built by a PM, for PMs.*