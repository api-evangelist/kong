# Kong (kong)
Kong is the AI Connectivity Company. Its platform spans Kong Gateway (open-source API gateway on NGINX and Lua), Kong Konnect (SaaS control plane), Kong AI Gateway (LLM, MCP, and agent-to-agent governance), Kong Agent Gateway, Kong Event Gateway (Kafka-native governance), Kong Mesh (service mesh on Kuma and Envoy), Kong MCP Registry, Kong Context Mesh, and Kong Insomnia (API design and testing). Together they unify governance across APIs, real-time event streams, LLM calls, MCP tools, and agent-to-agent communication for the agentic era.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Gateway, AI Gateway, AI Connectivity, Agent Gateway, Event Gateway, MCP Registry, Service Mesh, LLM, Kafka, Konnect, Open Source

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-15

## APIs

### Kong Gateway
Open-source, lightweight, cloud-native API gateway optimized for microservices, delivering low-latency performance and scalability through a rich plugin ecosystem. The data-plane foundation under every other Kong product.

**Human URL:** [https://konghq.com/products/kong-gateway](https://konghq.com/products/kong-gateway)

#### Tags:

 - API Gateway, Open Source

#### Properties

- [Documentation](https://developer.konghq.com/gateway/)
- [GettingStarted](https://developer.konghq.com/gateway/install/)
- [ChangeLog](https://developer.konghq.com/gateway/changelog/)
- [GitHubRepository](https://github.com/Kong/kong)

### Kong Gateway Admin API
RESTful interface for configuring and managing Kong Gateway instances — services, routes, plugins, consumers, certificates, RBAC, workspaces, event hooks. The programmatic surface operators use directly or via decK declarative configuration.

**Human URL:** [https://developer.konghq.com/api/gateway/admin-ee/](https://developer.konghq.com/api/gateway/admin-ee/)

#### Tags:

 - Admin API, Configuration, Gateway, REST API

#### Properties

- [Documentation](https://developer.konghq.com/api/gateway/admin-ee/3.14/)
- [OpenAPI](openapi/kong-gateway-admin-api.yml)
- [JSONSchema](json-schema/kong-service-schema.json)
- [JSONLD](json-ld/kong-context.jsonld)
- [GitHubRepository](https://github.com/Kong/kong)

### Kong Konnect Platform API
Unified programmatic surface for the Konnect SaaS control plane — control planes, API products, developer portals, service catalog, identity and team management, analytics dashboards, audit logging, dedicated cloud gateways, CMEK, Event Gateway, MCP Registry, Mesh Manager, metering & billing, notification hub, search. Over 20 individual API surfaces under one OpenAPI 3.1 document.

**Human URL:** [https://developer.konghq.com/api/](https://developer.konghq.com/api/)

#### Tags:

 - Cloud, Konnect, Management, REST API

#### Properties

- [Documentation](https://developer.konghq.com/api/)
- [OpenAPI](openapi/kong-konnect-platform-api.yml)
- [APIReference](https://developer.konghq.com/api/)
- [Authentication](https://developer.konghq.com/konnect-platform/personal-access-tokens/)
- [SDK](https://github.com/Kong/sdk-konnect-go)

### Kong AI Gateway
Connectivity and governance layer for AI-native applications, built on Kong Gateway. Universal LLM API across OpenAI, Anthropic, Gemini, Bedrock, Azure AI, Databricks, Mistral, HuggingFace and more, with semantic caching, prompt firewalls, PII guardrails, automated RAG injection, token-level observability, MCP traffic governance, and Agent Gateway support for A2A communication.

**Human URL:** [https://konghq.com/products/kong-ai-gateway](https://konghq.com/products/kong-ai-gateway)

#### Tags:

 - AI Gateway, LLM, MCP, A2A

#### Properties

- [Documentation](https://developer.konghq.com/ai-gateway/)
- [ChangeLog](https://developer.konghq.com/gateway/changelog/)
- [GitHubRepository](https://github.com/Kong/kong)

### Kong Agent Gateway
Capability of Kong AI Gateway (GA April 2026 with AI Gateway 3.14) that governs agent-to-agent (A2A) communication. Enforces agent identity verification, real-time policy and prompt-injection inspection, per-agent cost allocation, and unified observability across LLM calls, MCP tool invocations, and A2A messages.

**Human URL:** [https://konghq.com/blog/product-releases/kong-agent-gateway](https://konghq.com/blog/product-releases/kong-agent-gateway)

#### Tags:

 - Agent Gateway, A2A, AI Gateway

#### Properties

- [Documentation](https://developer.konghq.com/ai-gateway/)
- [Blog](https://konghq.com/blog/product-releases/kong-agent-gateway)

### Kong Event Gateway
Kafka-native gateway that proxies the native Kafka protocol between producers, consumers, and backend clusters. Governs Kafka through virtual clusters, listener-level policies, identity-aware ACLs, mTLS, and per-topic quotas — bringing Kong's HTTP/gRPC governance pattern to real-time event streams.

**Human URL:** [https://konghq.com/products/event-gateway](https://konghq.com/products/event-gateway)

#### Tags:

 - Event Gateway, Kafka, Streaming, Governance

#### Properties

- [Documentation](https://developer.konghq.com/event-gateway/)
- [OpenAPI](https://developer.konghq.com/api/konnect/event-gateway/v1/)

### Kong MCP Registry
Enterprise directory inside Kong Konnect for registering, discovering, and governing MCP servers and AI-native tools. Provides dynamic discovery for AI agents, governance gates on which MCP resources are approved, and centralized observability of tool usage, health, and failures. Launched February 2026.

**Human URL:** [https://konghq.com/products/mcp-registry](https://konghq.com/products/mcp-registry)

#### Tags:

 - MCP, Registry, Konnect, Agentic AI

#### Properties

- [Documentation](https://developer.konghq.com/)
- [Blog](https://konghq.com/blog/product-releases/kong-mcp-registry-tech-preview)

### Kong Context Mesh
Automatically discovers enterprise APIs, transforms them into agent-consumable tooling, packages them as MCP definitions with schemas and authentication, and publishes them to Kong AI Gateway with inherited access controls and runtime policy enforcement. Tech preview in Konnect since February 2026.

**Human URL:** [https://konghq.com/blog/product-releases/introducing-kong-context-mesh](https://konghq.com/blog/product-releases/introducing-kong-context-mesh)

#### Tags:

 - Context Mesh, MCP, Agentic AI, Konnect

#### Properties

- [Blog](https://konghq.com/blog/product-releases/introducing-kong-context-mesh)

### Kong Mesh
Enterprise-grade service mesh built on Kuma and Envoy. Provides universal service mesh capabilities across Kubernetes and VM environments — mTLS, traffic policies, service discovery, observability, multi-zone deployments.

**Human URL:** [https://developer.konghq.com/mesh/](https://developer.konghq.com/mesh/)

#### Tags:

 - Envoy, Kubernetes, mTLS, Service Mesh

#### Properties

- [Documentation](https://developer.konghq.com/mesh/)
- [ChangeLog](https://developer.konghq.com/mesh/changelog/)
- [GettingStarted](https://developer.konghq.com/mesh/)

### Kong Insomnia
Open-source API development platform for designing, debugging, and testing APIs. Supports REST, GraphQL, gRPC, and WebSocket; provides collections, environments, mock servers, OpenAPI editing, Git Sync, and native vault integrations.

**Human URL:** [https://developer.konghq.com/insomnia/](https://developer.konghq.com/insomnia/)

#### Tags:

 - API Client, Developer Tools, Open Source, Testing

#### Properties

- [Documentation](https://developer.konghq.com/insomnia/)
- [GitHubRepository](https://github.com/Kong/insomnia)

## Common Properties

- [Documentation](https://developer.konghq.com/)
- [GettingStarted](https://developer.konghq.com/gateway/install/)
- [Blog](https://konghq.com/blog)
- [ChangeLog](https://developer.konghq.com/gateway/changelog/)
- [GitHubOrganization](https://github.com/Kong)
- [GitHubRepository](https://github.com/Kong/kong)
- [SDK: Kong Konnect Go SDK](https://github.com/Kong/sdk-konnect-go)
- [SDK: Kong Portal JS SDK](https://github.com/Kong/sdk-portal-js)
- [CLI: Kong Developer CLI](https://github.com/Kong/kongctl)
- [Support](https://discuss.konghq.com/)
- [Pricing](https://konghq.com/pricing)
- [Plans](plans/kong-plans-pricing.yml)
- [RateLimits](rate-limits/kong-rate-limits.yml)
- [FinOps](finops/kong-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Plugin Ecosystem | Authentication, rate limiting, logging, transformations, custom business logic. |
| Service and Route Management | Define upstream services and routing rules. |
| Consumer Management | Per-consumer authentication credentials and plugin configurations. |
| Load Balancing | Health checks, circuit breaking, weighted target distribution. |
| TLS Certificate Management | Certificates and SNI mappings for HTTPS termination. |
| Declarative Configuration | decK / Admin API infrastructure-as-code workflows. |
| Kong Konnect Cloud Platform | Centralized control plane for gateways, teams, products, Dev Portals. |
| Universal LLM API | Provider-agnostic LLM proxy with semantic caching and token-level governance. |
| MCP Registry and Tool Governance | Centralized directory of MCP servers and tools agents can discover, with approval enforcement. |
| Agent-to-Agent Governance | Kong Agent Gateway provides identity, policy, and observability for A2A traffic inside AI Gateway 3.14+. |
| Kafka-Native Event Governance | Kong Event Gateway proxies native Kafka with virtual clusters, identity-aware ACLs, and quotas. |
| Service Mesh with Kong Mesh | Kuma + Envoy mesh for mTLS, traffic policies, and multi-zone deployments. |

## Use Cases

| Name | Description |
|------|-------------|
| API Gateway for Microservices | Route, secure, observe microservice traffic. |
| Multi-Cloud API Management | Manage APIs across hybrid and multi-cloud through Konnect. |
| Zero-Trust Security | mTLS, OAuth2, JWT, API key authentication at the gateway. |
| AI and Agent Connectivity | Govern LLM, MCP, and A2A traffic with prompt firewalls, semantic caching, token budgets, per-agent cost allocation. |
| Kafka Governance at Scale | Per-topic identity-aware policies and quotas without rebuilding producers/consumers. |
| API Lifecycle Management | Design with Insomnia, deploy and monetize through Konnect. |
| Rate Limiting and Traffic Control | Configurable rate limiting, request size limits, traffic shaping. |

## Integrations

| Name | Description |
|------|-------------|
| Kubernetes | Kong Gateway as Kubernetes Ingress Controller or Kong Operator with CRDs. |
| Prometheus and Grafana | Metrics export and dashboards. |
| OpenTelemetry | Distributed tracing across services, LLM calls, and A2A traffic. |
| HashiCorp Vault | Secrets management. |
| Datadog | Logs, metrics, traces for API and AI monitoring. |
| Akamai | Reference architecture combining AI Gateway with Akamai distributed compute. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Kong Gateway Admin API (Enterprise) v3.14](openapi/kong-gateway-admin-api.yml)
- [Kong Konnect Platform API v3.14](openapi/kong-konnect-platform-api.yml)
- [Kong Konnect Event Gateway API (linked)](https://developer.konghq.com/api/konnect/event-gateway/v1/)

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
