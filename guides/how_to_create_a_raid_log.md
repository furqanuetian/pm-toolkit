# How to Create a RAID Log

**Purpose:** A step-by-step guide to building and maintaining a RAID log for your project.

---

## What Is a RAID Log?

A RAID log is a simple but powerful tool for tracking:
- **R**isks — potential future problems
- **A**ssumptions — things you believe to be true
- **I**ssues — current problems
- **D**ependencies — things you rely on from others

---

## Why Use a RAID Log?

- **Visibility** — everyone sees what could go wrong
- **Accountability** — owners are assigned to every item
- **Proactive management** — risks are addressed before they become issues
- **Transparency** — no surprises for stakeholders

---

## Step 1: Set Up Your Log

Create a table with columns for each category:

| ID | Risk Description | Probability | Impact | Mitigation | Owner | Status |
|----|------------------|-------------|--------|------------|-------|--------|

Repeat for Assumptions, Issues, and Dependencies.

---

## Step 2: Identify Risks

**Ask:**
- What could go wrong?
- What has gone wrong on similar projects?
- What keeps me up at night?

**Example:**
- *"Vendor API documentation might be delayed"*
- *"Key developer might leave the project"*
- *"Integration with legacy system might fail"*

---

## Step 3: Identify Assumptions

**Ask:**
- What are we assuming to be true?
- What do we believe without proof?

**Example:**
- *"Vendor will deliver on time"*
- *"Client will provide feedback within 48 hours"*
- *"Existing infrastructure is compatible with new integration"*

---

## Step 4: Identify Issues

**Ask:**
- What is blocking us right now?
- What needs immediate attention?

**Example:**
- *"Vendor API rate limits are lower than expected"*
- *"Test environment is unstable"*
- *"Stakeholder approval is delayed"*

---

## Step 5: Identify Dependencies

**Ask:**
- Who depends on us?
- Who do we depend on?

**Example:**
- *"We need API documentation from Vendor X"*
- *"QA team depends on us to deliver by Friday"*
- *"We depend on hardware delivery for testing"*

---

## Step 6: Assign Owners

Every item needs an owner:
- **Risks** — someone who monitors and mitigates
- **Assumptions** — someone who validates
- **Issues** — someone who resolves
- **Dependencies** — someone who manages the relationship

---

## Step 7: Review Regularly

- **Weekly** — review in team sync
- **Sprint Review** — share with stakeholders
- **Whenever something changes** — update immediately

---

## Example RAID Log Structure

| ID | Category | Description | Owner | Status |
|----|----------|-------------|-------|--------|
| R-001 | Risk | Hardware delivery delay | Procurement | Active |
| A-001 | Assumption | Vendor will deliver on time | PM | Pending validation |
| I-001 | Issue | API rate limits lower than expected | Lead Dev | In progress |
| D-001 | Dependency | API docs from Vendor X | PM | Open |