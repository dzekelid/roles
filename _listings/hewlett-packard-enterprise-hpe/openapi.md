swagger: "2.0"
x-collection-name: Hewlett Packard Enterprise (HPE)
x-complete: 1
info:
  title: HPE OneSphere API
  description: hpe-onesphere-hybrid-cloud-management-rest-api-for-calls-requiring-authentication-use-restsession-to-get-a-token-
  termsOfService: http://www.hpe.com/onesphere
  contact:
    name: HPE OneSphere API team
    url: http://www.hpe.com/onesphere
  version: 1.0.0
host: deic02-hpe.hpeonesphere.com
basePath: /rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /membership-roles:
    get:
      summary: Get Membership Roles
      description: Returns membership (project-specific) roles.
      operationId: ListMembershipRoles
      x-api-path-slug: membershiproles-get
      responses:
        200:
          description: OK
      tags:
      - Membership
      - Roles
  /roles:
    get:
      summary: Get Roles
      description: Returns global roles.
      operationId: ListRoles
      x-api-path-slug: roles-get
      responses:
        200:
          description: OK
      tags:
      - Roles