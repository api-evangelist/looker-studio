# Looker Studio (looker-studio)

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
