---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Get Identity Pool Roles
  version: 1.0.0
  description: Gets the roles for an identity pool.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetIdentityPoolRoles:
    get:
      summary: Get Identity Pool Roles
      description: Gets the roles for an identity pool.
      operationId: getIdentityPoolRoles
      x-api-path-slug: actiongetidentitypoolroles-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool Roles
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