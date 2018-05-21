---
swagger: "2.0"
x-collection-name: Intrinio
x-complete: 1
info:
  title: Intrinio
  description: through-our-intrinio-data-marketplace-we-offer-a-wide-selection-of-financial-data-feeds-sourced-by-our-own-proprietary-processes-as-well-as-from-many-data-vendors-the-primary-application-of-the-intrinio-api-is-for-use-in-thirdparty-applications-and-integrations-or-for-endusers-utilizing-the-excel-addin-and-google-sheets-addon-the-intrinio-api-uses-https-verbs-and-a-restful-endpoint-structure-which-makes-it-easy-to-request-data-from-intrinio-basic-authentication-is-administered-over-https-responses-are-delivered-in-json-format
  version: 1.0.0
host: api.intrinio.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /executives/roles:
    get:
      summary: Company Executive Roles
      description: For a specific executive company identifier, returns a list of
        all roles within the company.  For example, an executive may be the Chief
        Executive Officer, a Director, and the Chairman of the Board of Directors.
      operationId: company-executive-roles
      x-api-path-slug: executivesroles-get
      parameters:
      - in: query
        name: company
        description: ' the identifier for the specified security or company: '
        type: string
      - in: query
        name: identifier
        description: ' the Intrinio executive identifier'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Executives
      - Executive Roles
---