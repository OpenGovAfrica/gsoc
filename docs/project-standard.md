## GSoC 2026 Project Standards & Contributor Requirements

All work must adhere to the following standards to ensure long-term maintainability.

### 1. Technical Documentation
Every project must maintain these three core files:
* **README.md**: Includes project vision, visual UI mockups, and a "Quick Start" guide for local setup in under 5 minutes.
* **ARCHITECTURE.md**: Explains the tech stack choices, data flow diagrams, and the relationship between different services.
* **CONTRIBUTING.md**: Guidelines for environment setup, branching strategy, and pull request (PR) requirements.

### 2. Code Quality & Automation
Contributors must implement automated checks to ensure code health from the first commit.

| Category | Tooling | Requirement |
| :--- | :--- | :--- |
| **Linting** | Ruff (Python) / ESLint (JS) | Zero linting errors allowed in the main branch. |
| **Formatting** | Black (Python) / Prettier (JS) | Consistent code style enforced via pre-commit hooks. |
| **Testing** | PyTest / Jest | Minimum **70% code coverage** for all business logic. |
| **Version Control** | Git | Use [Conventional Commits](https://www.conventionalcommits.org/) (e.g., `feat:`, `fix:`, `docs:`). |

### 3. API & Data Standards
To ensure our data is useful to the broader civic tech ecosystem, you must follow these specs:

* **Self-Documenting APIs**: All backend routes must be documented using **OpenAPI/Swagger** (accessible via `/docs`).
* **Standard Schemas**:
    * **Citizens Tracker**: Must follow the [Popolo Specification](http://www.popoloproject.com/).
    * **Budget Parser**: Must output data in validated JSON or UTF-8 CSV.
    * **Service Tracker**: Must use **GeoJSON** for all spatial data points.
* **Provenance**: Every data entry must include a `source_url` or `evidence_ref` field to ensure data ethics and auditability.

### 4. Communication & Workflow
* **Public Development**: All work must be performed in public branches. Open a **Draft PR** early to get feedback on your architectural approach.
* **Issue Linking**: Every Pull Request must be linked to a specific GitHub Issue (e.g., `Closes #12`).
* **Weekly Sync**: Provide a written update every Friday covering:
    1. Achievements this week.
    2. Current blockers or technical challenges.
    3. Planned tasks for the following week.

### 5. Final Handover Deliverables
The project is considered complete only when the following are provided:
1. **Live Demo**: A link to a functional staging environment (e.g., Vercel, Railway, or Render).
2. **Video Demo**: A 5-minute screencast showing the feature walkthrough and code structure.
3. **Future Roadmap**: A list of at least 5 "Good First Issues" for the next batch of contributors.
