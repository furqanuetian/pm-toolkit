# Definition of Done Checklist — Embedded/Firmware Sprints

**Purpose:** Ensure every Increment meets quality standards for embedded systems development.

---

## DoD Checklist (All Items Must Be Completed)

- [ ] **Code** is reviewed by at least one peer
- [ ] **Unit tests** pass (coverage ≥ 80%)
- [ ] **Integration tests** pass on target hardware
- [ ] **HiL (Hardware-in-the-Loop)** tests pass
- [ ] **Firmware** is deployed to staging hardware
- [ ] **Documentation** is updated (code comments, user guide)
- [ ] **Requirements** are verified and traceable
- [ ] **Security** review passed (if applicable)
- [ ] **Performance** metrics meet baseline
- [ ] **No regression** introduced in existing functionality

---

## Hardware-Specific Checks

- [ ] **Hardware version** matches firmware requirements
- [ ] **Communication** works end-to-end
- [ ] **Power consumption** within acceptable limits
- [ ] **Boot time** meets requirements
- [ ] **OTA (Over-the-Air)** update tested

---

## Quality Gates

| Gate | Owner | Frequency |
|------|-------|-----------|
| Code review | Developers | Per PR |
| Unit tests | Developers | Per commit |
| Integration tests | QA | Per Sprint |
| HiL tests | Test Engineer | Per Sprint |

---

## DoD Evolution

The DoD is reviewed and adapted during each **Sprint Retrospective** based on:

- Escaped defects (quality issues found after release)
- New tools or infrastructure that enable better testing
- Organizational standards or compliance requirements