---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Modify a Role
  description: Modify a Role
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user-admin/v1/accounts/{accountId}/roles:
    get:
      summary: List Roles
      description: List Roles
      operationId: useradminv1accountsaccountidroles
      x-api-path-slug: useradminv1accountsaccountidroles-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for an account
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Admin
      - Accounts
      - Account
      - Roles
    post:
      summary: Create a New Role
      description: Create a New Role
      operationId: useradminv1accountsaccountidroles
      x-api-path-slug: useradminv1accountsaccountidroles-post
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for an account
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Admin
      - Accounts
      - Account
      - Roles
    put:
      summary: Modify a Role
      description: Modify a Role
      operationId: useradminv1accountsaccountidroles
      x-api-path-slug: useradminv1accountsaccountidroles-put
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for an account
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Admin
      - Accounts
      - Account
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