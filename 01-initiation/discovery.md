# 🚀 Project Discovery Template

This document captures the key thinking needed to move from idea → scoping → budgeting.  
It defines the **problem**, **opportunity**, **users**, **constraints**, and **technical realities** before committing to delivery.

---

## 1. Project Definition

### 1.1 Vision Statement
> Describe the ideal future after this project succeeds.

**Example**:  
*"Enable researchers to instantly access cross-departmental knowledge without email requests or IT bottlenecks."*

### 1.2 Business Goals
> Clear, measurable outcomes that justify investing in this project.

**Example**:  
- Reduce internal research request turnaround from 5 days to 1 hour.
- Increase interdepartmental collaboration by 25% in one year.

### 1.3 Core Problem(s) We're Solving
> Be specific and name the real obstacles.

**Example**:  
- Knowledge locked inside PDFs and people's heads.
- Lack of structured access to past research.

### 1.4 Open Questions & Risks
> Known unknowns that could impact feasibility, budget, or timeline.

**Example**:  
- How easily can legacy documents be digitized?
- Will departments agree to share their knowledge bases?

---

## 2. Context and Inputs

### 2.1 Existing Assets and Sources
> What already exists that can be leveraged?

**Example**:
- 3 SharePoint archives
- Manual Excel lists
- Staff SME (subject matter expert) interviews

### 2.2 Structured vs Unstructured Data
> What formats are we dealing with?

| Type           | Examples                         |
|----------------|----------------------------------|
| Structured     | SQL databases, spreadsheets      |
| Semi-Structured| JSON APIs, SharePoint exports    |
| Unstructured   | PDFs, Emails, Word Docs          |

### 2.3 Critical External Factors
> Legal, regulatory, market trends, technical debt.

**Example**:
- GDPR compliance for all user data
- Upcoming system migration to Azure

---

## 3. User & Organizational Definition

### 3.1 Primary User Personas
> Who will actually use or depend on this solution?

**Template**:  
| Persona Name | Role | Pain Points | Success Looks Like |
|--------------|------|-------------|--------------------|
| Researcher Rachel | Researcher | Can't find old project data | Finds relevant past projects in 2 clicks |

### 3.2 Internal Stakeholders
> Decision-makers, blockers, key voices.

**Example**:
- Head of Research (sponsor)
- IT Team (gatekeepers for integrations)

### 3.3 Primary User Flows
> Core journeys we expect to support.

**Example**:
- Search knowledge base → Find report → Export/share result
- Upload new research data → Tag appropriately

---

## 4. Technical and Strategic Constraints

### 4.1 Tech Constraints
- Must integrate with existing Microsoft ecosystem (SharePoint, Teams)
- API-first backend preferred
- Mobile responsive frontend required

### 4.2 Strategic Constraints
- MVP must ship within 4 months
- Prefer open-source where possible to reduce license costs
- Must future-proof for multilingual support

---

## 5. Early Budget and Timeline Assumptions

### 5.1 Budget Range (Early Estimate)
> Based on initial complexity guess.

| Scope | Est. Range |
|-------|------------|
| Small MVP (basic search + upload) | €20k–30k |
| Full featured platform (search + upload + analytics + user management) | €40k–60k |

### 5.2 Delivery Timeline (Draft Phases)
> Approximate rough stages, for expectation setting.

| Phase                  | Duration | Notes                      |
|-------------------------|----------|----------------------------|
| Discovery & Prototyping | 4 weeks  | Workshops, wireframes      |
| MVP Build               | 8 weeks  | Dev + limited testing      |
| Beta Launch             | 2 weeks  | Internal users             |
| Full Launch             | +1 month | Public or org-wide release |

---

## 6. Next Steps Checklist
- [ ] Confirm core goals with client leadership
- [ ] Validate available data formats and volumes
- [ ] Identify critical legal/security risks
- [ ] Draft MVP scope statement

---

# 📣 Notes
- This is a *living document*: update as discoveries happen.
- Track all new open questions separately.
- Include decision dates and owners for major trade-offs.

---

## 🧠 Embedded Prompt (for reuse)
```
You are preparing a Discovery Document for a digital project designed to unlock structured knowledge across departments. Your audience is a medium-sized institution starting a knowledge management modernization process.

Focus on:
- Defining the vision and goals
- Identifying users, assets, and risks
- Clarifying technical and strategic constraints
- Drafting realistic early budget/timeline ranges

Write clearly, avoid jargon, and anticipate executive-level readers needing both strategic and technical clarity.
```
