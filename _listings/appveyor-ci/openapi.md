---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 1
info:
  title: App Veyor
  description: appveyor-is-a-hosted-continuous-integration-service-which-runs-on-microsoftwindows---the-appveyor-rest-api-provides-a-restful-way-to-interact-with-theappveyor-service---this-includes-managing-projects-builds-deploymentsand-the-teams-that-build-them-additional-help-and-discussion-of-the-appveyor-rest-api-is-available-athttphelp-appveyor-comdiscussionsthis-swagger-definition-is-an-unofficial-description-of-the-appveyorrest-api-maintained-at-httpsgithub-comkevinoidappveyorswaggerplease-report-any-issues-or-suggestions-for-this-swagger-definition-athttpsgithub-comkevinoidappveyorswaggerissuesnew-api-conventionsfields-which-are-missing-from-update-operations-put-requests-aretypically-reset-to-their-default-values---so-although-most-fields-are-nottechnically-required-they-should-usually-be-specified-in-practice-
  termsOfService: https://www.appveyor.com/terms-of-service/
  contact:
    name: AppVeyor Team
    url: https://www.appveyor.com/about/
    email: team@appveyor.com
  version: 0.20170106.0
host: ci.appveyor.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /roles:
    get:
      summary: Get Roles
      description: Get roles.
      operationId: getRoles
      x-api-path-slug: roles-get
      responses:
        200:
          description: OK
      tags:
      - Roles
    post:
      summary: Post Roles
      description: Post roles.
      operationId: postRoles
      x-api-path-slug: roles-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Roles
    put:
      summary: Put Roles
      description: Put roles.
      operationId: putRoles
      x-api-path-slug: roles-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Roles
  /roles/{roleId}:
    delete:
      summary: Delete Roles Roleid
      description: Delete roles roleid.
      operationId: deleteRolesRole
      x-api-path-slug: rolesroleid-delete
      responses:
        200:
          description: OK
      tags:
      - Roles
      - RoleId
    get:
      summary: Get Roles Roleid
      description: Get roles roleid.
      operationId: getRolesRole
      x-api-path-slug: rolesroleid-get
      responses:
        200:
          description: OK
      tags:
      - Roles
      - RoleId
    parameters:
      summary: Parameters Roles Roleid
      description: Parameters roles roleid.
      operationId: parametersRolesRole
      x-api-path-slug: rolesroleid-parameters
      responses:
        200:
          description: OK
      tags:
      - Roles
      - RoleId
---