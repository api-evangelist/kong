# Kong (kong)
Kong Gateway is the world's most popular open-source API gateway, built on NGINX and Lua, offering a plugin ecosystem for authentication, rate limiting, observability, and traffic management at any scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Gateway, Lua, NGINX, Open Source

## Timestamps

- **Created:** 2026-03-18 
- **Modified:** 2026-04-18 

## APIs

### Kong Gateway
Kong Gateway is an open-source, lightweight API gateway optimized for microservices, delivering unparalleled latency performance and scalability through a rich plugin ecosystem.

**Human URL:** [https://konghq.com/products/kong-gateway](https://konghq.com/products/kong-gateway)

#### Tags:

 - API Gateway, Open Source

#### Properties

- [Documentation](https://developer.konghq.com/gateway/)
- [GettingStarted](https://docs.konghq.com/gateway/latest/get-started/)
- [ChangeLog](https://developer.konghq.com/gateway/changelog/)
- [GitHubRepository](https://github.com/Kong/kong)

### Kong Gateway Admin API
The Kong Gateway Admin API provides a RESTful interface for configuring and managing Kong Gateway instances, including services, routes, plugins, consumers, and certificates. It is used by operators to configure the gateway programmatically or via decK declarative configuration.

**Human URL:** [https://developer.konghq.com/admin-api/](https://developer.konghq.com/admin-api/)

#### Tags:

 - Admin API, Configuration, Gateway, REST API

#### Properties

- [Documentation](https://developer.konghq.com/admin-api/)
- [OpenAPI](openapi/kong-gateway-admin-api.yml)
- [JSONSchema](json-schema/kong-service-schema.json)
- [JSONLD](json-ld/kong-context.jsonld)
- [GitHubRepository](https://github.com/Kong/kong)

### Kong Konnect API
The Kong Konnect API provides a programmatic interface for managing the Konnect cloud platform, including control planes, API products, teams, system accounts, and developer portal configuration. It is used to automate Konnect operations and integrate with CI/CD pipelines.

**Human URL:** [https://developer.konghq.com/konnect-api/](https://developer.konghq.com/konnect-api/)

#### Tags:

 - Cloud, Konnect, Management, REST API

#### Properties

- [Documentation](https://developer.konghq.com/konnect-api/)
- [APIReference](https://developer.konghq.com/api/)
- [Authentication](https://developer.konghq.com/konnect-api/)
- [GitHubRepository](https://github.com/Kong/kong)

### Kong Mesh
Kong Mesh is an enterprise-grade service mesh built on top of Kuma and Envoy, providing universal service mesh capabilities across Kubernetes and virtual machine environments. It supports mTLS, traffic policies, service discovery, observability, and multi-zone deployments.

**Human URL:** [https://developer.konghq.com/mesh/](https://developer.konghq.com/mesh/)

#### Tags:

 - Envoy, Kubernetes, mTLS, Service Mesh

#### Properties

- [Documentation](https://developer.konghq.com/mesh/)
- [ChangeLog](https://developer.konghq.com/mesh/changelog/)
- [GettingStarted](https://developer.konghq.com/mesh/)

### Kong Insomnia
Kong Insomnia is an open-source API development platform for designing, debugging, and testing APIs. It supports REST, GraphQL, gRPC, and WebSocket protocols and provides collections, environments, mock servers, and OpenAPI spec editing for developers.

**Human URL:** [https://developer.konghq.com/insomnia/](https://developer.konghq.com/insomnia/)

#### Tags:

 - API Client, Developer Tools, Open Source, Testing

#### Properties

- [Documentation](https://developer.konghq.com/insomnia/)
- [GitHubRepository](https://github.com/Kong/insomnia)

## Common Properties

- [Documentation](https://developer.konghq.com/)
- [GettingStarted](https://docs.konghq.com/gateway/latest/get-started/)
- [Blog](https://konghq.com/blog)
- [ChangeLog](https://developer.konghq.com/gateway/changelog/)
- [GitHubOrganization](https://github.com/Kong)
- [GitHubRepository](https://github.com/Kong/kong)
- [SDK](https://github.com/Kong/sdk-konnect-go)
- [CLI](https://github.com/Kong/kongctl)
- [Support](https://discuss.konghq.com/)

## Features

| Name | Description |
|------|-------------|
| Plugin Ecosystem | Extensible plugin architecture for authentication, rate limiting, logging, transformations, and custom business logic. |
| Service and Route Management | Define upstream services and routing rules to direct client requests to the correct backend services. |
| Consumer Management | Create and manage API consumers with per-consumer authentication credentials and plugin configurations. |
| Load Balancing | Built-in upstream load balancing with health checks, circuit breaking, and weighted target distribution. |
| TLS Certificate Management | Manage TLS certificates and SNI mappings for secure HTTPS traffic termination at the gateway. |
| Declarative Configuration | Configure Kong Gateway declaratively using decK or the Admin API for infrastructure-as-code workflows. |
| Kong Konnect Cloud Platform | Centralized cloud control plane for managing multiple Kong Gateway instances, teams, and API products. |
| Service Mesh with Kong Mesh | Enterprise service mesh built on Kuma and Envoy for mTLS, traffic policies, and multi-zone deployments. |

## Use Cases

| Name | Description |
|------|-------------|
| API Gateway for Microservices | Route, secure, and observe traffic to microservices with authentication, rate limiting, and request transformations. |
| Multi-Cloud API Management | Manage APIs across hybrid and multi-cloud environments with centralized control through Kong Konnect. |
| Zero-Trust Security | Implement zero-trust security with mTLS, OAuth2, JWT validation, and API key authentication at the gateway layer. |
| API Lifecycle Management | Manage the full API lifecycle from design with Insomnia to deployment and monitoring with Kong Gateway. |
| Rate Limiting and Traffic Control | Protect backend services with configurable rate limiting, request size limits, and traffic shaping policies. |

## Integrations

| Name | Description |
|------|-------------|
| Kubernetes | Deploy Kong Gateway as a Kubernetes Ingress Controller with CRD-based configuration for cloud-native environments. |
| Prometheus and Grafana | Export gateway metrics to Prometheus and visualize API performance and health in Grafana dashboards. |
| OpenTelemetry | Distributed tracing integration with OpenTelemetry for end-to-end request visibility across services. |
| HashiCorp Vault | Secrets management integration for storing and retrieving API keys, certificates, and credentials. |
| Datadog | Send gateway logs, metrics, and traces to Datadog for comprehensive API monitoring and alerting. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Kong Gateway Admin API](openapi/kong-gateway-admin-api.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Kong Gateway Admin API](capabilities/shared/kong-admin.yaml) -- 50 operations for gateway configuration

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Gateway Management](capabilities/api-gateway-management.yaml) | Kong Admin | 26 | Platform Engineer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
