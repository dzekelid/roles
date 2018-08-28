---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Update a single role
  version: 1.0.0
  description: Update a single role.
host: /merchants
basePath: https://api.clover.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/merchants/{mId}/roles:
    get:
      summary: Get all roles from a merchant
      description: Get all roles from a merchant.
      operationId: GetRoles
      x-api-path-slug: v3merchantsmidroles-get
      parameters:
      - in: query
        name: expand
        description: 'Expandable fields: [employees]'
      - in: query
        name: filter
        description: 'Filter fields: [modifiedTime, systemRole, name, id, deletedTime]'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Roles
    post:
      summary: Create a role
      description: Create a role.
      operationId: CreateRole
      x-api-path-slug: v3merchantsmidroles-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Roles
  /v3/merchants/{mId}/roles/{rId}:
    get:
      summary: Get a single role
      description: Get a single role.
      operationId: GetRole
      x-api-path-slug: v3merchantsmidrolesrid-get
      parameters:
      - in: query
        name: expand
        description: 'Expandable fields: [employees]'
      - in: path
        name: mId
        description: Merchant Id
      - in: path
        name: rId
        description: Role Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Roles
      - RId
    post:
      summary: Update a single role
      description: Update a single role.
      operationId: UpdateRole
      x-api-path-slug: v3merchantsmidrolesrid-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: expand
        description: 'Expandable fields: [employees]'
      - in: path
        name: mId
        description: Merchant Id
      - in: path
        name: rId
        description: Role Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Roles
      - RId
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---