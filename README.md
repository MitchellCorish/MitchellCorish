# Hi, I'm Mitch 👋

I build and rebuild the systems that utilities, health administrators, and commerce platforms run on.

Most of my work starts in the same place. Something important is fragmented. Product behaviour lives partly in code, partly in database configuration, partly in a deployment script, and partly in the head of whoever has been there longest. My job is to find the real behaviour and make it explicit. Then I build the testing, deployment, and recovery controls that let a team change it safely.

I am currently a **Staff Software Engineer** working on enterprise utility platform modernization.

### What I work on

- **Legacy modernization.** Separating real product behaviour from customer-specific configuration. Reconciling settings that live across application code, database rows, and config files, then building the evidence needed to change them safely
- **Regression architecture.** Testing production code paths through narrow seams instead of parallel test-only implementations. Deterministic in-memory scenarios, committed baselines, and browser rendering checks against the real generator
- **Platform and delivery.** Build-once artifact contracts, configuration-driven deployment targets, packaged database migrations, preflight and dry-run gates, rollback and recovery boundaries
- **Infrastructure as code.** Terraform and Pulumi, importing existing cloud resources into managed state without recreating them
- **Cross-system diagnosis.** Where application code, SQL, identity, and third-party integrations meet and nobody owns the boundary. Token lifecycles, data-identity assumptions after a model change, gateway timeouts with an unproven downstream call

### Stack

| Area | What I use |
|---|---|
| **Languages** | C#, TypeScript, JavaScript, Go, SQL (T-SQL, PL/SQL) |
| **Backend** | .NET, ASP.NET WebAPI, Entity Framework and EF Core, Node.js, Express, hapi.js, TypeORM |
| **Frontend** | Angular 2 through 7, React 17 and 18, Retool |
| **Data** | SQL Server, Oracle, MongoDB, MySQL, SQLite. Schema design, stored procedures, triggers, indexing strategy. Migrations with DbUp, Entity Framework, and TypeORM |
| **Cloud** | AWS (ECS, EC2, S3, ALB, WAF, VPC, CloudWatch), Azure, GCP |
| **Infrastructure as code** | Terraform, Pulumi, Docker. Importing existing cloud resources into managed state without recreation |
| **CI/CD** | GitHub Actions, GitLab CI, Azure DevOps, TFS, Git and GitFlow. Build-once artifact contracts, preflight and dry-run gates, NPM and Docker registries. Renovate and Dependabot for automated dependency upgrades |
| **Testing** | NUnit, Playwright, Go testing. VCR-style HTTP recording with YAML cassettes for deterministic third-party integration tests. Committed baselines, narrow production seams, browser rendering checks |
| **Identity** | KeyCloak, OAuth 2.0, OIDC. Token lifecycle and downstream authorization debugging |
| **Integration** | ArcGIS REST and SOAP (Collector, Survey123, Workforce, Operations Dashboard), SAP, Meter Data Management (MDM), Shopify, BigCommerce, WooCommerce, Magento. Webhooks, message queues |
| **Healthcare interop** | HL7v3, FHIR |
| **API design** | RAML, OpenAPI, YAML contracts |
| **Observability** | CloudWatch, ELK Stack, Azure Monitor, Power BI, S3-backed log retention and archival |
| **Domains** | Utility customer information and billing, work and asset management, meter data, provincial health administration, B2B commerce |

**Honest depth calibration.** TypeScript and Node have been constant since 2015, across three employers. Go comes from nearly three years of production backend work at a commerce SaaS. C#/.NET and SQL Server are my current daily depth. AWS with Terraform is my strongest infrastructure experience. Azure and Pulumi are current. GCP is supporting administration rather than equivalent depth.

### A note on this profile

Most of my work over the last decade has been in private repositories for enterprise employers, so what is public here is not representative. I am happy to talk through architecture and approach in detail.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/mitchellcorish/) · Charlottetown, PE, Canada · Open to remote
