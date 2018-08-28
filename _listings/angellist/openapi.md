swagger: "2.0"
x-collection-name: AngelList
x-complete: 1
info:
  title: AngelList
  description: the-angellist-api-provides-developers-with-a-restful-interface-to-the-angellist-data-set--for-more-information-read-the-oauth-faq-
  termsOfService: https://angel.co/terms
  contact:
    name: AngelList
    url: https://angel.co/api
    email: api@angel.co
  version: v1
host: api.angel.co
basePath: /1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /startups/{startup_id}/roles:
    get:
      summary: Get Startup Roles
      description: Get Startup Roles
      operationId: startupRoles
      x-api-path-slug: startupsstartup-idroles-get
      parameters:
      - in: path
        name: startup_id
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Roles
  /startup_roles:
    get:
      summary: Get Startup Roles
      description: Get Startup Roles
      operationId: 1Startup_roles
      x-api-path-slug: startup-roles-get
      parameters:
      - in: query
        name: startup_id
      - in: query
        name: v
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Roles