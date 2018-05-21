---
swagger: "2.0"
x-collection-name: AngelList
x-complete: 0
info:
  title: AngelList Get Startup Roles
  description: Get Startup Roles
  termsOfService: https://angel.co/terms
  contact:
    name: AngelList
    url: https://angel.co/api
    email: api@angel.co
  version: v1
host: api.angel.co
basePath: /1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /startups/{startup_id}/roles:
    get:
      summary: Get Startup Roles
      description: Get Startup Roles
      operationId: startupRoles
      x-api-path-slug: startupsstartup-idroles-get
      parameters:
      - in: path
        name: startup_id
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Roles
  /startup_roles:
    get:
      summary: Get Startup Roles
      description: Get Startup Roles
      operationId: 1Startup_roles
      x-api-path-slug: startup-roles-get
      parameters:
      - in: query
        name: startup_id
      - in: query
        name: v
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
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