---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
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
---