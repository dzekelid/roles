---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Get Roles Roleid
  description: Get roles roleid.
  termsOfService: https://www.appveyor.com/terms-of-service/
  contact:
    name: AppVeyor Team
    url: https://www.appveyor.com/about/
    email: team@appveyor.com
  version: 0.20170106.0
host: ci.appveyor.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /roles:
    get:
      summary: Get Roles
      description: Get roles.
      operationId: getRoles
      x-api-path-slug: roles-get
      responses:
        200:
          description: OK
      tags:
      - Roles
    post:
      summary: Post Roles
      description: Post roles.
      operationId: postRoles
      x-api-path-slug: roles-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Roles
    put:
      summary: Put Roles
      description: Put roles.
      operationId: putRoles
      x-api-path-slug: roles-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Roles
  /roles/{roleId}:
    delete:
      summary: Delete Roles Roleid
      description: Delete roles roleid.
      operationId: deleteRolesRole
      x-api-path-slug: rolesroleid-delete
      responses:
        200:
          description: OK
      tags:
      - Roles
      - RoleId
    get:
      summary: Get Roles Roleid
      description: Get roles roleid.
      operationId: getRolesRole
      x-api-path-slug: rolesroleid-get
      responses:
        200:
          description: OK
      tags:
      - Roles
      - RoleId
    parameters:
      summary: Parameters Roles Roleid
      description: Parameters roles roleid.
      operationId: parametersRolesRole
      x-api-path-slug: rolesroleid-parameters
      responses:
        200:
          description: OK
      tags:
      - Roles
      - RoleId
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