# Kong (kong)

Kong is the AI Connectivity Company. Its platform spans Kong Gateway (the open-source API gateway built on NGINX and Lua), Kong Konnect (the SaaS control plane), Kong AI Gateway (LLM, MCP, and agent-to-agent traffic governance with semantic caching, token budgeting, and prompt firewalls), Kong Agent Gateway, Kong Event Gateway (Kafka-native governance), Kong Mesh (service mesh on Kuma and Envoy), Kong MCP Registry (centralized directory of MCP servers and tools for AI agents), Kong Context Mesh, and Kong Insomnia (API design and testing). Together they unify governance across APIs, real-time event streams, LLM calls, MCP tools, and agent-to-agent communication for the agentic era.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Gateway
- AI Gateway
- AI Connectivity
- Agent Gateway
- Event Gateway
- MCP Registry
- Service Mesh
- LLM
- Kafka
- Konnect
- Open Source

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### Kong Gateway

Kong Gateway is the open-source, lightweight, cloud-native API gateway optimized for microservices, delivering low-latency performance and scalability through a rich plugin ecosystem. It is the data-plane foundation underneath every other Kong product.

- **Human URL:** [https://konghq.com/products/kong-gateway](https://konghq.com/products/kong-gateway)

#### Tags

- API Gateway
- Open Source

#### Properties

- [Documentation](https://developer.konghq.com/gateway/)
- [Getting Started](https://developer.konghq.com/gateway/install/)
- [Changelog](https://developer.konghq.com/gateway/changelog/)
- [GitHub Repository](https://github.com/Kong/kong)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong Gateway Admin API

The Kong Gateway Admin API provides a RESTful interface for configuring and managing Kong Gateway instances, including services, routes, plugins, consumers, certificates, RBAC, workspaces, and event hooks. It is the programmatic surface operators use to configure the gateway directly or via decK declarative configuration.

- **Human URL:** [https://developer.konghq.com/api/gateway/admin-ee/](https://developer.konghq.com/api/gateway/admin-ee/)
- **Base URL:** `https://konghq.com/`

#### Tags

- Admin API
- Configuration
- Gateway
- REST API

#### Properties

- [Documentation](https://developer.konghq.com/api/gateway/admin-ee/3.14/)
- [OpenAPI](openapi/kong-gateway-admin-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/kong-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/kong-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [GitHub Repository](https://github.com/Kong/kong)

### Kong Konnect Platform API

The Kong Konnect Platform API is the unified programmatic surface for the Konnect SaaS control plane. It exposes control planes, API products, developer portals, service catalog, identity and team management, analytics dashboards, audit logging, dedicated cloud gateways, CMEK, Event Gateway configuration, MCP Registry, Mesh Manager, metering & billing, notification hub, and search across the platform — over 20 individual API surfaces under one OpenAPI 3.1 document.

- **Human URL:** [https://developer.konghq.com/api/](https://developer.konghq.com/api/)
- **Base URL:** `https://us.api.konghq.com/`

#### Tags

- Cloud
- Konnect
- Management
- REST API

#### Properties

- [Documentation](https://developer.konghq.com/api/)
- [OpenAPI](openapi/kong-konnect-platform-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://developer.konghq.com/api/)
- [Authentication](https://developer.konghq.com/konnect-platform/personal-access-tokens/)
- [SDK](https://github.com/Kong/sdk-konnect-go)

### Kong AI Gateway

Kong AI Gateway is the connectivity and governance layer for AI-native applications. Built on Kong Gateway, it provides a universal LLM API across providers (OpenAI, Anthropic, Gemini, Bedrock, Azure AI, Databricks, Mistral, HuggingFace and more), semantic caching, prompt firewalls and PII guardrails, automated RAG injection, token-level observability, MCP traffic governance, and Agent Gateway support for agent-to-agent (A2A) communication.

- **Human URL:** [https://konghq.com/products/kong-ai-gateway](https://konghq.com/products/kong-ai-gateway)

#### Tags

- AI Gateway
- LLM
- MCP
- A2A

#### Properties

- [Documentation](https://developer.konghq.com/ai-gateway/)
- [Changelog](https://developer.konghq.com/gateway/changelog/)
- [GitHub Repository](https://github.com/Kong/kong)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong Agent Gateway

Kong Agent Gateway is a capability of Kong AI Gateway (GA April 2026 with AI Gateway 3.14) that governs agent-to-agent (A2A) communication. It enforces agent identity verification, real-time policy and prompt-injection inspection, per-agent cost allocation, and unified observability across LLM calls, MCP tool invocations, and A2A messages.

- **Human URL:** [https://konghq.com/blog/product-releases/kong-agent-gateway](https://konghq.com/blog/product-releases/kong-agent-gateway)

#### Tags

- Agent Gateway
- A2A
- AI Gateway

#### Properties

- [Documentation](https://developer.konghq.com/ai-gateway/)
- [Blog](https://konghq.com/blog/product-releases/kong-agent-gateway)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong Event Gateway

Kong Event Gateway is a Kafka-native gateway that proxies the native Kafka protocol between producers, consumers, and backend clusters. It governs Kafka traffic through virtual clusters, listener-level policies, identity-aware ACLs, mTLS, and per-topic quotas — bringing the same governance pattern Kong Gateway provides for HTTP/gRPC to real-time event streams.

- **Human URL:** [https://konghq.com/products/event-gateway](https://konghq.com/products/event-gateway)
- **Base URL:** `https://konghq.com/`

#### Tags

- Event Gateway
- Kafka
- Streaming
- Governance

#### Properties

- [Documentation](https://developer.konghq.com/event-gateway/)
- [OpenAPI](https://developer.konghq.com/api/konnect/event-gateway/v1/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong MCP Registry

Kong MCP Registry (launched February 2026) is an enterprise directory inside Kong Konnect for registering, discovering, and governing MCP servers and AI-native tools. It provides dynamic discovery for AI agents, governance gates on which MCP resources are approved for use, and centralized observability of tool usage, health, and failures.

- **Human URL:** [https://konghq.com/products/mcp-registry](https://konghq.com/products/mcp-registry)

#### Tags

- MCP
- Registry
- Konnect
- Agentic AI

#### Properties

- [Documentation](https://developer.konghq.com/)
- [Blog](https://konghq.com/blog/product-releases/kong-mcp-registry-tech-preview)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong Context Mesh

Kong Context Mesh (launched February 2026, tech preview in Konnect) automatically discovers enterprise APIs, transforms them into agent-consumable tooling, packages them as MCP definitions with schemas and authentication, and publishes them to Kong AI Gateway with inherited access controls and runtime policy enforcement.

- **Human URL:** [https://konghq.com/blog/product-releases/introducing-kong-context-mesh](https://konghq.com/blog/product-releases/introducing-kong-context-mesh)

#### Tags

- Context Mesh
- MCP
- Agentic AI
- Konnect

#### Properties

- [Blog](https://konghq.com/blog/product-releases/introducing-kong-context-mesh)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong Mesh

Kong Mesh is an enterprise-grade service mesh built on Kuma and Envoy, providing universal service mesh capabilities across Kubernetes and virtual machine environments. It supports mTLS, traffic policies, service discovery, observability, and multi-zone deployments.

- **Human URL:** [https://developer.konghq.com/mesh/](https://developer.konghq.com/mesh/)
- **Base URL:** `https://konghq.com/`

#### Tags

- Envoy
- Kubernetes
- mTLS
- Service Mesh

#### Properties

- [Documentation](https://developer.konghq.com/mesh/)
- [Changelog](https://developer.konghq.com/mesh/changelog/)
- [Getting Started](https://developer.konghq.com/mesh/)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong Insomnia

Kong Insomnia is an open-source API development platform for designing, debugging, and testing APIs. It supports REST, GraphQL, gRPC, and WebSocket protocols and provides collections, environments, mock servers, OpenAPI editing, Git Sync, and native vault integrations for developers and platform teams.

- **Human URL:** [https://developer.konghq.com/insomnia/](https://developer.konghq.com/insomnia/)
- **Base URL:** `https://konghq.com/`

#### Tags

- API Client
- Developer Tools
- Open Source
- Testing

#### Properties

- [Documentation](https://developer.konghq.com/insomnia/)
- [GitHub Repository](https://github.com/Kong/insomnia)
- [Postman Collection](collections/kong-gateway-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-gateway-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kong-konnect-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kong-konnect-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/konghq)
- [Documentation](https://developer.konghq.com/)
- [Getting Started](https://developer.konghq.com/gateway/install/)
- [Blog](https://konghq.com/blog)
- [Changelog](https://developer.konghq.com/gateway/changelog/)
- [GitHub Organization](https://github.com/Kong)
- [GitHub Repository](https://github.com/Kong/kong)
- [SDK](https://github.com/Kong/sdk-konnect-go)
- [SDK](https://github.com/Kong/sdk-portal-js)
- [C L I](https://github.com/Kong/kongctl)
- [Support](https://discuss.konghq.com/)
- [Pricing](https://konghq.com/pricing)
- [Plans](plans/kong-plans-pricing.yml)
- [Rate Limits](rate-limits/kong-rate-limits.yml)
- [Fin Ops](finops/kong-finops.yml)
- [JSON Schema](json-schema/kong-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/kong-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [M C P Server](https://github.com/Kong/mcp-konnect)
- [L L Ms Txt](https://developer.konghq.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
