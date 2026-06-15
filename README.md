# Zitadel (zitadel)

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
