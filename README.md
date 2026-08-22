# Zitadel (zitadel)

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

Zitadel is an open source identity infrastructure platform providing secure authentication and user management with built-in support for OAuth 2.0, OpenID Connect, SAML 2.0, SCIM, FIDO2, and passkeys. It offers multi-tenancy, fine-grained authorization, and a comprehensive management API for building and operating identity-first applications. Available as cloud-hosted and self-hosted deployments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Authentication
- Authorization
- Identity Management
- Open Source
- OAuth 2.0
- OIDC

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-19

## APIs

### Zitadel Management API

The Zitadel Management API provides administrative operations for managing users, organizations, projects, applications, roles, policies, and identity providers within a Zitadel instance. Accessible via REST at /management/v1/ and via gRPC. Supports comprehensive CRUD operations for all identity management resources.

- **Human URL:** [https://zitadel.com/docs/reference/api/management](https://zitadel.com/docs/reference/api/management)

#### Tags

- Identity Management
- Authentication
- User Management
- Organizations

#### Properties

- [Documentation](https://zitadel.com/docs/reference/api/management)
- [GitHub Repository](https://github.com/zitadel/zitadel)
- [OpenAPI](openapi/zitadel-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zitadel-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zitadel-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/zitadel-management-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zitadel-management-human-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zitadel-management-machine-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zitadel-management-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zitadel-management-project-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zitadel-management-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/zitadel-management-object-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/zitadel-management-user-structure.json)
- [JSON Structure](json-structure/zitadel-management-human-user-structure.json)
- [JSON Structure](json-structure/zitadel-management-machine-user-structure.json)
- [JSON Structure](json-structure/zitadel-management-organization-structure.json)
- [JSON Structure](json-structure/zitadel-management-project-structure.json)
- [JSON Structure](json-structure/zitadel-management-application-structure.json)
- [Example](examples/zitadel-management-list-users-example.json)
- [Example](examples/zitadel-management-create-human-user-example.json)
- [Example](examples/zitadel-management-create-organization-example.json)
- [Example](examples/zitadel-management-create-project-example.json)

### Zitadel Auth API

The Zitadel Auth API provides endpoints for authenticated users to perform operations on their own accounts, including profile management, session handling, MFA setup, and personal data management. Accessible at /auth/v1/.

- **Human URL:** [https://zitadel.com/docs/apis/introduction](https://zitadel.com/docs/apis/introduction)

#### Tags

- Authentication
- User Profile
- Session Management
- MFA

#### Properties

- [Documentation](https://zitadel.com/docs/apis/introduction)
- [Postman Collection](collections/zitadel-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zitadel-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zitadel Admin API

The Zitadel Admin API provides instance-level configuration for Zitadel administrators. Used to configure instance-wide settings, default policies, SMTP, SMS providers, and manage identity providers at the system level. Accessible at /admin/v1/.

- **Human URL:** [https://zitadel.com/docs/apis/introduction](https://zitadel.com/docs/apis/introduction)

#### Tags

- Administration
- Identity Management
- Configuration

#### Properties

- [Documentation](https://zitadel.com/docs/apis/introduction)
- [Postman Collection](collections/zitadel-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zitadel-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zitadel OIDC / OAuth 2.0

Zitadel implements the OpenID Connect and OAuth 2.0 standards for authentication and authorization flows. Provides authorization code flow, client credentials, device code, token introspection, and userinfo endpoints. Available at /oauth/v2/ and /oidc/v1/.

- **Human URL:** [https://zitadel.com/docs/guides/integrate/login/oidc](https://zitadel.com/docs/guides/integrate/login/oidc)

#### Tags

- OAuth 2.0
- OpenID Connect
- Authentication
- Authorization

#### Properties

- [Documentation](https://zitadel.com/docs/guides/integrate/login/oidc)
- [Postman Collection](collections/zitadel-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zitadel-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zitadel SAML API

Zitadel provides SAML 2.0 single sign-on support, enabling enterprises to integrate with Zitadel using SAML identity federation. Accessible at /saml/v2/.

- **Human URL:** [https://zitadel.com/docs/guides/integrate/login/saml](https://zitadel.com/docs/guides/integrate/login/saml)

#### Tags

- SAML
- Single Sign-On
- Authentication

#### Properties

- [Documentation](https://zitadel.com/docs/guides/integrate/login/saml)
- [Postman Collection](collections/zitadel-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zitadel-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/zitadel)
- [Website](https://zitadel.com)
- [Documentation](https://zitadel.com/docs)
- [GitHub Organization](https://github.com/zitadel)
- [SDK](https://github.com/zitadel/zitadel-go)
- [SDK](https://github.com/zitadel/zitadel-java)
- [Tools](https://github.com/zitadel/terraform-provider-zitadel)
- [Tools](https://github.com/zitadel/zitadel-charts)
- [Sign Up](https://zitadel.cloud/ui/register)
- [Pricing](https://zitadel.com/pricing)
- [Privacy Policy](https://zitadel.com/legal/privacy-policy)
- [Terms of Service](https://zitadel.com/legal/terms-of-service)
- [License](https://github.com/zitadel/zitadel/blob/main/LICENSE)
- [JSON-LD](json-ld/zitadel-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/zitadel-spectral.yaml)
- [Vocabulary](vocabulary/zitadel-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
