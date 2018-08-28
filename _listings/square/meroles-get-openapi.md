---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API Get Me Roles
  description: Provides summary information for all of a business's employee roles.
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: 1.0.0
host: connect.squareup.com
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/roles:
    post:
      summary: Post Me Roles
      description: Creates an employee role you can then assign to employees.
      operationId: postMeRoles
      x-api-path-slug: meroles-post
      parameters:
      - in: body
        name: EmployeeRole
        description: An EmployeeRole object with a name and permissions, and an optional
          owner flag
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Me
      - Roles
    get:
      summary: Get Me Roles
      description: Provides summary information for all of a business's employee roles.
      operationId: getMeRoles
      x-api-path-slug: meroles-get
      parameters:
      - in: query
        name: batch_token
        description: A pagination cursor to retrieve the next set of results for youroriginal
          query to the endpoint
      - in: query
        name: limit
        description: The maximum integer number of employee entities to return in
          a single response
      - in: query
        name: order
        description: The order in which employees are listed in the response, based
          on their created_at field
      responses:
        200:
          description: OK
      tags:
      - Me
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