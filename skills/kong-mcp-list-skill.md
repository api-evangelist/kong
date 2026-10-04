---
name: mcp-list
description: List MCP servers for a control plane, providing details on how to retrieve and interpret the MCP server information associated with a specific control plane in Kong's management plane.
api: openapi/kong-mcp-servers-api-openapi.yml
operations:
  - list-mcp-servers-by-control-plane
---

## Steps
1. Authenticate using a Konnect access token.
2. Call `GET /v1/mcp-cp/{controlPlaneId}/mcp-servers` with the desired `controlPlaneId`.
3. Parse the JSON response array of MCP server objects.
