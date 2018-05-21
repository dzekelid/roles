---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Delete Role
  version: 1.0.0
  description: Deletes the specified role.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateRole:
    get:
      summary: Create Role
      description: Creates a new role for your AWS account.
      operationId: createRole
      x-api-path-slug: actioncreaterole-get
      parameters:
      - in: query
        name: AssumeRolePolicyDocument
        description: The trust relationship policy document that grants an entity
          permission to assume the      role
        type: string
      - in: query
        name: Path
        description: The path to the role
        type: string
      - in: query
        name: RoleName
        description: The name of the role to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
  /?Action=DeleteRole:
    get:
      summary: Delete Role
      description: Deletes the specified role.
      operationId: deleteRole
      x-api-path-slug: actiondeleterole-get
      parameters:
      - in: query
        name: RoleName
        description: The name of the role to delete
        type: string
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