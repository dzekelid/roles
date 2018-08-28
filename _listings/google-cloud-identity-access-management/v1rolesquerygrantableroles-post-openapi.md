---
swagger: "2.0"
x-collection-name: Google Cloud Identity Access Management
x-complete: 0
info:
  title: Google Cloud Identity & Access Management API Query Roles
  description: |-
    Queries roles that can be granted on a particular resource.
    A role is grantable if it can be used as the role in a binding for a policy
    for that resource.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: iam.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/roles:queryGrantableRoles:
    post:
      summary: Query Roles
      description: |-
        Queries roles that can be granted on a particular resource.
        A role is grantable if it can be used as the role in a binding for a policy
        for that resource.
      operationId: iam.roles.queryGrantableRoles
      x-api-path-slug: v1rolesquerygrantableroles-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Role
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