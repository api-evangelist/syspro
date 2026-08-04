# SYSPRO (syspro)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SYSPRO is a manufacturing and distribution ERP platform providing a REST API and integration framework for managing production orders, inventory, purchasing, sales, financial accounting, and supply chain operations. The platform supports integration via e.net Solutions business objects, OData RESTful endpoints, and WCF services, enabling ISVs and custom application developers to extend and connect with the SYSPRO ecosystem.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/syspro/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/syspro/refs/heads/main/apis.yml)

## Tags

- ERP
- Manufacturing
- Distribution
- Inventory
- Production Orders
- Purchasing
- Sales
- Financial Accounting
- Supply Chain

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### SYSPRO OData API

SYSPRO OData provides RESTful access to SYSPRO data across all functional modules including inventory, production, purchasing, sales, and financials. It uses basic authentication over HTTPS and supports standard OData query options including filtering, sorting, pagination, and column selection. Data retrieval is capped at 5000 rows per request with pagination supported via $skip and $top parameters.

- **Human URL:** [https://help.syspro.com/syspro-8-2023/topics/insights-and-reporting/syspro-odata/syspro-odata.htm](https://help.syspro.com/syspro-8-2023/topics/insights-and-reporting/syspro-odata/syspro-odata.htm)
- **Base URL:** `https://[server]/SYSPRO8Odata/SYSPROOData`

#### Tags

- OData
- Inventory
- Production
- Purchasing
- Sales
- Financials

#### Properties

- [Documentation](https://help.syspro.com/syspro-8-2023/topics/insights-and-reporting/syspro-odata/syspro-odata.htm)
- [Authentication](https://developer.syspro.com/documentation/)

### SYSPRO e.net Solutions API

SYSPRO e.net Solutions provides a framework for building custom business applications that integrate with SYSPRO using business objects. Business objects are specialized modules with predefined functions that automate processing across production orders, inventory management, purchasing, sales orders, and financial accounting. Supports HTTP REST and SOAP endpoints via WCF services with .NET Framework integration.

- **Human URL:** [https://developer.syspro.com/syspro-e-net/](https://developer.syspro.com/syspro-e-net/)
- **Base URL:** `https://[server]/SYSPROWCFService`

#### Tags

- Business Objects
- e.net
- WCF
- REST
- SOAP
- Integration

#### Properties

- [Documentation](https://developer.syspro.com/syspro-e-net/)
- [Documentation](https://developer.syspro.com/integrate-syspro/)

### SYSPRO Open Reporting API

The SYSPRO Open Reporting API enables external applications to programmatically call SYSPRO to run and distribute documents. It creates a business object wrapper around standard SYSPRO print programs, allowing custom and third-party developers to produce single documents from applications outside the main SYSPRO application.

- **Human URL:** [https://help.syspro.com/syspro-8-2025/resources/pdfs/2022-release/topics/syspro-8-srs-api-reference-guide.pdf](https://help.syspro.com/syspro-8-2025/resources/pdfs/2022-release/topics/syspro-8-srs-api-reference-guide.pdf)
- **Base URL:** `https://[server]/SYSPRO8`

#### Tags

- Reporting
- Documents
- Business Objects

#### Properties

- [Documentation](https://help.syspro.com/syspro-8-2025/resources/pdfs/2022-release/topics/syspro-8-srs-api-reference-guide.pdf)

## Common Properties

- [Website](https://www.syspro.com)
- [Documentation](https://developer.syspro.com/documentation/)
- [Git Hub Org](https://github.com/topics/syspro)
- [LinkedIn](https://www.linkedin.com/company/syspro)
- [Blog](https://www.syspro.com/blog/)
- [Pricing](https://www.syspro.com/contact-us/)
- [Status Page](https://trust.syspro.com/cloud-services/)
- [X (Twitter)](https://twitter.com/SYSPRO)
- [Plans](plans/syspro-plans-pricing.yml)
- [Rate Limits](rate-limits/syspro-rate-limits.yml)
- [Fin Ops](finops/syspro-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
