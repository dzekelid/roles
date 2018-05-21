---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 1
info:
  title: Akamai API
  description: the-akamai-api-for-managing-your-akamai-service
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
  /user-admin/v1/accounts/{accountId}/roles/{roleId}:
    get:
      summary: Get a Role
      description: Get a Role
      operationId: useradminv1accountsaccountidrolesroleid
      x-api-path-slug: useradminv1accountsaccountidrolesroleid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for an account
        type: string
      - in: query
        name: roleId
        description: Unique identifier for a role object
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
      - Role
    delete:
      summary: Remove a Role
      description: Remove a Role
      operationId: useradminv1accountsaccountidrolesroleid
      x-api-path-slug: useradminv1accountsaccountidrolesroleid-delete
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for an account
        type: string
      - in: query
        name: roleId
        description: Unique identifier for a role object
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
      - Role
  /user-admin/v1/accounts/{accountId}/roles/grantable:
    get:
      summary: List Grantable Roles
      description: List Grantable Roles
      operationId: useradminv1accountsaccountidrolesgrantable
      x-api-path-slug: useradminv1accountsaccountidrolesgrantable-get
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
      - Grantable
---