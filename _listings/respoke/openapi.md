---
swagger: "2.0"
x-collection-name: Respoke
x-complete: 1
info:
  title: Respoke REST API
  description: add-live-voice-video-text-and-data-features-to-your-website-or-app-
  termsOfService: https://www.respoke.io/files/respoke-tos-20141007.pdf
  version: v1
host: api.respoke.io
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  roles/:
    post:
      summary: Roles
      description: Create roleId and roleName for creating tokens.
      operationId: postRoles
      x-api-path-slug: roles-post
      parameters:
      - schema:
          $ref: '#/definitions/holder'
      - in: header
        name: App-Secret
        description: Your application secret
      responses:
        200:
          description: OK
      tags:
      - Roles
---