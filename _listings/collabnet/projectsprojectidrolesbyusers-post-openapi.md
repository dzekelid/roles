---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Get roles by user
  version: 1.0.0
  description: Get roles by user.
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{projectid}/roles/by-users:
    post:
      summary: Get roles by user
      description: Get roles by user.
      operationId: getRolesByUsers
      x-api-path-slug: projectsprojectidrolesbyusers-post
      parameters:
      - in: body
        name: body
        description: List of user Names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: projectid
      responses:
        200:
          description: OK
      tags:
      - Roles
      - By
      - User
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