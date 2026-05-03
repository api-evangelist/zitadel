# Zitadel (zitadel)
Zitadel is an open source identity infrastructure platform providing secure authentication and user management with built-in support for OAuth 2.0, OpenID Connect, SAML 2.0, SCIM, FIDO2, and passkeys. It offers multi-tenancy, fine-grained authorization, and a comprehensive management API for building and operating identity-first applications. Available as cloud-hosted and self-hosted deployments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Authentication, Authorization, Identity Management, Open Source, OAuth 2.0, OIDC

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-03

## APIs

### Zitadel Management API
The Zitadel Management API provides administrative operations for managing users, organizations, projects, applications, roles, policies, and identity providers within a Zitadel instance. Accessible via REST at /management/v1/ and via gRPC. Supports comprehensive CRUD operations for all identity management resources.

**Human URL:** [https://zitadel.com/docs/reference/api/management](https://zitadel.com/docs/reference/api/management)

#### Tags:

 - Identity Management, Authentication, User Management, Organizations

#### Properties

- [Documentation](https://zitadel.com/docs/reference/api/management)
- [GitHubRepository](https://github.com/zitadel/zitadel)
- [OpenAPI](openapi/zitadel-management-openapi.yml)
- [JSONSchema - User](json-schema/zitadel-management-user-schema.json)
- [JSONSchema - HumanUser](json-schema/zitadel-management-human-user-schema.json)
- [JSONSchema - MachineUser](json-schema/zitadel-management-machine-user-schema.json)
- [JSONSchema - Organization](json-schema/zitadel-management-organization-schema.json)
- [JSONSchema - Project](json-schema/zitadel-management-project-schema.json)
- [JSONSchema - Application](json-schema/zitadel-management-application-schema.json)
- [JSONSchema - ObjectDetails](json-schema/zitadel-management-object-details-schema.json)
- [JSONStructure - User](json-structure/zitadel-management-user-structure.json)
- [JSONStructure - HumanUser](json-structure/zitadel-management-human-user-structure.json)
- [JSONStructure - MachineUser](json-structure/zitadel-management-machine-user-structure.json)
- [JSONStructure - Organization](json-structure/zitadel-management-organization-structure.json)
- [JSONStructure - Project](json-structure/zitadel-management-project-structure.json)
- [JSONStructure - Application](json-structure/zitadel-management-application-structure.json)
- [Example - List Users](examples/zitadel-management-list-users-example.json)
- [Example - Create Human User](examples/zitadel-management-create-human-user-example.json)
- [Example - Create Organization](examples/zitadel-management-create-organization-example.json)
- [Example - Create Project](examples/zitadel-management-create-project-example.json)

### Zitadel Auth API
The Zitadel Auth API provides endpoints for authenticated users to perform operations on their own accounts, including profile management, session handling, MFA setup, and personal data management. Accessible at /auth/v1/.

**Human URL:** [https://zitadel.com/docs/apis/introduction](https://zitadel.com/docs/apis/introduction)

#### Tags:

 - Authentication, User Profile, Session Management, MFA

### Zitadel Admin API
The Zitadel Admin API provides instance-level configuration for Zitadel administrators. Used to configure instance-wide settings, default policies, SMTP, SMS providers, and manage identity providers at the system level. Accessible at /admin/v1/.

**Human URL:** [https://zitadel.com/docs/apis/introduction](https://zitadel.com/docs/apis/introduction)

#### Tags:

 - Administration, Identity Management, Configuration

### Zitadel OIDC / OAuth 2.0
Zitadel implements the OpenID Connect and OAuth 2.0 standards for authentication and authorization flows. Provides authorization code flow, client credentials, device code, token introspection, and userinfo endpoints.

**Human URL:** [https://zitadel.com/docs/guides/integrate/login/oidc](https://zitadel.com/docs/guides/integrate/login/oidc)

#### Tags:

 - OAuth 2.0, OpenID Connect, Authentication, Authorization

### Zitadel SAML API
Zitadel provides SAML 2.0 single sign-on support, enabling enterprises to integrate with Zitadel using SAML identity federation. Accessible at /saml/v2/.

**Human URL:** [https://zitadel.com/docs/guides/integrate/login/saml](https://zitadel.com/docs/guides/integrate/login/saml)

#### Tags:

 - SAML, Single Sign-On, Authentication

## Common Properties

- [Website](https://zitadel.com)
- [Documentation](https://zitadel.com/docs)
- [GitHubOrganization](https://github.com/zitadel)
- [SDK - zitadel-go (Go)](https://github.com/zitadel/zitadel-go)
- [SDK - zitadel-java (Java)](https://github.com/zitadel/zitadel-java)
- [Tools - Terraform Provider for Zitadel](https://github.com/zitadel/terraform-provider-zitadel)
- [Tools - Zitadel Helm Charts](https://github.com/zitadel/zitadel-charts)
- [SignUp](https://zitadel.cloud/ui/register)
- [Pricing](https://zitadel.com/pricing)
- [PrivacyPolicy](https://zitadel.com/legal/privacy-policy)
- [TermsOfService](https://zitadel.com/legal/terms-of-service)
- [License - GNU AGPLv3](https://github.com/zitadel/zitadel/blob/main/LICENSE)
- [JSONLD](json-ld/zitadel-context.jsonld)
- [SpectralRules](rules/zitadel-spectral.yaml)
- [NaftikoCapability](capabilities/identity-onboarding.yaml)
- [Vocabulary](vocabulary/zitadel-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Multi-Tenancy | Native multi-tenant architecture with organizations and projects. |
| OAuth 2.0 / OIDC | Standards-compliant OAuth 2.0 and OpenID Connect support. |
| SAML 2.0 | Enterprise SAML 2.0 single sign-on for identity federation. |
| SCIM | SCIM-based user provisioning from upstream identity providers. |
| FIDO2 / Passkeys | Passwordless authentication with FIDO2 and passkeys. |
| MFA | Multi-factor authentication including TOTP, U2F, and FIDO2. |
| Self-Hosted or Cloud | Deploy as a managed cloud service or self-hosted on Kubernetes. |

## Use Cases

| Name | Description |
|------|-------------|
| Customer Identity | B2C identity for customer-facing applications and portals. |
| Workforce Identity | B2B/B2E identity for employees, contractors, and partners. |
| Machine Identity | Service account identity and OAuth client credentials flow. |
| SaaS Multi-Tenancy | Tenant-isolated identity for multi-tenant SaaS applications. |

## Integrations

| Name | Description |
|------|-------------|
| Terraform | Terraform provider for declarative Zitadel resource management. |
| Kubernetes | Helm charts for Zitadel deployment on Kubernetes. |
| Google Login | External identity provider integration with Google. |
| GitHub Login | External identity provider integration with GitHub. |
| SAML IdPs | Federation with SAML identity providers. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Zitadel Management API](openapi/zitadel-management-openapi.yml)

### JSON Schema

- [User](json-schema/zitadel-management-user-schema.json)
- [HumanUser](json-schema/zitadel-management-human-user-schema.json)
- [MachineUser](json-schema/zitadel-management-machine-user-schema.json)
- [Organization](json-schema/zitadel-management-organization-schema.json)
- [Project](json-schema/zitadel-management-project-schema.json)
- [Application](json-schema/zitadel-management-application-schema.json)
- [ObjectDetails](json-schema/zitadel-management-object-details-schema.json)

### JSON Structure

- [User](json-structure/zitadel-management-user-structure.json)
- [HumanUser](json-structure/zitadel-management-human-user-structure.json)
- [MachineUser](json-structure/zitadel-management-machine-user-structure.json)
- [Organization](json-structure/zitadel-management-organization-structure.json)
- [Project](json-structure/zitadel-management-project-structure.json)
- [Application](json-structure/zitadel-management-application-structure.json)

### JSON-LD

- [Zitadel Context](json-ld/zitadel-context.jsonld)

### Examples

- [List Users](examples/zitadel-management-list-users-example.json)
- [Create Human User](examples/zitadel-management-create-human-user-example.json)
- [Create Organization](examples/zitadel-management-create-organization-example.json)
- [Create Project](examples/zitadel-management-create-project-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Zitadel Management API](capabilities/shared/zitadel-management-api.yaml) — 16 operations for users, organizations, projects, and applications

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Identity Onboarding](capabilities/identity-onboarding.yaml) | zitadel-management-api | 7 | Identity Administrator |

## Vocabulary

- [Zitadel Vocabulary](vocabulary/zitadel-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 16 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Zitadel Spectral Ruleset](rules/zitadel-spectral.yaml) — 7 rules across naming, operation, security, and structure categories enforcing Zitadel API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
