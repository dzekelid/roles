swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 1
info:
  title: Global Change Information System API
  description: who-we-are-what-the-gcis-is-and-how-we-use-identifiers-and-semantic-information-to-provide-points-of-reference-and-traceability--examples-and-tutorials-for-using-this-system-as-a-researcher-citizen-scientist-application-developer-or-information-theorist--a-description-of-how-the-information-is-structured-including-the-overlaps-between-relational-and-semantic-representations-of-the-information--complete-documentation-for-the-api-including-methods-for-browsing-and-finding-resources-
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /role_type:
    get:
      summary: List roles
      description: Get a list of the types of roles for contributors.
      operationId: get-a-list-of-the-types-of-roles-for-contributors
      x-api-path-slug: role-type-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the contributors
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Roles