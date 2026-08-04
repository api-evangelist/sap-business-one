# SAP Business One (sap-business-one)

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

SAP Business One is an affordable, on-premise or cloud ERP solution designed for small and midsize businesses, covering finance and accounting, purchasing, inventory, sales, CRM, production, and analytics in a single integrated application. It exposes programmatic access through the Service Layer, a modern REST/OData v4 API for the SAP HANA edition, alongside the legacy DI API and DI Server for SQL Server deployments. Authentication uses session-based login that returns a B1SESSION cookie used for subsequent OData calls against company databases.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sap-business-one/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sap-business-one/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- ERP
- Enterprise Resource Planning
- Accounting
- Inventory Management
- CRM
- Small Business
- Midsize Business
- SAP

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### SAP Business One Service Layer API

RESTful OData v4 API for SAP Business One on HANA exposing nearly all business objects (business partners, items, orders, invoices, journal entries, inventory, production) for POST/GET/PATCH/DELETE operations. Authentication is session-based via POST /Login returning a B1SESSION cookie scoped to a specific company database.

- **Human URL:** [https://help.sap.com/doc/056f69366b5345a386bb8149f1700c19/10.0/en-US/Service%20Layer%20API%20Reference.html](https://help.sap.com/doc/056f69366b5345a386bb8149f1700c19/10.0/en-US/Service%20Layer%20API%20Reference.html)
- **Base URL:** `https://<load-balancer>:50000/b1s/v2`

#### Tags

- ERP
- OData
- REST
- Service Layer
- Business Objects

#### Properties

- [Documentation](https://help.sap.com/doc/056f69366b5345a386bb8149f1700c19/10.0/en-US/Service%20Layer%20API%20Reference.html)
- [Getting Started](https://learning.sap.com/courses/leveraging-the-sap-business-one-service-layer/introducing-service-layer-api-terms-and-documentation)
- [Reference](https://sap.highwaytwo.com/)
- [Postman Collection](collections/sap-business-one.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-business-one.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Business One DI API

COM-based Data Interface API for the SQL Server edition of SAP Business One providing programmatic access to business objects, master data, and transactional documents. The companion DI Server exposes a SOAP/XML wrapper for remote integration scenarios.

- **Human URL:** [https://help.sap.com/docs/SAP_BUSINESS_ONE](https://help.sap.com/docs/SAP_BUSINESS_ONE)
- **Base URL:** `https://<server>:30000`

#### Tags

- ERP
- DI API
- SOAP
- COM
- Integration

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_BUSINESS_ONE)
- [Postman Collection](collections/sap-business-one.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-business-one.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/sap-business-one)
- [Website](https://www.sap.com/products/erp/business-one.html)
- [Documentation](https://help.sap.com/docs/SAP_BUSINESS_ONE)
- [Pricing](https://www.sap.com/products/erp/business-one.html)
- [Sign Up](https://www.sap.com/products/erp/business-one/contact.html)
- [Support](https://support.sap.com)
- [Developer  Resources](https://api.sap.com)
- [Git Hub  Samples](https://github.com/SAP-samples)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
