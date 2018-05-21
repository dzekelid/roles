---
swagger: "2.0"
x-collection-name: CloudFlare
x-complete: 1
info:
  title: CloudFlare
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/:organization_identifier/roles:
    get:
      summary: Get all available roles for an organization
      description: Get all available roles for an organization
      operationId: cloudflare-organization-roles-api
      x-api-path-slug: organizationsorganization-identifierroles-get
      responses:
        200:
          description: OK
      tags:
      - Organization Roles
  /organizations/:organization_identifier/roles/:identifier:
    get:
      summary: Get information about a specific role for an organization
      description: Get information about a specific role for an organization
      operationId: cloudflare-organization-roles-api
      x-api-path-slug: organizationsorganization-identifierrolesidentifier-get
      responses:
        200:
          description: OK
      tags:
      - Organization Roles
---