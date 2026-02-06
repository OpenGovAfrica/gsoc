### OpenGov Africa GSoC 2026 Project Standards and Contributor Requirements

All work must adhere to the following standards to ensure long-term maintainability. 

### Collaboration vs. Individual Evaluation

It is important to clarify a core Google Summer of Code (GSoC) rule: GSoC is an individual program. While you are encouraged to collaborate with the community, help peers troubleshoot, and share knowledge during the application and bonding periods, your final project proposal and the code you submit for your project must be your own individual work. GSoC does not accept team applications or group projects for a single stipend slot. Mentors need to see your individual technical capability to select you for a slot. For **all tasks listed till "Phase 0"** we highly encourage you to collaborate with each other as you will definitely learn faster. Use Phase 0 as an opportunity to show you can lead and set up a project independently, even if you are discussing high-level logic with other potential contributors in public channels. 

### 1. Technical Documentation

Every project must maintain these three core files in the repository root:

* **README.md**: Includes project vision, visual UI mockups, and a "Quick Start" guide for local setup in under 5 minutes.
* **ARCHITECTURE.md**: Explains the tech stack choices, data flow diagrams, and the relationship between different services (e.g., frontend, backend, database).
* **CONTRIBUTING.md**: Guidelines for environment setup, branching strategy, and pull request (PR) requirements.

### 2. Code Quality and Automation

Contributors must implement automated checks to ensure code health from the first commit.

| Category | Tooling | Requirement |
| :--- | :--- | :--- |
| **Linting** | Ruff (Python) / ESLint (JS) | Zero linting errors allowed in the main branch. |
| **Formatting** | Black (Python) / Prettier (JS) | Consistent code style enforced via pre-commit hooks. |
| **Testing** | PyTest / Jest | Minimum **70% code coverage** for all business logic. |
| **Version Control** | Git | Use [Conventional Commits](https://www.conventionalcommits.org/) (e.g., `feat:`, `fix:`, `docs:`). |

### 3. API and Data Standards

To ensure our data is useful to the broader civic tech ecosystem, you must follow these specs:

* **Self-Documenting APIs**: All backend routes must be documented using **OpenAPI/Swagger** (accessible via `/docs`).
* **Standard Schemas**:
    * **Citizens Tracker**: Must follow the [Popolo Specification](http://www.popoloproject.com/).
    * **Budget Parser**: Must output data in validated JSON or UTF-8 CSV.
    * **Service Tracker**: Must use **GeoJSON** for all spatial data points.
* **Provenance**: Every data entry must include a `source_url` or `evidence_ref` field to ensure data ethics and auditability.

### 4. Communication and Workflow

* **Public Development**: All work must be performed in public branches. Open a Draft PR early to get feedback on your architectural approach.
* **Issue Linking**: Every Pull Request must be linked to a specific GitHub Issue (e.g., Closes #12).
* **Weekly Sync**: Provide a written update every Friday covering:
* Achievements this week.
* Current blockers or technical challenges.
* Planned tasks for the following week.

### 5. Final Handover Deliverables

The project is considered complete only when the following are provided:

* **Live Demo**: A link to a functional staging environment (e.g., Vercel, Railway, or Render).
* **Video Demo**: A 5-minute screencast showing the feature walkthrough and code structure.
* **Future Roadmap**: A list of at least 5 "Good First Issues" for the next batch of contributors.

---

### Phase 0: The Foundational Scaffold (Universal Tasks)

Before starting project-specific features, all contributors must complete this foundation to ensure the project is scalable, then go ahead to the project they'll be working on.

| Task Item | Technical Goal / Deliverable |
| --- | --- |
| Dockerization | Create a docker-compose.yml that spins up the App, Database (PostgreSQL/PostGIS), and Cache (Redis) with one command. |
| CI/CD Pipeline | Set up GitHub Actions to run Linters and Tests on every Push or Pull Request. |
| Environment Config | Implement a .env.example system for managing API keys (OpenAI, Maps, AWS) securely. |
| Boilerplate Auth | Set up basic JWT or Session-based authentication to protect Admin and Researcher routes. |
| Base UI Theme | Initialize the Frontend with a design system (Tailwind or MaterialUI) and a shared component library. |

---

### Definition of Done Checklist (Pre GSoC & During GSoC)

For any task to be considered complete, the contributor must provide:

1. **Code**: Clean, commented, and linted according to project standards.
2. **Tests**: Unit and integration tests covering the new logic with successful CI execution.
3. **Documentation**: Updates to ARCHITECTURE.md and auto-generated API documentation.
4. **Migrations**: Valid database migration files for any schema changes.
5. **Review**: At least one approved code review from a mentor or peer **(peer review, assisting fellow contributors and collaboration is highly encouraged)**.
