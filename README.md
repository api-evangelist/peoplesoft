# PeopleSoft (peoplesoft)
Oracle PeopleSoft provides enterprise applications for Human Capital Management, Financial Management, Supply Chain Management, CRM, and Campus Solutions. The PeopleTools platform provides REST, SOAP, and Component Interface APIs for integration and automation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Campus Solutions, CRM, Enterprise Software, ERP, Financial Management, HCM, Supply Chain Management

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-17

## APIs

31 APIs covering PeopleTools platform services (REST API, Application Services Framework, Integration Broker, Component Interface, Query API), HCM modules (Workforce Administration, Benefits, Payroll, Talent), Financial Management (GL, AP, AR, Asset Management), Supply Chain Management (Purchasing, Inventory, Order Management), Campus Solutions (Student Records, Admissions, Financial Aid), and CRM.

See [apis.yml](apis.yml) for the complete API inventory.

## Artifacts

### OpenAPI

21 OpenAPI specifications in [openapi/](openapi/) covering platform services, HCM, financial, supply chain, and campus solutions APIs. Key modules enriched with component schemas built from PeopleSoft domain knowledge.

### JSON Schema

8 standalone JSON Schema files in [json-schema/](json-schema/) covering Employee, Position, JournalEntry, Voucher, Student, ClassEnrollment, PurchaseOrder, and Case records.

### JSON Structure

8 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [PeopleSoft Context](json-ld/peoplesoft-context.jsonld) — 8 types, 77 properties

### Examples

8 realistic example JSON files in [examples/](examples/).

## Features

| Name | Description |
|------|-------------|
| REST Web Services | RESTful APIs via PeopleTools Integration Broker for JSON-based integration. |
| Application Services Framework | Modern REST API layer with OpenAPI spec generation and JSON payloads. |
| Integration Broker | Enterprise messaging platform supporting SOAP, REST, and async messaging. |
| Component Interface API | Programmatic access to PeopleSoft component business logic. |
| Query API | Execute PeopleSoft queries and retrieve results via REST. |
| HCM APIs | Workforce administration, benefits, payroll, and talent management. |
| Financial Management APIs | General ledger, AP/AR, asset management, and procurement. |
| Supply Chain Management APIs | Inventory, purchasing, order management, and supplier collaboration. |
| Campus Solutions APIs | Student records, admissions, financial aid, and academic advisement. |
| OAuth 2.0 Authentication | Standards-based OAuth 2.0 for secure API access. |
| Fluid UI Integration | APIs for integrating with PeopleSoft Fluid user interface. |
| Chatbot Integration | Digital assistant and chatbot framework APIs. |

## Use Cases

| Name | Description |
|------|-------------|
| HR System Integration | Integrate HCM data with payroll, benefits, and talent management platforms. |
| Financial Data Exchange | Exchange financial transactions with external ERP and accounting systems. |
| Student Information System | Integrate campus solutions with learning management and student portals. |
| Supply Chain Automation | Automate procurement, inventory, and supplier management workflows. |
| Self-Service Portals | Build employee and student self-service applications. |
| Mobile Applications | Power mobile apps for self-service, approvals, and time entry. |
| Cloud Integration | Connect PeopleSoft with Oracle Integration Cloud and other platforms. |
| Reporting and Analytics | Extract data via Query API for BI and analytics platforms. |

## Solutions

| Name | Description |
|------|-------------|
| PeopleSoft HCM | Human Capital Management for workforce, benefits, payroll, and talent. |
| PeopleSoft FSCM | Financial and Supply Chain Management for GL, AP/AR, procurement, and inventory. |
| PeopleSoft Campus Solutions | Higher education for student records, admissions, financial aid, and academics. |
| PeopleSoft CRM | Customer Relationship Management for sales, marketing, and service. |

## Vocabulary

- [PeopleSoft Vocabulary](vocabulary/peoplesoft-vocabulary.yaml) — 6 resources, 5 APIs, 4 domains, 5 personas

## Rules

- [PeopleSoft Spectral Rules](rules/peoplesoft-spectral-rules.yml) — 19 rules enforcing PeopleSoft API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
