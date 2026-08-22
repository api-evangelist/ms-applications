# Microsoft Applications APIs (ms-applications)

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

Collection of Microsoft application APIs for productivity, collaboration, and enterprise services.

**APIs.json:** [https://developer.microsoft.com](https://developer.microsoft.com)

## Scope

- **Type:** Index

## Tags

- Cloud
- Enterprise
- Microsoft
- Microsoft-365
- Office
- Productivity
- Saas

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### Microsoft Graph API

Unified API endpoint for accessing Microsoft 365 services including users, mail, calendar, contacts, files, and more.

- **Human URL:** [https://developer.microsoft.com/graph](https://developer.microsoft.com/graph)
- **Base URL:** `https://graph.microsoft.com`

#### Tags

- Cloud
- Collaboration
- Identity
- Productivity

#### Properties

- [Documentation](https://docs.microsoft.com/graph/overview)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.microsoft.com/graph/auth/)
- [S D Ks](https://docs.microsoft.com/graph/sdks/sdks-overview)
- [Pricing](https://azure.microsoft.com/pricing/details/active-directory/)
- [Postman Collection](collections/ms-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ms-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Teams API

API for building apps and bots that integrate with Microsoft Teams.

- **Human URL:** [https://developer.microsoft.com/microsoft-teams](https://developer.microsoft.com/microsoft-teams)
- **Base URL:** `https://graph.microsoft.com/v1.0/teams`

#### Tags

- Chat
- Collaboration
- Meetings
- Productivity

#### Properties

- [Documentation](https://docs.microsoft.com/microsoftteams/platform/)
- [Getting Started](https://docs.microsoft.com/microsoftteams/platform/get-started/get-started-overview)
- [Bot  Framework](https://docs.microsoft.com/microsoftteams/platform/bots/what-are-bots)
- [Sample  Apps](https://github.com/OfficeDev/Microsoft-Teams-Samples)
- [Postman Collection](collections/ms-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ms-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Outlook Mail API

API for accessing and managing email messages through Microsoft Outlook.

- **Human URL:** [https://developer.microsoft.com/outlook](https://developer.microsoft.com/outlook)
- **Base URL:** `https://graph.microsoft.com/v1.0/me/messages`

#### Tags

- Email
- Messaging
- Productivity

#### Properties

- [Documentation](https://docs.microsoft.com/graph/api/resources/mail-api-overview)
- [API Reference](https://docs.microsoft.com/graph/api/resources/message)
- [Quick  Start](https://developer.microsoft.com/graph/quick-start)
- [Postman Collection](collections/ms-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ms-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OneDrive API

API for accessing and managing files stored in OneDrive and SharePoint.

- **Human URL:** [https://developer.microsoft.com/onedrive](https://developer.microsoft.com/onedrive)
- **Base URL:** `https://graph.microsoft.com/v1.0/me/drive`

#### Tags

- Cloud
- Collaboration
- Files
- Storage

#### Properties

- [Documentation](https://docs.microsoft.com/onedrive/developer/)
- [API Reference](https://docs.microsoft.com/graph/api/resources/onedrive)
- [File  Picker](https://docs.microsoft.com/onedrive/developer/controls/file-pickers/)
- [Postman Collection](collections/ms-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ms-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SharePoint API

API for accessing SharePoint sites, lists, and content.

- **Human URL:** [https://developer.microsoft.com/sharepoint](https://developer.microsoft.com/sharepoint)
- **Base URL:** `https://graph.microsoft.com/v1.0/sites`

#### Tags

- Collaboration
- Content Management
- Enterprise
- Intranet

#### Properties

- [Documentation](https://docs.microsoft.com/sharepoint/dev/)
- [R E S T  A P I  Reference](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service)
- [Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
- [Postman Collection](collections/ms-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ms-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Active Directory API

API for identity and access management in Azure AD.

- **Human URL:** [https://developer.microsoft.com/identity](https://developer.microsoft.com/identity)
- **Base URL:** `https://graph.microsoft.com/v1.0/users`

#### Tags

- Authentication
- Authorization
- Identity
- Security

#### Properties

- [Documentation](https://docs.microsoft.com/azure/active-directory/develop/)
- [Authentication  Flows](https://docs.microsoft.com/azure/active-directory/develop/authentication-flows-app-scenarios)
- [Microsoft  Identity  Platform](https://docs.microsoft.com/azure/active-directory/develop/v2-overview)
- [Postman Collection](collections/ms-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ms-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft To Do API

API for managing tasks and to-do lists.

- **Human URL:** [https://developer.microsoft.com/graph](https://developer.microsoft.com/graph)
- **Base URL:** `https://graph.microsoft.com/v1.0/me/todo`

#### Tags

- Planning
- Productivity
- Tasks

#### Properties

- [Documentation](https://docs.microsoft.com/graph/api/resources/todo-overview)
- [API Reference](https://docs.microsoft.com/graph/api/resources/todotask)
- [Postman Collection](collections/ms-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ms-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Planner API

API for creating and managing plans, tasks, and team collaboration.

- **Human URL:** [https://developer.microsoft.com/graph](https://developer.microsoft.com/graph)
- **Base URL:** `https://graph.microsoft.com/v1.0/planner`

#### Tags

- Collaboration
- Productivity
- Project Management
- Tasks

#### Properties

- [Documentation](https://docs.microsoft.com/graph/api/resources/planner-overview)
- [API Reference](https://docs.microsoft.com/graph/api/resources/plannertask)
- [Postman Collection](collections/ms-applications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ms-applications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
