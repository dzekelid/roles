---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API List Roles
  version: 1.0.0
  description: Lists the IAM roles that have the specified path prefix.
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
  /?Action=GetRole:
    get:
      summary: Get Role
      description: |-
        Retrieves information about the specified role, including the role's path, GUID, ARN,
              and the role's trust policy that grants permission to assume the role.
      operationId: getRole
      x-api-path-slug: actiongetrole-get
      parameters:
      - in: query
        name: RoleName
        description: The name of the IAM role to get information about
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
  /?Action=ListRoles:
    get:
      summary: List Roles
      description: Lists the IAM roles that have the specified path prefix.
      operationId: listRoles
      x-api-path-slug: actionlistroles-get
      parameters:
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only after     you
          receive a response indicating that the results are truncated
        type: string
      - in: query
        name: MaxItems
        description: (Optional) Use this only when paginating results to indicate
          the     maximum number of items you want in the response
        type: string
      - in: query
        name: PathPrefix
        description: The path prefix for filtering the results
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