---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Create a role
  version: 1.0.0
  description: Create a role.
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