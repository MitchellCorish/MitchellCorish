## Hi there 👋

<!--
**MitchellCorish/MitchellCorish** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

I am currently a **Staff Software Engineer** leading the productization of a utility customer information system where every customer had been a unique build, from discovery and concept through build, hyper-care at go-live, and into long-term support.

### What I work on

- **Productization.** Turning a product where every customer is a custom build into a configurable one: cataloguing settings, building market-specific defaults and configuration packs, and making installs repeatable
- **Legacy modernization.** Separating real product behaviour from customer-specific configuration. Reconciling settings that live across application code, database rows, and config files, then building the evidence needed to change them safely
- **Regression architecture.** Testing production code paths through narrow seams instead of parallel test-only implementations. Deterministic in-memory scenarios, committed baselines, and browser rendering checks against the real generator
- **Platform and delivery.** Build-once artifact contracts, configuration-driven deployment targets, packaged database migrations, preflight and dry-run gates, rollback and recovery boundaries
- **Infrastructure as code.** Pulumi and Terraform. Importing existing cloud resources into Pulumi managed state without recreating them. Architecting the full VPC stack from Route 53, WAFs, and network interfaces through ECS/Fargate, RDS, and backup retention policies
- **Cross-system diagnosis.** Where application code, SQL, identity, and third-party integrations meet and nobody owns the boundary. Token lifecycles, data-identity assumptions after a model change, gateway timeouts with an unproven downstream call

### How I work

- **Small, reversible change.** Pull requests of about 500 lines or fewer, one revertable unit each, with new behaviour behind a feature flag that defaults off. A bug fix ships without a flag only after characterization tests pin today's behaviour.
- **Measure before fixing.** I want the p50, the p90, and the count of cases the current fix misses before I change anything.
- **Remove before adding.** The first question is whether the thing needs to exist. A dropped feature or dependency is often safer than a guarded one.
- **Options, risk, and the reason.** Every recommendation comes with alternatives, a risk to production, and why. Security fixes get weighed against the downtime risk of deploying them.
- **Boundaries before delegation.** For people and for AI agents alike: read-only cloud access, deploys only through gated CI, and nothing merges without a human approval.
- **Done means verified.** Merged is not done. Done is checked in the next environment, visible in the logs or analytics, and documented.

### Something I am proud of

Early in my career I worked for a utility ERP vendor whose platform was locked into Dexterity, WCF, and Silverlight, with no path to the web. The company needed one.

With a team, I architected the work order system as the first product built outside that stack. Node.js, Express, TypeORM, and Angular, strictly typed and code first rather than the database-first approach standard in the sector. End to end from API to front end, in under a year, sized for a national utility.

That architecture became the foundation the company used to move from Microsoft Dynamics GP onto Dynamics 365. It still underpins their flagship product today, roughly eight years later.

### Stack

| Area | What I use |
|---|---|
| **Languages** | C#, TypeScript, JavaScript, Go, SQL (T-SQL, PL/SQL) |
| **Backend** | .NET, ASP.NET WebAPI, Entity Framework and EF Core, Node.js, Express, hapi.js, TypeORM |
| **Frontend** | Angular 2 through 7, React 17 and 18, Retool |
| **Data** | SQL Server, Oracle, MongoDB, MySQL, SQLite. Schema design, stored procedures, triggers, indexing strategy. Migrations with DbUp, Entity Framework, and TypeORM |
| **Cloud** | AWS (ECS, Fargate, EC2, RDS, S3, Route 53, ALB, WAF, VPC, CloudWatch), Azure, GCP |
| **Infrastructure as code** | Terraform, Pulumi, Docker. Importing existing cloud resources into managed state without recreation. Backup retention and recovery boundaries |
| **CI/CD** | GitHub Actions, GitLab CI, Azure DevOps, TFS, Git and GitFlow. Build-once artifact contracts, preflight and dry-run gates, NPM and Docker registries. Renovate and Dependabot for automated dependency upgrades |
| **Testing** | NUnit, Playwright, Go testing. VCR-style HTTP recording with YAML cassettes for deterministic third-party integration tests. Committed baselines, narrow production seams, browser rendering checks |
| **Identity** | KeyCloak, OAuth 2.0, OIDC. JWT token lifecycle and downstream authorization debugging |
| **Integration** | ArcGIS REST and SOAP (Collector, Survey123, Workforce, Operations Dashboard), SAP, asset management systems, Shopify, BigCommerce, WooCommerce, Magento. Webhooks, message queues |
| **AI-assisted engineering** | Claude Code, OpenAI Codex, GitHub Copilot, MCP servers. LangChain and Pinecone. Agent guardrails, structured architecture and security review of agent output |
| **Healthcare interop** | HL7v3, FHIR |
| **API design** | RAML, OpenAPI, YAML contracts |
| **Observability** | CloudWatch, ELK Stack, Azure Monitor, Power BI, S3-backed log retention and archival |
| **Domains** | Utility customer information and billing, work and asset management, provincial health administration, B2B commerce |

**Transparent depth calibration.** TypeScript and Node have been constant since 2015, across three employers. Go comes from nearly three years of production backend work at a commerce SaaS. C#/.NET and SQL Server are my current daily depth. AWS is my strongest infrastructure experience. Azure and Pulumi are current.

### A note on this profile

Most of my work over the last decade has been in private repositories for enterprise employers, so what is public here is not representative. I am happy to talk through architecture and approach in detail.

Always happy to talk about legacy modernization, platform architecture, utility software, or anything involving a system nobody fully understands anymore.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/mitchellcorish/) · Charlottetown, PE, Canada · Open to remote