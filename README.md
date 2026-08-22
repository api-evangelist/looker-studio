# Looker Studio (looker-studio)

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

Looker Studio (formerly Google Data Studio) is a free tool that turns your data into informative, easy to read, easy to share, and fully customizable dashboards and reports. The API allows developers to programmatically manage assets, build custom connectors and visualizations, embed reports, and automate workflows.

**APIs.json:** [https://lookerstudio.google.com](https://lookerstudio.google.com)

## Tags

- Analytics
- Business Intelligence
- Dashboards
- Data Visualization
- Google
- Reports

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Looker Studio API

The Looker Studio API enables developers to programmatically manage reports, data sources, and permissions. It provides methods for searching assets and managing asset permissions including getting, updating, adding, and removing members.

- **Human URL:** [https://developers.google.com/looker-studio/integrate/api](https://developers.google.com/looker-studio/integrate/api)
- **Base URL:** `https://datastudio.googleapis.com/v1`

#### Tags

- Assets
- Automation
- Data Sources
- Permissions
- Reports

#### Properties

- [Documentation](https://developers.google.com/looker-studio/integrate/api)
- [Reference](https://developers.google.com/looker-studio/integrate/api/reference)
- [OpenAPI](openapi/looker-studio-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/looker-studio-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-studio-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://lookerstudio.googleapis.com/$discovery/rest?version=v1) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developers.google.com/looker-studio/api/authentication)
- [Getting Started](https://developers.google.com/looker-studio/api/quickstart)
- [S D Ks](https://developers.google.com/looker-studio/api/client-libraries)
- [Rate Limits](https://developers.google.com/looker-studio/api/quotas)
- [Errors](https://developers.google.com/looker-studio/api/errors)
- [J S O N  Schema](json-schema/looker-studio-asset-schema.json)
- [J S O N  Schema](json-schema/looker-studio-permissions-schema.json)
- [J S O N  Schema](json-schema/looker-studio-report-schema.json)
- [J S O N  Schema](json-schema/looker-studio-data-source-schema.json)

### Looker Studio Linking API

The Looker Studio Linking API enables the creation of dynamic URLs that link to pre-configured reports. It allows developers to define data sources, control report behavior, and customize settings through URL parameters.

- **Human URL:** [https://developers.google.com/looker-studio/integrate/linking-api](https://developers.google.com/looker-studio/integrate/linking-api)
- **Base URL:** `https://lookerstudio.google.com`

#### Tags

- Data Sources
- Integration
- Linking
- Reports
- URL Parameters

#### Properties

- [Documentation](https://developers.google.com/looker-studio/integrate/linking-api)
- [OpenAPI](openapi/looker-studio-linking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/looker-studio-linking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-studio-linking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Looker Studio Embedding API

Embed Looker Studio reports in your applications using HTML iframe tags, oEmbed, and Open Graph Tags with customizable parameters and filtering options. Supports embedding on platforms like Medium and Reddit.

- **Human URL:** [https://developers.google.com/looker-studio/integrate/embed](https://developers.google.com/looker-studio/integrate/embed)
- **Base URL:** `https://lookerstudio.google.com/embed`

#### Tags

- Embedding
- Iframe
- Integration
- Reports
- Sharing

#### Properties

- [Documentation](https://developers.google.com/looker-studio/integrate/embed)
- [OpenAPI](openapi/looker-studio-embedding-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/looker-studio-embedding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-studio-embedding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://developers.google.com/looker-studio/integrate/embedding-api/get-started)
- [Security](https://developers.google.com/looker-studio/connector/embed-row-level-security)

### Looker Studio Community Connector API

Build custom data connectors to bring data from any source into Looker Studio. Connectors are built using Google Apps Script and implement three core functions: getConfig(), getSchema(), and getData().

- **Human URL:** [https://developers.google.com/looker-studio/connector](https://developers.google.com/looker-studio/connector)
- **Base URL:** `https://datastudio.google.com/datasources/create`

#### Tags

- Apps Script
- Connectors
- Custom Integration
- Data Sources
- ETL

#### Properties

- [Documentation](https://developers.google.com/looker-studio/connector)
- [Reference](https://developers.google.com/looker-studio/connector/reference)
- [OpenAPI](openapi/looker-studio-community-connector-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/looker-studio-community-connector-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-studio-community-connector-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://developers.google.com/looker-studio/connector/build)
- [Examples](https://developers.google.com/looker-studio/connector/examples)
- [Gallery](https://lookerstudio.google.com/data)
- [Changelog](https://developers.google.com/looker-studio/connector/changelog)
- [Publishing](https://developers.google.com/looker-studio/connector/publish-connector)
- [Sharing](https://developers.google.com/looker-studio/connector/share)
- [Direct  Links](https://developers.google.com/looker-studio/connector/direct-links)
- [Codelabs](https://codelabs.developers.google.com/codelabs/community-connectors)
- [J S O N  Schema](json-schema/looker-studio-connector-schema.json)

### Looker Studio Community Visualization API

Build and deploy custom visualizations for Looker Studio using any JavaScript visualization library. The dscc helper library simplifies development by providing functions for data subscriptions, component dimensions, and user interactions.

- **Human URL:** [https://developers.google.com/looker-studio/visualization](https://developers.google.com/looker-studio/visualization)
- **Base URL:** `https://lookerstudio.google.com/visualization`

#### Tags

- Components
- Custom Charts
- Data Visualization
- JavaScript
- Visualizations

#### Properties

- [Documentation](https://developers.google.com/looker-studio/visualization)
- [Reference](https://developers.google.com/looker-studio/visualization/library-reference)
- [OpenAPI](openapi/looker-studio-community-visualization-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/looker-studio-community-visualization-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/looker-studio-community-visualization-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://developers.google.com/looker-studio/visualization/write-viz)
- [S D Ks](https://developers.google.com/looker-studio/visualization/library)
- [Local  Development](https://developers.google.com/looker-studio/visualization/local-dev)
- [Open  Source](https://developers.google.com/looker-studio/visualization/open-source)
- [Interactions](https://developers.google.com/looker-studio/visualization/interactions-guide)
- [Support](https://developers.google.com/looker-studio/visualization/support)
- [Codelabs](https://codelabs.developers.google.com/codelabs/community-visualization)
- [J S O N  Schema](json-schema/looker-studio-visualization-schema.json)

## Common Properties

- [Portal](https://console.cloud.google.com)
- [Documentation](https://docs.cloud.google.com/looker/docs/studio)
- [Getting Started](https://support.google.com/looker-studio/answer/6283323)
- [Authentication](https://developers.google.com/identity/protocols/oauth2)
- [Blog](https://cloud.google.com/blog/products/data-analytics)
- [Status Page](https://status.cloud.google.com)
- [Support](https://cloud.google.com/looker/docs/studio/contact-us)
- [Terms of Service](https://policies.google.com/terms)
- [Privacy Policy](https://policies.google.com/privacy)
- [GitHub Organization](https://github.com/looker-open-source)
- [Community](https://www.googlecloudcommunity.com/gc/Looker-Looker-Studio/ct-p/looker)
- [Website](https://lookerstudio.google.com)
- [Login](https://lookerstudio.google.com/?requirelogin=1)
- [Sign Up](https://lookerstudio.google.com)
- [Pricing](https://support.google.com/looker-studio/answer/9171315)
- [Release Notes](https://docs.cloud.google.com/looker-studio/docs/release-notes)
- [Errors](https://developers.google.com/looker-studio/api/errors)
- [Developer  Forum](https://discuss.google.dev/c/looker/looker-q-a/looker-studio/214)
- [Developers](https://developers.google.com/looker-studio)
- [Publishing](https://developers.google.com/looker-studio/integrate)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
