# Sample RAID Log — Vendor Integration Project (Illustrative Example)

**Project:** Third-Party API Integration

**Last Updated:** 2026-07-27

> **Note:** This is an illustrative example for demonstration purposes only. It is not based on any specific client project or real engagement.

---

## Risks

| ID | Risk Description | Probability | Impact | Mitigation Strategy | Owner | Status |
|----|------------------|-------------|--------|----------------------|-------|--------|
| R-001 | Vendor API documentation delayed | Medium | High | Request draft docs early; identify alternative vendor | Procurement | Active |
| R-002 | Rate limiting affects production performance | Medium | High | Test rate limits in staging; negotiate higher limits | Tech Lead | Active |
| R-003 | Client feedback delayed due to timezone differences | Low | Medium | Set clear SLAs; sync at overlapping hours | PM | Monitoring |

---

## Assumptions

| ID | Assumption | Criticality | Validation Method | Status |
|----|------------|-------------|-------------------|--------|
| A-001 | Vendor will provide API keys on schedule | High | Confirmed with vendor PO | Pending |
| A-002 | Existing infrastructure supports new API | High | Run compatibility check | Validated |
| A-003 | Client has internal resources for acceptance testing | Medium | Confirm with client | Pending |

---

## Issues

| ID | Issue Description | Date Identified | Impact | Resolution Plan | Owner | Status |
|----|-------------------|-----------------|--------|------------------|-------|--------|
| I-001 | API rate limits lower than expected | 2026-07-20 | May impact production performance | Negotiate higher limits; implement caching | Lead Dev | In Progress |
| I-002 | Test environment unstable after deployment | 2026-07-25 | Delays QA validation | Roll back to stable version; investigate root cause | QA Lead | In Progress |
| I-003 | Stakeholder approval delayed due to unclear requirements | 2026-07-27 | May delay next Sprint | Share clarified requirements; align on Definition of Done | PM | Open |

---

## Dependencies

| ID | Dependency Description | Type | Owner | Status |
|----|-------------------------|------|-------|--------|
| D-001 | API documentation from Vendor X | External | PM | Pending |
| D-002 | Security review from compliance team | Internal | QA Lead | In Progress |
| D-003 | QA team availability for integration testing | Internal | PM | Resolved |