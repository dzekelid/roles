swagger: "2.0"
x-collection-name: Google Cloud Identity Access Management
x-complete: 1
info:
  title: Google Identity and Access Management (IAM)
  description: manages-identity-and-access-control-for-google-cloud-platform-resources-including-the-creation-of-service-accounts-which-you-can-use-to-authenticate-to-google-and-make-api-calls-
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