# Awesome-Org-Configuration-Optimization
# Awesome-Org-Configuration-Optimization

# Top Org Configuration Optimization Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Technical Debt Analysis, Metadata Optimization & Org Health Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Org Configuration Optimization Tools**. These tools analyze Salesforce orgs (and similar SaaS platforms) to identify unused metadata, redundant automations, security risks, and technical debt — providing actionable recommendations to reduce complexity, improve performance, and prepare for AI-driven features like Agentforce.

**Examples** include Salesforce Optimizer, Hubbl Diagnostics, Quality Clouds, Elements.cloud, Panaya ForeSight, Metazoa Snapshot, Salto, Clayton.io, and Proudly (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom metadata analysis, and transparent org health monitoring — ideal for Salesforce admins, architects, and developers building data-sovereign optimization tooling.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Optimizer](https://help.salesforce.com/)**  
  Built-in Salesforce tool that snapshots your org and analyzes 50+ metrics covering security, storage, fields, custom code, layouts, and reports. Provides detailed findings with links to fix settings directly. Note: Salesforce Optimizer is being sunset; Org Check is the recommended free alternative .

- **[Hubbl Diagnostics](https://www.hubbl.com/)**  
  Org intelligence platform with free Essentials tier (monthly basic scan) and Premium features. Provides complexity analysis, automation insights, and AI-powered Recommendations Dashboard aligned with the Salesforce Well-Architected framework. Action Plan delivers prioritized, impact-driven remediation roadmaps .

- **[Quality Clouds](https://qualityclouds.ai/)**  
  SaaS code governance platform for Salesforce, ServiceNow, and Dynamics. Automates static code analysis, technical debt tracking, and compliance validation with CI/CD integration. Library of code and no-code best practices; trusted by Fortune 500 enterprises .

- **[Elements.cloud](https://elements.cloud/)**  
  Free tier available for process mapping, documentation, and Salesforce metadata change tracking. Connects to Salesforce orgs (read-only) for impact analysis, dependency visualization, and AI-powered org insights. Consulting spaces for multi-client management .

- **[Panaya ForeSight](https://www.panaya.com/)**  
  Change Intelligence and Smart Testing platform for Salesforce. World-class Impact Analysis Engine maps dependencies across all metadata types for safe changes. Used by 150+ customers for CPQ development, Flow migration, M&A, and technical debt reduction .

- **[Metazoa Snapshot](https://www.metazoa.com/)**  
  Salesforce metadata analysis platform with Impact Analysis Report covering 250+ metadata types and 1,400+ relationships. Visual entity relationship diagrams, unused asset identification, and Intelligent Assistant for AI-guided remediation. Enables org splits, clones, and merges .

- **[Salto](https://www.salto.io/)**  
  SaaS configuration management platform that extracts, compares, and deploys metadata across environments with Git-based version control.

- **[Clayton.io](https://clayton.io/)**  
  Automated code review and org health monitoring for Salesforce with AI-powered quality gates.

- **[Proudly](https://www.proudly.com/)**  
  Salesforce org optimization and technical debt remediation platform with expert-driven analysis.

## Open-Source GitHub Projects

- **[Org Check](https://github.com/SalesforceLabs/OrgCheck)**  
  Salesforce Labs open-source application and sf plugin for quick org analysis and technical debt identification. Installable from AppExchange or via npm (`sf plugins install @orgcheck/sfdx-plugin`). Analyzes metadata, identifies unused components, and exports results as JSON, CSV, or XLSX. The recommended free alternative to Salesforce Optimizer . Apache 2.0 licensed.

- **[Tailor](https://github.com/opendevstack/tailor)**  
  Open-source tool for declarative configuration management and drift detection (primarily for OpenShift/Kubernetes, adaptable for org config comparison). `tailor diff` compares current state against desired templates; `tailor apply` reconciles drift with per-resource confirmation. Secret drift hidden by default for security . BSD-3-Clause licensed.

- **[Salesforce-MCP-Server](https://github.com/SameerShrivastava-SF/Salesforce-MCP-Server)**  
  Open-source MCP server for Salesforce with field usage analysis across ALL metadata types (Apex Classes, Triggers, Flows, Validation Rules, Formula Fields, Workflow Rules, Page Layouts, Reports). Generates CSV reports for field cleanup, impact analysis, compliance audits, and migration planning. v2.2 analyzes 500 fields in 5-10 minutes (5-6x faster) . MIT licensed.

- **[ansible-inspec](https://pypi.org/project/ansible-inspec/)**  
  Open-source compliance testing integration combining Ansible inventory management with InSpec testing. Runs parallel compliance checks across hosts with unified reporting (JSON, CLI, HTML). Adaptable for SaaS configuration validation workflows . GPL-3.0 licensed.

- **[Operately](https://github.com/Operately/Operately)**  
  Open-source company operating system with goals/OKRs, project management, and team spaces. Provides structured execution cadence and progress check-ins. Self-hostable with flat-rate pricing (no per-seat). While not Salesforce-specific, useful for org governance and operational discipline . Apache 2.0 licensed.

- **[Paperclip](https://www.npmjs.com/package/@solosoficial/solos)**  
  Open-source full control plane for AI agent organizations with identity/access, org charts, work/task system, heartbeat execution, governance/approvals, and budget controls. Full audit logging and company portability for multi-tenant operations . MIT licensed.

- **[Salesforce MCP Server (Community)](https://github.com/SalesforceLabs)**  
  Community-maintained MCP servers for Salesforce metadata analysis and org operations.

- **[sfdx-hardis](https://github.com/hardisgroupcom/sfdx-hardis)**  
  Open-source Salesforce DevOps tool with org audit, metadata analysis, and technical debt monitoring capabilities.

### Additional Strong Open-Source Options

- **[SFDMU](https://github.com/forcedotcom/SFDX-Data-Move-Utility)** — Salesforce Data Move Utility for complex data migrations with metadata awareness.
- **[CumulusCI](https://github.com/SFDO-Tooling/CumulusCI)** — Salesforce DevOps framework with org snapshot, dependency management, and release automation.
- **[Salesforce CLI](https://github.com/forcedotcom/cli)** — Official CLI with metadata retrieval, deployment, and org analysis commands.
- **[SFDX Scanner](https://github.com/forcedotcom/sfdx-scanner)** — Static analysis for Apex, Visualforce, and Lightning components with customizable rules.
- **[PMD](https://github.com/pmd/pmd)** — Extensible static code analyzer with Apex support for code quality and technical debt.
- **Orchestration Tools** — Apache Airflow, Dagster for scheduling org health checks and remediation pipelines.
- **Analytics Tools** — Metabase, Apache Superset for visualizing org health metrics over time.

**Frameworks for building custom systems**: Combine **Org Check** for technical debt analysis, **Salesforce-MCP-Server** for field usage audits, **Tailor** for configuration drift detection, **CumulusCI** for DevOps, and **Metabase + PostgreSQL** for trend dashboards to build a complete self-hosted org optimization stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Org configuration optimization tools must comply with data protection regulations (GDPR, CCPA), Salesforce terms of service, and security best practices.
- Self-hosted open-source solutions require proper security hardening, credential management, and regular updates.

---

**Made for Salesforce administrators, solution architects, DevOps engineers, and developers building org health optimization platforms.**  
Let's make org configuration optimization more open, transparent, and admin-friendly.
