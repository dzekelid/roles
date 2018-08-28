---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Set the guaranteed rent a landlord will receive for a roles tenancies
  version: 1.0.0
  description: Set the guaranteed rent a landlord will receive for a roles tenancies.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/selectedpropertiesmatch:
    post:
      summary: Generates a correspondence to a single applicant, sending them user
        selected property roles
      description: Generates a correspondence to a single applicant, sending them
        user selected property roles.
      operationId: DocumentGeneration_SendSelectedPropertiesToApplicantBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationselectedpropertiesmatch-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Correspondence
      - To
      - Single
      - Applicant
      - ""
      - Sending
      - Them
      - User
      - Selected
      - Property
      - Roles
  /api/documentgeneration/selectedlettingspropertiesmatch:
    post:
      summary: Generates a correspondence to a single letting applicant, sending them
        user selected property roles
      description: Generates a correspondence to a single letting applicant, sending
        them user selected property roles.
      operationId: DocumentGeneration_SendSelectedLettingsPropertiesToApplicantBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationselectedlettingspropertiesmatch-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Correspondence
      - To
      - Single
      - Letting
      - Applicant
      - ""
      - Sending
      - Them
      - User
      - Selected
      - Property
      - Roles
  /api/documentgeneration/multipropertymatch:
    post:
      summary: Generates a correspondence to multiple applicants, sending them a filtered
        set of the matching property roles
      description: Generates a correspondence to multiple applicants, sending them
        a filtered set of the matching property roles.
      operationId: DocumentGeneration_SendAutoMatchedPropertiesToApplicantListBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationmultipropertymatch-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Correspondence
      - To
      - Multiple
      - Applicants
      - ""
      - Sending
      - Them
      - Filtered
      - Set
      - Of
      - Matching
      - Property
      - Roles
  /api/documentgeneration/multilettingspropertymatch:
    post:
      summary: Generates a correspondence to multiple letting applicants, sending
        them a filtered set of the matching letting property roles
      description: Generates a correspondence to multiple letting applicants, sending
        them a filtered set of the matching letting property roles.
      operationId: DocumentGeneration_SendAutoMatchedLettingsPropertiesToApplicantListBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationmultilettingspropertymatch-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Correspondence
      - To
      - Multiple
      - Letting
      - Applicants
      - ""
      - Sending
      - Them
      - Filtered
      - Set
      - Of
      - Matching
      - Letting
      - Property
      - Roles
  /api/documentgeneration/bulkinterestrolecommunication:
    post:
      summary: Generates a bulk communication pack out to multiple clients with interest
        roles.
      description: Generates a bulk communication pack out to multiple clients with
        interest roles..
      operationId: DocumentGeneration_BulkInterestRoleCommunicationBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationbulkinterestrolecommunication-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Bulk
      - Communication
      - Pack
      - Out
      - To
      - Multiple
      - Clients
      - Interest
      - Roles
  /api/progression/lettings/{id}/setguaranteedrent:
    post:
      summary: Set the guaranteed rent a landlord will receive for a roles tenancies
      description: Set the guaranteed rent a landlord will receive for a roles tenancies.
      operationId: LettingsProgression_SetGuaranteedRentByidByamount
      x-api-path-slug: apiprogressionlettingsidsetguaranteedrent-post
      parameters:
      - in: query
        name: amount
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Guaranteed
      - Rent
      - Landlord
      - Will
      - Receivea
      - Roles
      - Tenancies
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