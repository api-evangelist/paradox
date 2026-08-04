# Paradox (paradox)

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

APIs and resources for Paradox, a conversational AI recruiting assistant platform powered by Olivia, an AI assistant that automates candidate screening, interview scheduling, and hiring workflows through chat, SMS, and mobile-driven experiences.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/paradox/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Artificial Intelligence
- Candidate Screening
- Chatbot
- Conversational AI
- Hiring Automation
- HR Technology
- Interview Scheduling
- Recruiting
- SMS
- Talent Acquisition

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Paradox Conversational AI API

API for integrating Paradox conversational AI recruiting assistant capabilities into your applications.

- **Human URL:** [https://www.paradox.ai](https://www.paradox.ai)
- **Base URL:** `https://api.paradox.ai`

#### Tags

- AI
- Candidate Experience
- Chatbot
- Conversational AI
- HR Technology
- Recruiting

#### Properties

- [Documentation](https://developers.paradox.ai/docs)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.paradox.ai/docs/authentication)
- [Rate Limits](https://developers.paradox.ai/docs/rate-limits)

### Paradox Company API

API for accessing company-level data in Paradox including conversations, groups, schools, areas, and AI assistant configuration.

- **Human URL:** [https://readme.paradox.ai/reference/get-company-conversations](https://readme.paradox.ai/reference/get-company-conversations)
- **Base URL:** `https://api.paradox.ai/api/v1/public`

#### Tags

- AI Assistant
- Company
- Conversations
- Groups

#### Properties

- [Documentation](https://readme.paradox.ai/reference/get-company-conversations)
- [API Reference](https://readme.paradox.ai/reference/overview)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paradox Candidates API

API for managing candidates within the Paradox platform including creating, retrieving, updating, deleting, and unsubscribing candidates, as well as sending candidate messages and scheduling shortlist reviews.

- **Human URL:** [https://readme.paradox.ai/reference/get-candidates](https://readme.paradox.ai/reference/get-candidates)
- **Base URL:** `https://api.paradox.ai/api/v1/public`

#### Tags

- Candidates
- Messaging
- Recruiting
- Screening

#### Properties

- [Documentation](https://readme.paradox.ai/reference/get-candidates)
- [API Reference](https://readme.paradox.ai/reference/create-candidate)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [J S O N  Schema](json-schema/paradox-candidate-schema.json)

### Paradox Users API

API for managing users within the Paradox platform including creating, retrieving, updating, deleting, deactivating, and reactivating users, as well as managing user roles and looking up users by employee ID.

- **Human URL:** [https://readme.paradox.ai/reference/get-users](https://readme.paradox.ai/reference/get-users)
- **Base URL:** `https://api.paradox.ai/api/v1/public`

#### Tags

- Administration
- Roles
- Users

#### Properties

- [Documentation](https://readme.paradox.ai/reference/get-users)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paradox Scheduling API

API for managing interview scheduling within the Paradox platform including retrieving multiparty interviewers, interview settings, job location rooms, sending interview alerts, and accessing interview history.

- **Human URL:** [https://readme.paradox.ai/reference/send-interview-alerts](https://readme.paradox.ai/reference/send-interview-alerts)
- **Base URL:** `https://api.paradox.ai/api/v1/public`

#### Tags

- Calendars
- Interviews
- Scheduling

#### Properties

- [Documentation](https://readme.paradox.ai/reference/send-interview-alerts)
- [API Reference](https://readme.paradox.ai/reference/get-job-location-rooms)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paradox Locations API

API for managing locations within the Paradox platform including creating, retrieving, updating, and deleting locations, as well as looking up locations by job location code and managing location rooms.

- **Human URL:** [https://readme.paradox.ai/reference/get-single-location-by-job_loc_code](https://readme.paradox.ai/reference/get-single-location-by-job_loc_code)
- **Base URL:** `https://api.paradox.ai/api/v1/public`

#### Tags

- Job Sites
- Locations
- Rooms

#### Properties

- [Documentation](https://readme.paradox.ai/reference/get-single-location-by-job_loc_code)
- [API Reference](https://readme.paradox.ai/reference/update-a-location)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paradox Reporting API

API for accessing and generating reports within the Paradox platform including retrieving report lists, creating new reports, and accessing individual report details.

- **Human URL:** [https://readme.paradox.ai/reference/get-report-list](https://readme.paradox.ai/reference/get-report-list)
- **Base URL:** `https://api.paradox.ai/api/v1/public`

#### Tags

- Analytics
- Data
- Reporting

#### Properties

- [Documentation](https://readme.paradox.ai/reference/get-report-list)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paradox Candidate Attributes API

API for managing candidate attributes within the Paradox platform including retrieving, patching, and updating candidate attribute data.

- **Human URL:** [https://readme.paradox.ai/reference/get-candidate-attributes](https://readme.paradox.ai/reference/get-candidate-attributes)
- **Base URL:** `https://api.paradox.ai/api/v1/public`

#### Tags

- Attributes
- Candidates
- Custom Fields

#### Properties

- [Documentation](https://readme.paradox.ai/reference/get-candidate-attributes)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paradox User Permissions API

API for managing user location permissions within the Paradox platform including adding, retrieving, and deleting location-based access permissions for users.

- **Human URL:** [https://readme.paradox.ai/reference/authentication](https://readme.paradox.ai/reference/authentication)
- **Base URL:** `https://api.paradox.ai/api/v1/public`

#### Tags

- Access Control
- Permissions
- Users

#### Properties

- [Documentation](https://readme.paradox.ai/reference/authentication)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paradox-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paradox-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ParadoxAI)
- [Portal](https://readme.paradox.ai/)
- [Documentation](https://readme.paradox.ai/docs)
- [Authentication](https://readme.paradox.ai/reference/authentication)
- [Changelog](https://readme.paradox.ai/changelog)
- [Status Page](https://status.paradox.ai/)
- [Login](https://olivia.paradox.ai/login)
- [Privacy Policy](https://www.paradox.ai/legal/privacy-policy)
- [Terms of Service](https://www.paradox.ai/legal/service-terms)
- [Security](https://www.paradox.ai/legal/security)
- [F A Q](https://www.paradox.ai/faqs)
- [Integrations](https://www.paradox.ai/partners/integrations)
- [Contact](https://www.paradox.ai/contact)
- [Blog](https://www.paradox.ai/blog)
- [LinkedIn](https://www.linkedin.com/company/paradoxolivia)
- [About](https://www.paradox.ai/about)
- [OpenAPI](openapi/paradox-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N  Schema](json-schema/paradox-candidate-schema.json)
- [J S O N- L D  Context](json-ld/paradox-context.jsonld)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
