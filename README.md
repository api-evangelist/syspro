# SYSPRO (syspro)

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
