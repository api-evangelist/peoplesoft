# PeopleSoft (peoplesoft)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Collection of Oracle PeopleSoft Enterprise application APIs for Human Capital Management, Financial Management, Supply Chain Management, CRM, Campus Solutions, and engineering intelligence across PeopleTools platform services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/peoplesoft/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Campus Solutions
- CRM
- Enterprise Software
- ERP
- Financial Management
- HCM
- Supply Chain Management

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-17

## APIs

### PeopleSoft REST API

RESTful web services for PeopleSoft applications enabling integration with external systems via the PeopleTools platform.

- **Human URL:** [https://docs.oracle.com/en/applications/peoplesoft/](https://docs.oracle.com/en/applications/peoplesoft/)
- **Base URL:** `https://{hostname}:{port}/psft/api/v1`

#### Tags

- Integration
- REST
- Web Services

#### Properties

- [Documentation](https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tpcl/index.html)
- [Authentication](https://docs.oracle.com/cd/F30998_01/pt858pbr2/eng/pt/tsec/concept_UnderstandingOAuth2_0.html)
- [OpenAPI](openapi/rest-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Application Services Framework API

Modern REST API layer introduced in PeopleTools 8.59 that produces fully compliant OpenAPI/Swagger specifications, supports proper HTTP status codes, uniform URLs, and JSON payloads for integration with Oracle Integration Cloud, mobile apps, and microservices.

- **Human URL:** [https://docs.oracle.com/cd/E52319_01/infoportal/asf.html](https://docs.oracle.com/cd/E52319_01/infoportal/asf.html)
- **Base URL:** `https://{hostname}:{port}/psft/asf/v1`

#### Tags

- Integration
- Modern
- OpenAPI
- REST

#### Properties

- [Documentation](https://docs.oracle.com/cd/E52319_01/infoportal/asf.html)
- [OpenAPI](openapi/application-services-framework.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Integration Broker

Message-based integration framework for synchronous and asynchronous communication supporting both SOAP and REST protocols.

- **Human URL:** [https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tibr/index.html](https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tibr/index.html)
- **Base URL:** `https://{hostname}:{port}/PSIGW/RESTListeningConnector`

#### Tags

- Integration
- Messaging
- REST
- SOAP

#### Properties

- [Documentation](https://docs.oracle.com/en/applications/peoplesoft/integration-broker/)
- [OpenAPI](openapi/integration-broker.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Query API

Execute PeopleSoft Query definitions and retrieve results via REST including the Query Access Service operations for listing, executing, and managing queries.

- **Human URL:** [https://docs.oracle.com/en/applications/peoplesoft/query-api/](https://docs.oracle.com/en/applications/peoplesoft/query-api/)
- **Base URL:** `https://{hostname}:{port}/psft/api/query/v1`

#### Tags

- Data Access
- QAS
- Query
- Reporting

#### Properties

- [Documentation](https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/trws/concept_QueryAccessServiceOperations-1f7e36.html)
- [OpenAPI](openapi/query.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Component Interface API

Programmatic access to PeopleSoft components for data manipulation providing CRUD operations on component data via REST.

- **Human URL:** [https://docs.oracle.com/en/applications/peoplesoft/component-interfaces/](https://docs.oracle.com/en/applications/peoplesoft/component-interfaces/)
- **Base URL:** `https://{hostname}:{port}/psft/api/componentinterface/v1`

#### Tags

- Component Interface
- CRUD Operations
- Data Access

#### Properties

- [Documentation](https://docs.oracle.com/cd/E92519_02/pt856pbr3/eng/pt/tcpi/index.html)
- [OpenAPI](openapi/component-interface.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Search Framework API

Search indexing and query capabilities powered by OpenSearch (previously Elasticsearch) for full-text search, analytics dashboards, and PeopleSoft Insights.

- **Human URL:** [https://docs.oracle.com/cd/E52319_01/infoportal/search.html](https://docs.oracle.com/cd/E52319_01/infoportal/search.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/search/v1`

#### Tags

- Analytics
- Insights
- OpenSearch
- Search

#### Properties

- [Documentation](https://docs.oracle.com/cd/E52319_01/infoportal/search.html)
- [OpenAPI](openapi/search-framework.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Data Distribution Framework API

Framework for extracting and flattening PeopleSoft data for machine learning and analytics purposes. Uses PeopleSoft Search Framework technology with OpenSearch to build, index, and register data models that can be exposed as REST APIs.

- **Human URL:** [https://docs.oracle.com/cd/F44200_01/pt859pbr2/eng/pt/tmlf/concept_UnderstandingDataDistributionFramework.html](https://docs.oracle.com/cd/F44200_01/pt859pbr2/eng/pt/tmlf/concept_UnderstandingDataDistributionFramework.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/ddf/v1`

#### Tags

- Analytics
- Data Distribution
- Data Extraction
- Machine Learning

#### Properties

- [Documentation](https://docs.oracle.com/cd/F44200_01/pt859pbr2/eng/pt/tmlf/concept_UnderstandingDataDistributionFramework.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Notification Framework API

Push notification and event-driven notification services including the Notification Composer for email, text, and in-app notifications. Requires PeopleTools 8.59.19+.

- **Human URL:** [https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/eewe/concept_PeopleSoftEventsandNotificationsFrameworkOverview-227ff2.html](https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/eewe/concept_PeopleSoftEventsandNotificationsFrameworkOverview-227ff2.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/notifications/v1`

#### Tags

- Events
- Messaging
- Notifications
- Push Notifications

#### Properties

- [Documentation](https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/eewe/concept_PeopleSoftEventsandNotificationsFrameworkOverview-227ff2.html)
- [OpenAPI](openapi/notification-framework.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Chatbot Integration Framework API

Integration framework for connecting PeopleSoft with Oracle Digital Assistant (ODA) including REST services for chatbot data retrieval and embedded chatbot UI on Fluid pages (PICASO). Requires PeopleTools 8.57.07+.

- **Human URL:** [https://docs.oracle.com/cd/E52319_01/infoportal/chatbot.html](https://docs.oracle.com/cd/E52319_01/infoportal/chatbot.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/chatbot/v1`

#### Tags

- Chatbot
- Conversational AI
- Digital Assistant
- PICASO

#### Properties

- [Documentation](https://docs.oracle.com/cd/E52319_01/infoportal/chatbot.html)
- [F A Q](https://docs.oracle.com/cd/E52319_01/infoportal/peoplesoft_chatbot_faq.html)
- [OpenAPI](openapi/chatbot-integration.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Approval Workflow Engine API

Framework for creating, running, and managing approval processes exposable via REST service operations through Integration Broker or ASF.

- **Human URL:** [https://docs.oracle.com/en/applications/peoplesoft/](https://docs.oracle.com/en/applications/peoplesoft/)
- **Base URL:** `https://{hostname}:{port}/psft/api/approvals/v1`

#### Tags

- Approvals
- AWE
- Workflow

#### Properties

- [Documentation](https://docs.oracle.com/en/applications/peoplesoft/)
- [OpenAPI](openapi/approval-workflow-engine.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Process Scheduler API

Process request APIs for submitting and scheduling batch jobs, monitoring process run status, viewing logs, and Application Engine batch processing statistics.

- **Human URL:** [https://docs.oracle.com/cd/E24150_01/pt851h2/eng/psbooks/tprs/htm/tprs05.htm](https://docs.oracle.com/cd/E24150_01/pt851h2/eng/psbooks/tprs/htm/tprs05.htm)
- **Base URL:** `https://{hostname}:{port}/psft/api/scheduler/v1`

#### Tags

- Batch Processing
- Process Monitor
- Scheduling

#### Properties

- [Documentation](https://docs.oracle.com/cd/E24150_01/pt851h2/eng/psbooks/tprs/htm/tprs05.htm)
- [OpenAPI](openapi/process-scheduler.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Cloud Manager API

REST APIs for automated environment provisioning and deployment on Oracle Cloud Infrastructure including PeopleTools upgrades, update management, and self-service provisioning templates.

- **Human URL:** [https://docs.oracle.com/cd/E52319_01/infoportal/cloudmgr.html](https://docs.oracle.com/cd/E52319_01/infoportal/cloudmgr.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/cloudmgr/v1`

#### Tags

- Cloud
- Deployment
- OCI
- Provisioning

#### Properties

- [Documentation](https://docs.oracle.com/cd/E52319_01/infoportal/cloudmgr.html)
- [OpenAPI](openapi/cloud-manager.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Update Manager API

REST services for automated update image management, change package generation, and PeopleSoft Automated Updates (PAU).

- **Human URL:** [https://docs.oracle.com/cd/E52319_01/infoportal/pum.html](https://docs.oracle.com/cd/E52319_01/infoportal/pum.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/pum/v1`

#### Tags

- Lifecycle Management
- Patching
- Updates

#### Properties

- [Documentation](https://docs.oracle.com/cd/E52319_01/infoportal/pum.html)
- [OpenAPI](openapi/update-manager.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Pivot Grid API

Operational dashboard reporting using PS Query, Composite Query, or component data sources accessible via web services for analytics and visualization.

- **Human URL:** [https://docs.oracle.com/cd/F28299_01/pt857pbr3/eng/pt/tpvg/concept_PeopleSoftPivotGridOverview-1e7c6b.html](https://docs.oracle.com/cd/F28299_01/pt857pbr3/eng/pt/tpvg/concept_PeopleSoftPivotGridOverview-1e7c6b.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/pivotgrid/v1`

#### Tags

- Analytics
- Dashboards
- Pivot Grid
- Reporting

#### Properties

- [Documentation](https://docs.oracle.com/cd/F28299_01/pt857pbr3/eng/pt/tpvg/concept_PeopleSoftPivotGridOverview-1e7c6b.html)
- [OpenAPI](openapi/pivot-grid.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft HCM API

Human Capital Management APIs for employee data, benefits, payroll, workforce administration, and talent management.

- **Human URL:** [https://docs.oracle.com/en/applications/peoplesoft/human-capital-management/index.html](https://docs.oracle.com/en/applications/peoplesoft/human-capital-management/index.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/hcm/v1`

#### Tags

- Benefits
- HCM
- HR
- Payroll

#### Properties

- [Documentation](https://docs.oracle.com/en/applications/peoplesoft/human-capital-management/index.html)
- [API Reference](https://docs.oracle.com/cd/F58024_01/hcm92pbr43/eng/hcm/ecch/UnderstandingRestApiEndpointsForPeoplesoftSkills.html)
- [OpenAPI](openapi/hcm.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Employee Directory API

REST API for retrieving employee details by name or employee ID, and for looking up direct reports based on manager name or ID. Supports the Employee Directory chatbot skill and integration with external directories.

- **Human URL:** [https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeoplesoftEmployeeDirectoryemployeedirectory.html](https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeoplesoftEmployeeDirectoryemployeedirectory.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/hcm/employeedirectory/v1`

#### Tags

- Employee Directory
- HCM
- Workforce Data

#### Properties

- [Documentation](https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeoplesoftEmployeeDirectoryemployeedirectory.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Absence Management API

REST API for creating, updating, and retrieving absence requests, viewing employee absence balances by type, and retrieving absence configuration rules. Supports Absence Management chatbot skill and self-service integrations.

- **Human URL:** [https://docs.oracle.com/cd/F70351_01/cs92pbr27/eng/cs/eccs/UnderstandingRESTAPIEndpointsForPeopleSoftAbsenceManagementApplicationServicesabsence.html](https://docs.oracle.com/cd/F70351_01/cs92pbr27/eng/cs/eccs/UnderstandingRESTAPIEndpointsForPeopleSoftAbsenceManagementApplicationServicesabsence.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/hcm/absence/v1`

#### Tags

- Absence Management
- HCM
- Leave
- Time Off

#### Properties

- [Documentation](https://docs.oracle.com/cd/F70351_01/cs92pbr27/eng/cs/eccs/UnderstandingRESTAPIEndpointsForPeopleSoftAbsenceManagementApplicationServicesabsence.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Recruiting and Talent Management API

REST endpoints for job search services, Candidate Gateway self-service, recruiting solutions, and talent management workflows.

- **Human URL:** [https://docs.oracle.com/cd/F85027_01/hcm92pbr47/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftJobSearchServiceshrsjobs.html](https://docs.oracle.com/cd/F85027_01/hcm92pbr47/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftJobSearchServiceshrsjobs.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/hcm/recruiting/v1`

#### Tags

- Candidate Gateway
- Job Search
- Recruiting
- Talent Management

#### Properties

- [Documentation](https://docs.oracle.com/cd/F85027_01/hcm92pbr47/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftJobSearchServiceshrsjobs.html)
- [OpenAPI](openapi/recruiting-talent-management.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Payroll for North America API

Delivered REST API endpoints for retrieving paycheck header details, earnings, deductions, taxes, direct deposits, employer paid benefits, garnishments, and year-end forms for North American payroll processing.

- **Human URL:** [https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRestApiEndpointsForPeoplesoftPayrollForNorthAmericaSkill.html](https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRestApiEndpointsForPeoplesoftPayrollForNorthAmericaSkill.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/hcm/payrollbankingyearendforms/v1`

#### Tags

- Compensation
- HCM
- North America
- Payroll

#### Properties

- [Documentation](https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRestApiEndpointsForPeoplesoftPayrollForNorthAmericaSkill.html)
- [API Reference](https://docs.oracle.com/cd/F82673_01/elm92pbr23/eng/elm/eccl/UnderstandingRESTAPIEndpointsForPeoplesoftPayrollForNorthAmericaServicespayrollbankingyearendforms.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Global Payroll API

REST API endpoints for the Global Payroll skill, providing access to payroll data, product profile information, and chatbot framework resources for international payroll processing across multiple countries.

- **Human URL:** [https://docs.oracle.com/cd/F58738_01/cs92pbr26/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftGlobalPayrollSkill.html](https://docs.oracle.com/cd/F58738_01/cs92pbr26/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftGlobalPayrollSkill.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/hcm/globalpayroll/v1`

#### Tags

- Global Payroll
- HCM
- International
- Payroll

#### Properties

- [Documentation](https://docs.oracle.com/cd/F58738_01/cs92pbr26/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftGlobalPayrollSkill.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft HR Common Utility Services API

REST API for retrieving employee country and business partner contact details. Shared utility services used across all delivered HCM skills and integration scenarios.

- **Human URL:** [https://docs.oracle.com/cd/F85282_01/cs92pbr30/eng/cs/eccs/UnderstandingRESTAPIEndpointsforPeopleSoftHRCommonUtilityServices.html](https://docs.oracle.com/cd/F85282_01/cs92pbr30/eng/cs/eccs/UnderstandingRESTAPIEndpointsforPeopleSoftHRCommonUtilityServices.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/hcm/hcmcommonutilities/v1`

#### Tags

- Employee Data
- HCM
- Utilities

#### Properties

- [Documentation](https://docs.oracle.com/cd/F85282_01/cs92pbr30/eng/cs/eccs/UnderstandingRESTAPIEndpointsforPeopleSoftHRCommonUtilityServices.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Financials API

Financial Management APIs for general ledger, accounts payable, accounts receivable, expenses, asset management, and financial reporting.

- **Human URL:** [https://docs.oracle.com/en/applications/peoplesoft/financial-management/index.html](https://docs.oracle.com/en/applications/peoplesoft/financial-management/index.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/financials/v1`

#### Tags

- AP
- AR
- Expenses
- Financials
- General Ledger

#### Properties

- [Documentation](https://docs.oracle.com/en/applications/peoplesoft/financial-management/index.html)
- [OpenAPI](openapi/financials.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Expenses API

Delivered REST API endpoints for expense report management including fetching expense reports by status, creation date, or sheet name, retrieving transaction details, managing wallet entries, expense type validation, and notification services for travel and expense processing.

- **Human URL:** [https://docs.oracle.com/cd/F48195_01/cs92pbr23/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftExpenseSkill.html](https://docs.oracle.com/cd/F48195_01/cs92pbr23/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftExpenseSkill.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/fscm/expenses/v1`

#### Tags

- Expense Reports
- Expenses
- Financials
- Travel

#### Properties

- [Documentation](https://docs.oracle.com/cd/F48195_01/cs92pbr23/eng/cs/eccs/UnderstandingRestApiEndpointsForPeoplesoftExpenseSkill.html)
- [API Reference](https://docs.oracle.com/cd/G47724_01/fscm92pbr55/eng/fscm/eccf/UnderstandingRESTAPIEndpointsForPeopleSoftGetTransactionDetailsexgettransdetails.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft eSettlements API

Delivered REST API endpoints for invoice and payment management including fetching disputed invoices, invoice status inquiries, payment status tracking, payment inquiries, and payment difference resolution for supplier settlement processing.

- **Human URL:** [https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRESTAPIEndpointsforPeopleSofteSettlementsSkill.html](https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRESTAPIEndpointsforPeopleSofteSettlementsSkill.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/fscm/esettlements/v1`

#### Tags

- eSettlements
- Financials
- Invoices
- Payments

#### Properties

- [Documentation](https://docs.oracle.com/cd/F57918_01/ps91pbr14/eng/ps/eccp/UnderstandingRESTAPIEndpointsforPeopleSofteSettlementsSkill.html)
- [API Reference](https://docs.oracle.com/cd/G35227_01/fscm92pbr54/eng/fscm/eccf/UnderstandingRESTAPIEndpointsForPeopleSoftFetchPaymentStatusespaymentstatus.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Supply Chain Management API

REST API endpoints for procurement, inventory management, order fulfillment, logistics, and enterprise integration points for warehouse management systems.

- **Human URL:** [https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html](https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/scm/v1`

#### Tags

- Inventory
- Logistics
- Order Fulfillment
- Procurement
- Supply Chain

#### Properties

- [Documentation](https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html)
- [OpenAPI](openapi/supply-chain-management.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft eProcurement API

Delivered REST API endpoints for requisition management including retrieving requisitions for items, getting requester lists and names, and checking requisition status. Supports the full procure-to-pay lifecycle from requisition creation through purchase order dispatch and receiving.

- **Human URL:** [https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html](https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/fscm/eprocurement/v1`

#### Tags

- eProcurement
- Purchasing
- Requisitions
- Supply Chain

#### Properties

- [Documentation](https://docs.oracle.com/cd/F92336_01/fscm92pbr50/eng/fscm/eccf/UnderstandingRestApiEndpointsForPeoplesoft.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Supplier Portal API

Comprehensive REST API for the Supplier Portal providing access to bid details, managed content such as announcements and events, overdue shipment tracking, purchase order acknowledgement, invoice and payment inquiries, and sourcing operations across secure and public supplier collaboration channels.

- **Human URL:** [https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftSupplierComprehensivePortalServicescp.html](https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftSupplierComprehensivePortalServicescp.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/fscm/scp/v1`

#### Tags

- Sourcing
- Supplier Collaboration
- Supplier Portal
- Supply Chain

#### Properties

- [Documentation](https://docs.oracle.com/cd/G20540_01/hcm92pbr51/eng/hcm/ecch/UnderstandingRESTAPIEndpointsForPeopleSoftSupplierComprehensivePortalServicescp.html)
- [Postman Collection](collections/application-services-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/application-services-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/approval-workflow-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/approval-workflow-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatbot-integration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatbot-integration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cloud-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/component-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/component-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/integration-broker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/integration-broker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/notification-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notification-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pivot-grid.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pivot-grid.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/process-scheduler.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/process-scheduler.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/query.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/query.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/recruiting-talent-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recruiting-talent-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/search-framework.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/search-framework.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/update-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/update-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft CRM API

Customer Relationship Management REST API endpoints and integration points for customer data, case management, sales, and marketing.

- **Human URL:** [https://docs.oracle.com/cd/F95753_01/crm92pbr22/eng/crm/eccc/UnderstandingRestApiEndpointsForPeoplesoft.html](https://docs.oracle.com/cd/F95753_01/crm92pbr22/eng/crm/eccc/UnderstandingRestApiEndpointsForPeoplesoft.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/crm/v1`

#### Tags

- Case Management
- CRM
- Customer Data
- Marketing
- Sales

#### Properties

- [Documentation](https://docs.oracle.com/cd/F95753_01/crm92pbr22/eng/crm/eccc/UnderstandingRestApiEndpointsForPeoplesoft.html)
- [OpenAPI](openapi/crm.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/crm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Campus Solutions API

Campus Solutions APIs for student records, admissions, enrollment, financial aid, and academic advising.

- **Human URL:** [https://docs.oracle.com/en/applications/peoplesoft/campus-solutions/index.html](https://docs.oracle.com/en/applications/peoplesoft/campus-solutions/index.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/campus/v1`

#### Tags

- Admissions
- Campus Solutions
- Education
- Financial Aid
- Student Records

#### Properties

- [Documentation](https://docs.oracle.com/en/applications/peoplesoft/campus-solutions/index.html)
- [OpenAPI](openapi/campus-solutions.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campus-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campus-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Enterprise Performance Management API

Analytics, budgeting, forecasting, and planning APIs with events and notifications framework for financial and operational performance management.

- **Human URL:** [https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/penw/index.html](https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/penw/index.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/epm/v1`

#### Tags

- Analytics
- Budgeting
- EPM
- Forecasting
- Planning

#### Properties

- [Documentation](https://docs.oracle.com/cd/E41507_01/epm91pbr3/eng/epm/penw/index.html)
- [OpenAPI](openapi/enterprise-performance-management.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/enterprise-performance-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/enterprise-performance-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PeopleSoft Interaction Hub API

Content management, branding, and portal administration APIs for the PeopleSoft Interaction Hub (formerly Enterprise Portal) with Integration Broker services.

- **Human URL:** [https://docs.oracle.com/cd/F75142_01/ps91pbr15/eng/ps/psad/PeopleSoftInteractionHubOverview.html](https://docs.oracle.com/cd/F75142_01/ps91pbr15/eng/ps/psad/PeopleSoftInteractionHubOverview.html)
- **Base URL:** `https://{hostname}:{port}/psft/api/hub/v1`

#### Tags

- Branding
- Content Management
- Interaction Hub
- Portal

#### Properties

- [Documentation](https://docs.oracle.com/cd/F75142_01/ps91pbr15/eng/ps/psad/PeopleSoftInteractionHubOverview.html)
- [OpenAPI](openapi/interaction-hub.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/interaction-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interaction-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/peoplesoft-inc)
- [Portal](https://www.oracle.com/applications/peoplesoft/)
- [Documentation](https://docs.oracle.com/en/applications/peoplesoft/index.html)
- [Getting Started](https://docs.oracle.com/en/applications/peoplesoft/peopletools/index.html)
- [Information  Portal](https://docs.oracle.com/cd/E52319_01/infoportal/)
- [Authentication](https://docs.oracle.com/cd/F30998_01/pt858pbr2/eng/pt/tsec/concept_UnderstandingOAuth2_0.html)
- [Blog](https://blogs.oracle.com/peoplesoft/)
- [Changelog](https://blogs.oracle.com/peoplesoft/category/ps-image-and-release-updates)
- [People Code  A P I  Reference](https://docs.oracle.com/cd/E25688_01/pt852pbr0/eng/psbooks/tpcr/book.htm)
- [Security](https://www.oracle.com/security-alerts/)
- [Support](https://support.oracle.com/)
- [Knowledge  Base](https://docs.oracle.com/en/applications/peoplesoft/)
- [Community](https://community.oracle.com/customerconnect/categories/peoplesoft)
- [Forum](https://forums.oracle.com/ords/apexds/domain/dev-community/category/peoplesoft_enterprise)
- [People Soft on  O C I](https://docs.oracle.com/cd/E52319_01/infoportal/opc.html)
- [Training](https://education.oracle.com/peoplesoft)
- [Videos](https://docs.oracle.com/cd/E52319_01/infoportal/videos.html)
- [Pricing](https://www.oracle.com/corporate/pricing/)
- [Terms of Service](https://www.oracle.com/contracts/)
- [Privacy Policy](https://www.oracle.com/legal/privacy/services-privacy-policy/)
- [News](https://docs.oracle.com/cd/E52319_01/infoportal/news.html)
- [Status Page](https://ocistatus.oraclecloud.com/)
- [Website](https://www.oracle.com/applications/peoplesoft/)
- [Login](https://cloud.oracle.com/)
- [Sign Up](https://cloud.oracle.com/)
- [R E S T  A P I  Endpoints](https://docs.oracle.com/cd/G36917_01/ps91pbr20/eng/ps/eccp/UnderstandingRestApiEndpointsForPeoplesoft.html)
- [Features](undefined)
- [Use Cases](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
