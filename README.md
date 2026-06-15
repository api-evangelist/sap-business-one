# SAP Business One (sap-business-one)

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
