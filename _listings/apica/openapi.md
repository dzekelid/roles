swagger: "2.0"
x-collection-name: Apica
x-complete: 1
info:
  title: Scenarios API
  version: 1.0.0
host: api.pingdom.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
basePath: /
paths:
  '/roles ':
    ' get ':
      summary: Get Roles
      description: Return user roles
      operationId: getRoles
      x-api-path-slug: roles-get
      responses:
        200:
          description: OK
      tags:
      - Roles