---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Gets role members
  version: 1.0.0
  description: Gets role members.
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
  /roles/{roleid}/members/{username}:
    delete:
      summary: Removes user from a role
      description: Removes user from a role.
      operationId: removeRoleMember
      x-api-path-slug: rolesroleidmembersusername-delete
      parameters:
      - in: path
        name: roleid
        description: Role identifier
      - in: path
        name: username
        description: username
      responses:
        200:
          description: OK
      tags:
      - Removes
      - User
      - From
      - Role
    put:
      summary: Add user to a role
      description: Add user to a role.
      operationId: addRoleMember
      x-api-path-slug: rolesroleidmembersusername-put
      parameters:
      - in: path
        name: roleid
        description: Role identifier
      - in: path
        name: username
        description: username
      responses:
        200:
          description: OK
      tags:
      - User
      - To
      - Role
  /roles/{roleid}/members:
    get:
      summary: Gets role members
      description: Gets role members.
      operationId: getRoleMembers
      x-api-path-slug: rolesroleidmembers-get
      parameters:
      - in: path
        name: roleid
        description: Role identifier
      responses:
        200:
          description: OK
      tags:
      - Role
      - Members
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