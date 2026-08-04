# PowerPoint (powerpoint)

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

Microsoft PowerPoint provides programmatic access through the Microsoft Graph API and the Office JavaScript API for creating, reading, and manipulating PowerPoint presentations. PowerPoint files stored in OneDrive and SharePoint are accessible as drive items via Microsoft Graph, while the Office JavaScript API enables in-document automation for Office Add-ins.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/powerpoint/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/powerpoint/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Microsoft Office
- Microsoft 365
- Presentations
- Productivity
- Documents

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### PowerPoint via Microsoft Graph

Microsoft Graph exposes PowerPoint presentation files (.pptx) stored in OneDrive and SharePoint as drive items, enabling upload, download, sharing, and metadata operations against presentations programmatically.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/driveitem](https://learn.microsoft.com/en-us/graph/api/resources/driveitem)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Microsoft Graph
- Files
- Presentations

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/driveitem)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Postman Collection](collections/powerpoint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/powerpoint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Office JavaScript API for PowerPoint

Office JavaScript API namespace for building PowerPoint Add-ins that read, write, and manipulate slides, shapes, text, and tables inside the running PowerPoint application.

- **Human URL:** [https://learn.microsoft.com/en-us/javascript/api/powerpoint](https://learn.microsoft.com/en-us/javascript/api/powerpoint)

#### Tags

- Office Add-ins
- JavaScript
- Presentations

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/javascript/api/powerpoint)
- [SDK](https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/powerpoint-quickstart)
- [Postman Collection](collections/powerpoint.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/powerpoint.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.microsoft.com/en-us/microsoft-365/powerpoint)
- [Documentation](https://learn.microsoft.com/en-us/graph/overview)
- [Developer](https://learn.microsoft.com/en-us/office/dev/add-ins/)
- [Integrations](https://www.microsoft.com/en-us/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
