# GSoC Project Ideas

OpenGov Africa is preparing to apply as a **Google Summer of Code (GSoC) 2026 Mentoring Organization**.

This page presents a curated set of **mission-aligned, Africa-first proposed project ideas** that reflect OpenGov Africa’s core mandate:
**leveraging open data, open-source technologies, and civic innovation to strengthen transparency, accountability, and citizen participation across African governance systems.**

These ideas are intentionally grounded in **real political, social, and institutional realities on the continent**—from elections and public finance to civic space, protests, and digital rights.

Project ideas may evolve based on mentor input, contributor feedback, and feasibility discussions. Community members interested in mentoring are encouraged to propose refinements or entirely new ideas aligned with our mission.

The table below outlines **proposed GSoC 2026 project ideas** for OpenGov Africa.
All projects are aligned with our mission to advance **open governance, transparency, accountability, civic participation, and digital rights across Africa**.

---

## Accepted Project Ideas

These projects have a clearly defined scope and are suitable for a standard 12 week GSoC timeline. Each project includes starter tasks, documentation references, and clearly scoped deliverables. Contributors are encouraged to engage early with the community.

| Project Title | Category | Skills to Study / Improve | Short Description | Expected Outcomes / Deliverables (Final Done = Tool Usable) | Code Repository | Mentor(s) |
|--------------|----------|----------------------------|-------------------|--------------------------------------------------------------|-----------------|-----------|
| OGA Public Office Register (Citizens-in-Office Tracker) | Governance & Accountability | Web Development, Databases, Data Modeling, Research Automation | Build a transparent, verifiable system documenting public officials, offices held, tenure, and affiliations using open data, with strong provenance and data ethics. | • Application can be deployed by a new contributor using documented steps <br> • At least one African country’s public office data is fully ingested and browseable <br> • Users can view public officials, offices held, tenure dates, and affiliations end-to-end <br> • Every data point includes a clear source and audit trail <br> • Public read-only API endpoints return documented, valid responses <br> • Data model conforms to Popolo (Person, Organization, Post, Membership) <br> • Verified vs unverified data is clearly distinguished <br> • Core functionality is covered by basic automated tests <br> • Documentation explains data sources, limitations, and update workflow | [Project Repo](https://github.com/OpenGovAfrica/oga-public-office-register) | Tamara, & Bena - gsoc@opengovafrica.org |
| OGA Budget Lens (AI-Assisted Budget Document Parsing) | GovTech / AI | Python, NLP, Document Processing | Design an AI-assisted pipeline to extract, structure, and analyze data from complex and often unstructured African government budget documents. | • A user can run the full pipeline on a new budget PDF using documented commands <br> • OCR and extraction work on at least one real African budget document end-to-end <br> • Structured outputs are produced in machine-readable formats (CSV, JSON) <br> • The system does not fabricate amounts or line items beyond source documents <br> • A human-in-the-loop review interface allows correction and approval of extracted data <br> • Evaluation metrics (accuracy, completeness) are reported on sample documents <br> • Known limitations and failure modes are clearly documented <br> • Outputs are reusable by external analysis tools and researchers | [Project Repo](https://github.com/OpenGovAfrica/oga-budget-lens) | Tamara, & Bena - gsoc@opengovafrica.org  |
| OGA Local Service Atlas (Local Government Service Delivery Tracker) | Service Delivery / Civic Tech | Web Development, Databases, Data Collection | Create a platform to track local government service delivery (water, sanitation, health, education) using open datasets and community-reported inputs. | • Platform can be deployed by a new user using documented steps <br> • At least one locality is populated with real service delivery data <br> • Users can browse, search, and view services (e.g. health facilities, water points) <br> • An interactive map or dashboard accurately reflects stored data <br> • New data can be added through a documented ingestion or submission process <br> • Basic validation prevents clearly invalid or incomplete records <br> • Data sources and update cadence are clearly shown to users <br> • Contributor and user documentation enables ongoing maintenance | [Project Repo](https://github.com/OpenGovAfrica/oga-local-service-atlas) | Tamara & Bena - gsoc@opengovafrica.org |

---

## Draft Project Ideas

These ideas are accepted in principle but may evolve in scope. Contributors and mentors are encouraged to participate in discussions.

### 🧩 Example Idea 1 – Open Civic Data Dashboard
**Description:** Build a web dashboard to visualize civic datasets.
**Tech stack:** React, Node.js, D3.js
**Expected outcome:** Interactive charts showing government transparency metrics.
**Difficulty:** Medium
**Mentors:** To be assigned

---

### 🧩 Example Idea 2 – Documentation Automation Tool
**Description:** Script to automate generation of reports and documentation pages.
**Tech stack:** Python, Markdown, GitHub Actions
**Expected outcome:** Auto-updated docs with community metrics.
**Difficulty:** Medium
**Mentors:** To be assigned

---

| # | Project Title | Category | Skills to Study / Improve | Project Description | Potential Mentor(s) |
|---|--------------|----------|---------------------------|---------------------|---------------------|
| 1 | African Public Finance Transparency Portal | Open Data / Civic Tech | Python, Data Engineering, APIs, JavaScript, Open Data Standards | Build an open-source platform that aggregates, cleans, and visualizes public finance data (budgets, spending, procurement) across African countries to enable citizen oversight and accountability. | TBD |
| 2 | Citizens-in-Office Tracker | Governance & Accountability | Web Development, Databases, Data Modeling, Research Automation | Develop a transparent system to document public officials, offices held, tenure, and affiliations using verifiable open data sources, prioritizing data ethics and provenance. | Tamara & Bena - gsoc@opengovafrica.org |
| 3 | Protest, Civic Action & Civic Space Monitor | Civic Monitoring / Data Visualization | Python, Data Analysis, GIS, Frontend Visualization | Create a platform that aggregates and visualizes data on protests, civic actions, and civic space restrictions across Africa, supporting research, journalism, and advocacy. | TBD |
| 4 | Open Election Results & Integrity Dashboard | Democracy & Elections | Data Engineering, Web Development, UX/UI | Build a country-agnostic framework for publishing, auditing, and visualizing election results and electoral processes using open data to promote trust and transparency. | TBD |
| 5 | Government Commitments & Policy Tracking Tool | Policy Monitoring | Web Development, Databases, NLP (optional) | Develop a tool that tracks government promises, policy commitments, and development plans and maps them against timelines, outcomes, and publicly available evidence. | TBD |
| 6 | Open Data Quality & Readiness Scanner for African Governments | Open Data Infrastructure | Python, Web Scraping, APIs, Data Auditing | Create an automated scanner that evaluates the availability, quality, and usability of government open data portals and produces comparable readiness indicators. | TBD |
| 7 | Civic Education Through Data Platform | Civic Education / UX | Frontend Development, UX/UI, Data Storytelling | Design an interactive, beginner-friendly platform that explains African governance systems, public budgets, and citizen rights using data, visuals, and plain language. | TBD |
| 8 | Digital Rights & Surveillance Transparency Mapper | Digital Rights / Accountability | Research Automation, Data Visualization, Web Development | Build an open database documenting surveillance laws, internet shutdowns, biometric systems, and digital rights restrictions across African countries with strong citation standards. | TBD |
| 9 | AI-Assisted Budget Document Parsing | GovTech / AI | Python, NLP, Document Processing | Use AI-assisted techniques to parse, structure, and extract insights from complex and often unstructured African government budget documents. | Tamara & Bena - gsoc@opengovafrica.org |
| 10 | Local Government Service Delivery Tracker | Service Delivery / Civic Tech | Web Development, Databases, Data Collection | Build a platform that tracks service delivery at the local government level (water, sanitation, health, education) using open data and community-reported inputs. | Tamara & Bena - gsoc@opengovafrica.org |
| 11 | FOI & Access-to-Information Request Tracker | Transparency / Legal Tech | Web Development, Databases, Workflow Design | Create a system to track Freedom of Information and access-to-information requests, responses, and compliance across African jurisdictions. | TBD |
| 12 | Civic-Tech Toolkit for Grassroots Organizations | Capacity Building | Documentation, Web Development, UX | Develop an open-source toolkit that helps grassroots civic organizations adopt open data, digital security, and accountability tools. | TBD |

---

## Ongoing Discussion / Exploratory Ideas

| # | Project Title | Category | Description | Potential Mentor(s) |
|---|--------------|----------|-------------|---------------------|

---

## Proposing New Project Ideas

Community members and potential mentors are welcome to propose new ideas that:
- Align with OpenGov Africa’s mission
- Address real governance or accountability gaps
- Can be executed within a GSoC timeframe
- Are ethically grounded and politically aware

Project proposals should include:
- Problem statement
- Expected deliverables
- Required skills
- Mentorship availability

---

## Mentorship at OpenGov Africa

We value mentors who:
- Understand African political and civic realities
- Are committed to ethical open-source development
- Can guide contributors beyond just code, into context and impact

You do not need to be a “perfect” expert—commitment, clarity, and context-awareness matter more.

## Next Steps

- Interested mentors should signal interest and propose project ideas
- Contributors are encouraged to engage early with discussions and starter tasks
- Final project list will be published as part of our GSoC application

OpenGov Africa is building **for citizens, by citizens, with open technology**.
If this resonates with you, we invite you to help shape what comes next.


**Note:**
All projects are subject to refinement based on mentor availability, feasibility within the GSoC timeline, and community feedback. OpenGov Africa prioritizes ethical development, political context awareness, and citizen impact.
