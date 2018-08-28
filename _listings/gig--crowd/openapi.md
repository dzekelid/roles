swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/user/roles/{userId}:
    get:
      summary: Get Admin User Roles Userid
      description: Get admin user roles userid.
      operationId: getApiV1AdminUserRolesUser
      x-api-path-slug: apiv1adminuserrolesuserid-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - User
      - Roles
      - Userid
    post:
      summary: Post Admin User Roles Userid
      description: Post admin user roles userid.
      operationId: postApiV1AdminUserRolesUser
      x-api-path-slug: apiv1adminuserrolesuserid-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: roles
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - User
      - Roles
      - Userid
  /api/v1/admin/user/roles:
    get:
      summary: Get Admin User Roles
      description: Get admin user roles.
      operationId: getApiV1AdminUserRoles
      x-api-path-slug: apiv1adminuserroles-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Admin
      - User
      - Roles
  /api/v1/admin/user/empty/{role}:
    get:
      summary: Get Admin User Empty Role
      description: Get admin user empty role.
      operationId: getApiV1AdminUserEmptyRole
      x-api-path-slug: apiv1adminuseremptyrole-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: role
      responses:
        200:
          description: OK
      tags:
      - Admin
      - User
      - Empty
      - Role