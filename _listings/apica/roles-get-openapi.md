---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Roles API Get Roles
  version: 1.0.0
  description: Return user roles
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/roles ':
    ' get ':
      summary: Get Roles
      description: Return user roles
      operationId: getRoles
      x-api-path-slug: roles-get
      responses:
        200:
          description: OK
      tags:
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