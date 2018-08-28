---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Get a list of ordered brochures belonging to a role
  version: 1.0.0
  description: Get a list of ordered brochures belonging to a role.
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
  /api/list/property/propertyidsfiltered:
    post:
      summary: Get list of RoleIds for property marketing roles
      description: Get list of roleids for property marketing roles.
      operationId: List_GetPropertyListFilteredByfilter
      x-api-path-slug: apilistpropertypropertyidsfiltered-post
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - RoleIdsproperty
      - Marketing
      - Roles
  /api/property/{id}/tenantroles:
    get:
      summary: Get a list of all current and ended tenant roles from a property id.
      description: Get a list of all current and ended tenant roles from a property
        id..
      operationId: Property_TenantRolesByPropertyIdByid
      x-api-path-slug: apipropertyidtenantroles-get
      parameters:
      - in: path
        name: id
        description: The Id of the property
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - ""
      - Current
      - Ended
      - Tenant
      - Roles
      - From
      - Property
      - Id
  /api/role/pausesearchingroles:
    post:
      summary: Pauses searching roles in bulk (by Id)
      description: Pauses searching roles in bulk (by id).
      operationId: Role_PauseSearchingRolesBysearchingRoleIds
      x-api-path-slug: apirolepausesearchingroles-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: searchingRoleIds
        description: Ids of the searching roles to pause
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Pauses
      - Searching
      - Roles
      - In
      - Bulk
      - (by
      - Id)
  /api/role/unpausesearchingroles:
    post:
      summary: UnPauses searching roles in bulk (by Id)
      description: Unpauses searching roles in bulk (by id).
      operationId: Role_UnPauseSearchingRolesBysearchingRoleIds
      x-api-path-slug: apiroleunpausesearchingroles-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: searchingRoleIds
        description: Ids of the searching roles to pause
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - UnPauses
      - Searching
      - Roles
      - In
      - Bulk
      - (by
      - Id)
  /api/role/suggest:
    get:
      summary: Search for property marketing roles that match the specified search
        criteria
      description: Search for property marketing roles that match the specified search
        criteria.
      operationId: Role_SuggestBydataContract.isOnMarketBydataContract.pageNumberBydataContract.pageSizeBydataContract.
      x-api-path-slug: apirolesuggest-get
      parameters:
      - in: query
        name: dataContract.isOnMarket
      - in: query
        name: dataContract.pageNumber
      - in: query
        name: dataContract.pageSize
      - in: query
        name: dataContract.query
      - in: query
        name: dataContract.roleType
      - in: query
        name: dataContract.suggestType
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Searchproperty
      - Marketing
      - Roles
      - That
      - Match
      - Specified
      - Search
      - Criteria
  /api/agency/apikey:
    post:
      summary: Issues an API key for use with the simple role/search endpoints
      description: Issues an api key for use with the simple role/search endpoints.
      operationId: Agency_IssueApiKeyBysubjectId
      x-api-path-slug: apiagencyapikey-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: subjectId
        description: The Id of the group to assign a key to
      responses:
        200:
          description: OK
      tags:
      - Issues
      - Keyuse
      - Simple
      - Role
      - Search
      - Endpoints
  /api/auction/savecontact:
    post:
      summary: Add a new contact to the given auction Role or edit an existing contact
      description: Add a new contact to the given auction role or edit an existing
        contact.
      operationId: Auction_SaveAuctionContactBysaveContactDataContract
      x-api-path-slug: apiauctionsavecontact-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: saveContactDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - New
      - Contact
      - To
      - Given
      - Auction
      - Role
      - Edit
      - Existing
      - Contact
  /api/auction/removecontact:
    post:
      summary: Remove an existing auction contact from the auction role
      description: Remove an existing auction contact from the auction role.
      operationId: Auction_RemoveAuctionContactByremoveContactDataContract
      x-api-path-slug: apiauctionremovecontact-post
      parameters:
      - in: body
        name: removeContactDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Existing
      - Auction
      - Contact
      - From
      - Auction
      - Role
  /api/progression/auction/instructforauction:
    post:
      summary: Instructs a role to be let
      description: Instructs a role to be let.
      operationId: AuctionProgression_InstructForAuctionByinstructToSellCommandDataContract
      x-api-path-slug: apiprogressionauctioninstructforauction-post
      parameters:
      - in: body
        name: instructToSellCommandDataContract
        description: Details of the instruction
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Instructs
      - Role
      - To
      - Be
      - Let
  /api/role/auction/{id}/setrequestedlotnumber:
    post:
      summary: Set the requested lot number for a property auction role.
      description: Set the requested lot number for a property auction role..
      operationId: AuctionRole_SetRequestedLotNumberByidBylotNumber
      x-api-path-slug: apiroleauctionidsetrequestedlotnumber-post
      parameters:
      - in: path
        name: id
        description: the id of the role
      - in: query
        name: lotNumber
        description: the requested lot number
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Requested
      - Lot
      - Numbera
      - Property
      - Auction
      - Role
  /api/role/auction/{id}/setlotnumber:
    post:
      summary: Set the lot number for a property auction role.
      description: Set the lot number for a property auction role..
      operationId: AuctionRole_SetLotNumberByidByauctionIdBylotNumber
      x-api-path-slug: apiroleauctionidsetlotnumber-post
      parameters:
      - in: query
        name: auctionId
        description: the id of the auction to set the lot number for
      - in: path
        name: id
        description: the id of the role
      - in: query
        name: lotNumber
        description: the lot number
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Lot
      - Numbera
      - Property
      - Auction
      - Role
  /api/role/auction/{id}/addtoauction:
    post:
      summary: Add a property auction role to an existing auction
      description: Add a property auction role to an existing auction.
      operationId: AuctionRole_AddToAuctionByidByauctionIdBylotNumber
      x-api-path-slug: apiroleauctionidaddtoauction-post
      parameters:
      - in: query
        name: auctionId
        description: the id of the auction to add the role to
      - in: path
        name: id
        description: the id of the role
      - in: query
        name: lotNumber
        description: the lot number
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Property
      - Auction
      - Role
      - To
      - Existing
      - Auction
  /api/role/auction/{id}/removefromauction:
    post:
      summary: Add a property auction role to an existing auction
      description: Add a property auction role to an existing auction.
      operationId: AuctionRole_RemoveFromAuctionByidByremoveFromAuctionDataContract
      x-api-path-slug: apiroleauctionidremovefromauction-post
      parameters:
      - in: path
        name: id
        description: the id of the role
      - in: body
        name: removeFromAuctionDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Property
      - Auction
      - Role
      - To
      - Existing
      - Auction
  /api/role/auction/{id}/setreserve:
    post:
      summary: Set the reserve for a property auction role.
      description: Set the reserve for a property auction role..
      operationId: AuctionRole_SetReserveByidBysetReserveDataContract
      x-api-path-slug: apiroleauctionidsetreserve-post
      parameters:
      - in: path
        name: id
        description: the id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: setReserveDataContract
        description: SetReserveDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Set
      - Reservea
      - Property
      - Auction
      - Role
  /api/role/auction/{id}/settype:
    post:
      summary: Set the type of auction role (Commercial or Residential)
      description: Set the type of auction role (commercial or residential).
      operationId: AuctionRole_SetTypeByidByauctionRoleTypeSystemName
      x-api-path-slug: apiroleauctionidsettype-post
      parameters:
      - in: query
        name: auctionRoleTypeSystemName
        description: The auction role type
      - in: path
        name: id
        description: the id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Type
      - Of
      - Auction
      - Role
      - (Commercial
      - Residential)
  /api/role/auction/milestone/{roleId}:
    get:
      summary: Get auction role milestones
      description: Get auction role milestones.
      operationId: AuctionRole_GetRoleMilestonesByroleId
      x-api-path-slug: apiroleauctionmilestoneroleid-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
      responses:
        200:
          description: OK
      tags:
      - Auction
      - Role
      - Milestones
    put:
      summary: Update an auction role milestone
      description: Update an auction role milestone.
      operationId: AuctionRole_SaveAuctionMilestoneByroleIdBydataContract
      x-api-path-slug: apiroleauctionmilestoneroleid-put
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
      responses:
        200:
          description: OK
      tags:
      - Auction
      - Role
      - Milestone
    post:
      summary: Add a new auction role milestone
      description: Add a new auction role milestone.
      operationId: AuctionRole_AddAuctionMilestoneByroleIdBydataContract
      x-api-path-slug: apiroleauctionmilestoneroleid-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
      responses:
        200:
          description: OK
      tags:
      - New
      - Auction
      - Role
      - Milestone
  /api/documentgeneration/instruction:
    post:
      summary: Generates a Instruction letter correspondence to the vendor of a particular
        marketing role
      description: Generates a instruction letter correspondence to the vendor of
        a particular marketing role.
      operationId: DocumentGeneration_GenerateInstructionLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationinstruction-post
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
      - Instruction
      - Letter
      - Correspondence
      - To
      - Vendor
      - Of
      - Particular
      - Marketing
      - Role
  /api/documentgeneration/withdrawninstruction:
    post:
      summary: Generates a Withdrawn Instruction letter correspondence to the vendor
        of a particular marketing role
      description: Generates a withdrawn instruction letter correspondence to the
        vendor of a particular marketing role.
      operationId: DocumentGeneration_GenerateWithdrawnInstructionLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationwithdrawninstruction-post
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
      - Withdrawn
      - Instruction
      - Letter
      - Correspondence
      - To
      - Vendor
      - Of
      - Particular
      - Marketing
      - Role
  /api/documentgeneration/valuationlost:
    post:
      summary: Generates a Valuation Lost letter correspondence to the vendor of a
        particular marketing role
      description: Generates a valuation lost letter correspondence to the vendor
        of a particular marketing role.
      operationId: DocumentGeneration_GenerateValuationLostLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationvaluationlost-post
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
      - Valuation
      - Lost
      - Letter
      - Correspondence
      - To
      - Vendor
      - Of
      - Particular
      - Marketing
      - Role
  /api/documentgeneration/singlepropertymatch:
    post:
      summary: Generates a correspondence to multiple applicants, sending them all
        the same property role
      description: Generates a correspondence to multiple applicants, sending them
        all the same property role.
      operationId: DocumentGeneration_SendPropertyToApplicantListBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationsinglepropertymatch-post
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
      - ""
      - Same
      - Property
      - Role
  /api/documentgeneration/singlelettingspropertymatch:
    post:
      summary: Generates a correspondence to multiple applicants, sending them all
        the same letting property role
      description: Generates a correspondence to multiple applicants, sending them
        all the same letting property role.
      operationId: DocumentGeneration_SendLettingsPropertyToApplicantListBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationsinglelettingspropertymatch-post
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
      - ""
      - Same
      - Letting
      - Property
      - Role
  /api/event/noteevent/add:
    post:
      summary: Adds a note to the provided role
      description: Adds a note to the provided role.
      operationId: Event_AddNoteEventByaddNoteDataContract
      x-api-path-slug: apieventnoteeventadd-post
      parameters:
      - in: body
        name: addNoteDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Note
      - To
      - Provided
      - Role
  /api/event/recordpropertyownercontact:
    post:
      summary: Records an event on the role representing a neg being in contact for
        a property they own
      description: Records an event on the role representing a neg being in contact
        for a property they own.
      operationId: Event_RecordPropertyOwnerContactByrecordPropertyOwnerContactDataContract
      x-api-path-slug: apieventrecordpropertyownercontact-post
      parameters:
      - in: body
        name: recordPropertyOwnerContactDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Records
      - Event
      - "On"
      - Role
      - Representing
      - Neg
      - Being
      - In
      - Contacta
      - Property
      - They
      - Own
  /api/event/recordownercontact:
    post:
      summary: Records an event on the role representing a neg being in contact for
        an owner
      description: Records an event on the role representing a neg being in contact
        for an owner.
      operationId: Event_RecordOwnerContactByrecordOwnerContactDataContract
      x-api-path-slug: apieventrecordownercontact-post
      parameters:
      - in: body
        name: recordOwnerContactDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Records
      - Event
      - "On"
      - Role
      - Representing
      - Neg
      - Being
      - In
      - Contactan
      - Owner
  /api/event/recordenquiry:
    post:
      summary: Records an event on the role representing a neg being in contact with
        a person
      description: Records an event on the role representing a neg being in contact
        with a person.
      operationId: Event_RecordEnquiryByrecordEnquiryDataContract
      x-api-path-slug: apieventrecordenquiry-post
      parameters:
      - in: body
        name: recordEnquiryDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Records
      - Event
      - "On"
      - Role
      - Representing
      - Neg
      - Being
      - In
      - Contact
      - Person
  /api/group/{id}/setsearchteam:
    post:
      summary: Set the Team Group for a searching role
      description: Set the team group for a searching role.
      operationId: Group_SetSearchTeamByidBysetTeamCommandDataContract
      x-api-path-slug: apigroupidsetsearchteam-post
      parameters:
      - in: path
        name: id
        description: Group that owns the searching role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: setTeamCommandDataContract
        description: Set Team Group Command
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Set
      - Team
      - Groupa
      - Searching
      - Role
  /api/group/{id}/getpropertyroleidsalreadysent:
    get:
      summary: returns a list of the property role ids that should be excluded from
        mailouts to this role id because the have been sent before
      description: Returns a list of the property role ids that should be excluded
        from mailouts to this role id because the have been sent before.
      operationId: Group_GetPropertyMarketingRoleIdsSentByidBywithinDaysByresendPriceChangedProperties
      x-api-path-slug: apigroupidgetpropertyroleidsalreadysent-get
      parameters:
      - in: path
        name: id
        description: The id of the group
      - in: query
        name: resendPriceChangedProperties
        description: include the properties that have had to a price change or withdrawn
          event since it was last sent to them
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: withinDays
        description: number of days since the last time it was sent, send 0 for all
      responses:
        200:
          description: OK
      tags:
      - Returns
      - List
      - Of
      - Property
      - Role
      - Ids
      - That
      - Should
      - Be
      - Excluded
      - From
      - Mailouts
      - To
      - This
      - Role
      - Id
      - Because
      - Have
      - Been
      - Sent
      - Before
  /api/group/{id}/setflags:
    put:
      summary: Sets the interest flags on groups interest role.
      description: Sets the interest flags on groups interest role..
      operationId: Group_SetInterestFlagsByidByflagsDataContract
      x-api-path-slug: apigroupidsetflags-put
      parameters:
      - in: body
        name: flagsDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Interest
      - Flags
      - "On"
      - Groups
      - Interest
      - Role
  /api/role/lettings/{id}/setdeposit:
    post:
      summary: Sets the deposit on a letting role
      description: Sets the deposit on a letting role.
      operationId: LettingRole_SetDepositByidBydatacontract
      x-api-path-slug: apirolelettingsidsetdeposit-post
      parameters:
      - in: body
        name: datacontract
        description: The deposit to set on the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Deposit
      - "On"
      - Letting
      - Role
  /api/role/lettings/{id}/setlettinginfo:
    post:
      summary: Sets the core information on a letting role
      description: Sets the core information on a letting role.
      operationId: LettingRole_SetInfoByidBydatacontract
      x-api-path-slug: apirolelettingsidsetlettinginfo-post
      parameters:
      - in: body
        name: datacontract
        description: The letting information of the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Core
      - Information
      - "On"
      - Letting
      - Role
  /api/role/lettings/{id}/setfeestructure:
    post:
      summary: Sets the fee structure on a letting role
      description: Sets the fee structure on a letting role.
      operationId: LettingRole_SetFeeStructureByidByfeeStructure
      x-api-path-slug: apirolelettingsidsetfeestructure-post
      parameters:
      - in: body
        name: feeStructure
        description: The fee structure text
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Fee
      - Structure
      - "On"
      - Letting
      - Role
  /api/role/lettings/{id}/feestructure:
    get:
      summary: Gets the fee structure on a letting role
      description: Gets the fee structure on a letting role.
      operationId: LettingRole_GetFeeStructureByid
      x-api-path-slug: apirolelettingsidfeestructure-get
      parameters:
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Fee
      - Structure
      - "On"
      - Letting
      - Role
  /api/role/lettings/{id}/saveutility:
    post:
      summary: Add or Update a utility for the letting role
      description: Add or update a utility for the letting role.
      operationId: LettingRole_SaveUtilityByidBysaveUtilityDataContract
      x-api-path-slug: apirolelettingsidsaveutility-post
      parameters:
      - in: path
        name: id
        description: The letting role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: saveUtilityDataContract
        description: The details of the utility to be added
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Utilitythe
      - Letting
      - Role
  /api/role/lettings/{roleId}/removeutility:
    delete:
      summary: Remove a utility for the letting role
      description: Remove a utility for the letting role.
      operationId: LettingRole_RemoveUtilityUtilityByroleIdByutilityId
      x-api-path-slug: apirolelettingsroleidremoveutility-delete
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: The letting role Id
      - in: query
        name: utilityId
        description: The utility Id
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Utilitythe
      - Letting
      - Role
  /api/role/lettings/{id}/setadditionalservice:
    post:
      summary: Create/Update additional service on lettings role
      description: Create/update additional service on lettings role.
      operationId: LettingRole_SetAdditionalServiceByidByadditionalServiceDataContract
      x-api-path-slug: apirolelettingsidsetadditionalservice-post
      parameters:
      - in: body
        name: additionalServiceDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Additional
      - Service
      - "On"
      - Lettings
      - Role
  /api/role/lettings/{id}/removeadditionalservice/{additionalServiceId}:
    post:
      summary: Remove additional service to lettings role tenancy
      description: Remove additional service to lettings role tenancy.
      operationId: LettingRole_DeleteAdditionalServiceByidByadditionalServiceId
      x-api-path-slug: apirolelettingsidremoveadditionalserviceadditionalserviceid-post
      parameters:
      - in: path
        name: additionalServiceId
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Additional
      - Service
      - To
      - Lettings
      - Role
      - Tenancy
  /api/progression/lettings/instructtolet:
    post:
      summary: Instructs a role to be let
      description: Instructs a role to be let.
      operationId: LettingsProgression_InstructToLetByinstructToLetCommandDataContract
      x-api-path-slug: apiprogressionlettingsinstructtolet-post
      parameters:
      - in: body
        name: instructToLetCommandDataContract
        description: Details of the instruction
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Instructs
      - Role
      - To
      - Be
      - Let
  /api/progression/lettings/fallenthrough:
    post:
      summary: Set Marketing Role as Fallen Through
      description: Set marketing role as fallen through.
      operationId: LettingsProgression_FallenThroughByfallenThroughDataContract
      x-api-path-slug: apiprogressionlettingsfallenthrough-post
      parameters:
      - in: body
        name: fallenThroughDataContract
        description: Details of the fallen though
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Marketing
      - Role
      - As
      - Fallen
      - Through
  /api/progression/lettings/setheadtenant:
    post:
      summary: Set the head tenant of a tenant role
      description: Set the head tenant of a tenant role.
      operationId: LettingsProgression_SetHeadTenantByidBytenantPersonIdBygroupId
      x-api-path-slug: apiprogressionlettingssetheadtenant-post
      parameters:
      - in: query
        name: groupId
        description: The id of the goup
      - in: query
        name: id
        description: The id of the tenant role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenantPersonId
        description: The id of the person who should become head tenant
      responses:
        200:
          description: OK
      tags:
      - Set
      - Head
      - Tenant
      - Of
      - Tenant
      - Role
  /api/progression/lettings/signunsigndeed:
    put:
      summary: Set the head tenant of a tenant role
      description: Set the head tenant of a tenant role.
      operationId: LettingsProgression_SignUnsignDeedByguarantorIdBysigned
      x-api-path-slug: apiprogressionlettingssignunsigndeed-put
      parameters:
      - in: query
        name: guarantorId
        description: The guarantor id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: signed
        description: Sign true or false
      responses:
        200:
          description: OK
      tags:
      - Set
      - Head
      - Tenant
      - Of
      - Tenant
      - Role
  /api/progression/lettings/{id}/setdeposit:
    post:
      summary: Sets the deposit on a letting role
      description: Sets the deposit on a letting role.
      operationId: LettingsProgression_SetDepositByidBydatacontract
      x-api-path-slug: apiprogressionlettingsidsetdeposit-post
      parameters:
      - in: body
        name: datacontract
        description: The deposit to set on the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Deposit
      - "On"
      - Letting
      - Role
  /api/progression/lettings/{id}/setfurnishinglevel:
    post:
      summary: Sets the deposit on a letting role
      description: Sets the deposit on a letting role.
      operationId: LettingsProgression_SetFurnishingLevelByidBydatacontract
      x-api-path-slug: apiprogressionlettingsidsetfurnishinglevel-post
      parameters:
      - in: body
        name: datacontract
        description: The deposit to set on the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Deposit
      - "On"
      - Letting
      - Role
  /api/progression/lettings/referencetenant:
    post:
      summary: Reference a tenant on a tenant role
      description: Reference a tenant on a tenant role.
      operationId: LettingsProgression_ReferenceTenantByidBytenantPersonIdByreferenceStatusByreferenceTypeBynameBynotes
      x-api-path-slug: apiprogressionlettingsreferencetenant-post
      parameters:
      - in: query
        name: id
        description: The id of the tenant role
      - in: query
        name: name
        description: The id of the person to reference
      - in: query
        name: notes
        description: Notes for the reference
      - in: query
        name: referenceDate
        description: Date of the reference if null today is used
      - in: query
        name: referenceStatus
        description: Whether the tenant has passed referencing or not
      - in: query
        name: referenceType
        description: Date of the reference if null today is used
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenantPersonId
        description: The id of the person to reference
      responses:
        200:
          description: OK
      tags:
      - Reference
      - Tenant
      - "On"
      - Tenant
      - Role
  /api/progression/lettings/referenceguarantor:
    post:
      summary: Reference a guarantor on a tenant role
      description: Reference a guarantor on a tenant role.
      operationId: LettingsProgression_ReferenceGuarantorByidByguarantorPersonIdByreferenceStatusBynameBynotesByreferen
      x-api-path-slug: apiprogressionlettingsreferenceguarantor-post
      parameters:
      - in: query
        name: guarantorPersonId
        description: The id of the person to reference
      - in: query
        name: id
        description: The id of the tenant role
      - in: query
        name: name
        description: The id of the tenant role
      - in: query
        name: notes
        description: Notes of reference
      - in: query
        name: referenceDate
        description: Date of the reference if null today is used
      - in: query
        name: referenceStatus
        description: Whether the guarantor has passed referencing or not
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Reference
      - Guarantor
      - "On"
      - Tenant
      - Role
  /api/progression/lettings/{roleId}/inventory/uploaddocument:
    post:
      summary: Uploads an inventory document for a tenant role
      description: Uploads an inventory document for a tenant role.
      operationId: LettingsProgression_UploadAndAttachInventoryDocumentByroleIdBydocumentSaveCommand
      x-api-path-slug: apiprogressionlettingsroleidinventoryuploaddocument-post
      parameters:
      - in: body
        name: documentSaveCommand
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: Tenant role id
      responses:
        200:
          description: OK
      tags:
      - Uploads
      - Inventory
      - Documenta
      - Tenant
      - Role
  /api/progression/lettings/{roleId}/inventory/setrequired:
    post:
      summary: Sets whether inventory is needed on tenant role
      description: Sets whether inventory is needed on tenant role.
      operationId: LettingsProgression_SetInventoryRequiredByroleIdByrequired
      x-api-path-slug: apiprogressionlettingsroleidinventorysetrequired-post
      parameters:
      - in: query
        name: required
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: Tenant Role Id
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Whether
      - Inventory
      - Is
      - Needed
      - "On"
      - Tenant
      - Role
  /api/progression/lettings/{roleId}/inventory/savenote:
    post:
      summary: Add a note to a tenant role inventory
      description: Add a note to a tenant role inventory.
      operationId: LettingsProgression_SaveInventoryNoteByroleIdBynote
      x-api-path-slug: apiprogressionlettingsroleidinventorysavenote-post
      parameters:
      - in: query
        name: note
        description: Note text
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: Tenant role id
      responses:
        200:
          description: OK
      tags:
      - Note
      - To
      - Tenant
      - Role
      - Inventory
  /api/progression/lettings/{roleId}/removetenantcharge:
    delete:
      summary: Remove charges from a tenant role
      description: Remove charges from a tenant role.
      operationId: LettingsProgression_RemoveTenantChargesByroleIdBychargeIds
      x-api-path-slug: apiprogressionlettingsroleidremovetenantcharge-delete
      parameters:
      - in: query
        name: chargeIds
        description: The ids of the charges to remove
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: The tenant role id
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Charges
      - From
      - Tenant
      - Role
  /api/progression/lettings/{id}/setdefaultmilestones:
    post:
      summary: Set tenant role milestones as the defaults for agency
      description: Set tenant role milestones as the defaults for agency.
      operationId: LettingsProgression_SetRoleMilestonesAsDefaultByid
      x-api-path-slug: apiprogressionlettingsidsetdefaultmilestones-post
      parameters:
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
      - Tenant
      - Role
      - Milestones
      - As
      - Defaultsagency
  /api/progression/lettings/{id}/resetmilestones:
    post:
      summary: Reset tenant role milestones back to agency defaults
      description: Reset tenant role milestones back to agency defaults.
      operationId: LettingsProgression_ResetRoleMilestonesToDefaultByid
      x-api-path-slug: apiprogressionlettingsidresetmilestones-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Reset
      - Tenant
      - Role
      - Milestones
      - Back
      - To
      - Agency
      - Defaults
  /api/list/groupmatches/csv:
    post:
      summary: Generates a csv file from group matches by property role id
      description: Generates a csv file from group matches by property role id.
      operationId: List_GenerateGroupMatchesCsvBycommandDataContract
      x-api-path-slug: apilistgroupmatchescsv-post
      parameters:
      - in: body
        name: commandDataContract
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
      - Csv
      - File
      - From
      - Group
      - Matches
      - By
      - Property
      - Role
      - Id
  /api/people/{id}/roles:
    get:
      summary: Get basic role infomation for a Person by PersonId
      description: Get basic role infomation for a person by personid.
      operationId: People_BasicRolesByidBypageSizeBypageNumber
      x-api-path-slug: apipeopleidroles-get
      parameters:
      - in: path
        name: id
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Basic
      - Role
      - Infomationa
      - Person
      - By
      - PersonId
  /api/admin/portal/getportaluploadsforrole:
    get:
      summary: Get all the live portal uploads associated with a property marketing
        role
      description: Get all the live portal uploads associated with a property marketing
        role.
      operationId: Portal_GetLivePortalInformationRecordsForRoleByroleId
      x-api-path-slug: apiadminportalgetportaluploadsforrole-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roleId
      responses:
        200:
          description: OK
      tags:
      - Live
      - Portal
      - Uploads
      - Associated
      - Property
      - Marketing
      - Role
  /api/progression/addprogressionnote:
    post:
      summary: Add a note to a purchasing role
      description: Add a note to a purchasing role.
      operationId: Progression_AddProgressionNoteByprogressionNoteCommandDataContract
      x-api-path-slug: apiprogressionaddprogressionnote-post
      parameters:
      - in: body
        name: progressionNoteCommandDataContract
        description: Details of the progression note
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Note
      - To
      - Purchasing
      - Role
  /api/progression/withdrawinstruction:
    put:
      summary: Add withdrawalvaluation to a property sales role
      description: Add withdrawalvaluation to a property sales role.
      operationId: Progression_WithdrawInstructionBywithdrawInstructionDataContract
      x-api-path-slug: apiprogressionwithdrawinstruction-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: withdrawInstructionDataContract
        description: Details of the progression withdrawal
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Withdrawalvaluation
      - To
      - Property
      - Sales
      - Role
  /api/progression/withdrawvaluation:
    put:
      summary: Add WithdrawVal to a property sales role
      description: Add withdrawval to a property sales role.
      operationId: Progression_WithdrawValuationBywithdrawValuationDataContract
      x-api-path-slug: apiprogressionwithdrawvaluation-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: withdrawValuationDataContract
        description: Details of the progression withdrawal
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - WithdrawVal
      - To
      - Property
      - Sales
      - Role
  /api/progression/savecontact:
    post:
      summary: Add a new contact to the given progression Role or edit an existing
        contact
      description: Add a new contact to the given progression role or edit an existing
        contact.
      operationId: Progression_SaveProgressionContactBysaveContactDataContract
      x-api-path-slug: apiprogressionsavecontact-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: saveContactDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - New
      - Contact
      - To
      - Given
      - Progression
      - Role
      - Edit
      - Existing
      - Contact
  /api/progression/removecontact:
    post:
      summary: Remove an existing progression contact from the progression role
      description: Remove an existing progression contact from the progression role.
      operationId: Progression_RemoveProgressionContactByremoveContactDataContract
      x-api-path-slug: apiprogressionremovecontact-post
      parameters:
      - in: body
        name: removeContactDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Existing
      - Progression
      - Contact
      - From
      - Progression
      - Role
  /api/progression/getallcontacts:
    get:
      summary: Get all progression contacts for the given progression role
      description: Get all progression contacts for the given progression role.
      operationId: Progression_GetAllProgressionContactsByprogressionRoleIdBypageSizeBypageNumberByprogressionRoleType
      x-api-path-slug: apiprogressiongetallcontacts-get
      parameters:
      - in: query
        name: pageNumber
        description: The page of contacts to return
      - in: query
        name: pageSize
        description: The number of contacts to return
      - in: query
        name: progressionRoleId
        description: The Id of progression role to get all contacts for
      - in: query
        name: progressionRoleType
        description: The progression role type
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Progression
      - Contactsthe
      - Given
      - Progression
      - Role
  /api/progression/getallmilestones:
    get:
      summary: Get all progression milestones for the given progression role
      description: Get all progression milestones for the given progression role.
      operationId: Progression_GetAllProgressionMilestonesByprogressionRoleIdBypageSizeBypageNumberBymilestoneLeaseType
      x-api-path-slug: apiprogressiongetallmilestones-get
      parameters:
      - in: query
        name: milestoneCategoryType
      - in: query
        name: milestoneLeaseType
      - in: query
        name: milestoneStatus
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: progressionRoleId
      - in: query
        name: progressionRoleType
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Progression
      - Milestonesthe
      - Given
      - Progression
      - Role
  /api/progression/milestonessummary:
    get:
      summary: Get a progression milestone summary for the given progression role
      description: Get a progression milestone summary for the given progression role.
      operationId: Progression_MilestonesSummaryByprogressionRoleIdBymilestoneLeaseTypeBymilestoneCategoryType
      x-api-path-slug: apiprogressionmilestonessummary-get
      parameters:
      - in: query
        name: milestoneCategoryType
      - in: query
        name: milestoneLeaseType
      - in: query
        name: progressionRoleId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Progression
      - Milestone
      - Summarythe
      - Given
      - Progression
      - Role
  /api/progression/{id}/deletemilestone/{milestoneId}:
    delete:
      summary: Delete milestone on Progression role
      description: Delete milestone on progression role.
      operationId: Progression_DeleteProgressionMilestoneByidBymilestoneId
      x-api-path-slug: apiprogressioniddeletemilestonemilestoneid-delete
      parameters:
      - in: path
        name: id
        description: Progression Role Id
      - in: path
        name: milestoneId
        description: Milestone Id to be deleted
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Milestone
      - "On"
      - Progression
      - Role
  /api/progression/milestone/{roleId}/add:
    post:
      summary: Add a milestone to a role.
      description: Add a milestone to a role..
      operationId: Progression_AddProgressionMilestoneByaddProgressionMilestoneDataContractByroleId
      x-api-path-slug: apiprogressionmilestoneroleidadd-post
      parameters:
      - in: body
        name: addProgressionMilestoneDataContract
        description: The milestone to add
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: Id of the role to add the milestone to
      responses:
        200:
          description: OK
      tags:
      - Milestone
      - To
      - Role
  /api/progressionchain/{id}:
    get:
      summary: Get the progression chain for purchasing role
      description: Get the progression chain for purchasing role.
      operationId: ProgressionChain_GetByid
      x-api-path-slug: apiprogressionchainid-get
      parameters:
      - in: path
        name: id
        description: Purchasing Role Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Progression
      - Chainpurchasing
      - Role
  /api/progressionchain/{id}/createchain:
    post:
      summary: Create chain for sales progression role
      description: Create chain for sales progression role.
      operationId: ProgressionChain_CreateChainByid
      x-api-path-slug: apiprogressionchainidcreatechain-post
      parameters:
      - in: path
        name: id
        description: PurchasingRoleId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Chainsales
      - Progression
      - Role
  /api/progressionchain/{id}/getchain:
    get:
      summary: Create chain for sales progression role
      description: Create chain for sales progression role.
      operationId: ProgressionChain_GetProgressionChainByid
      x-api-path-slug: apiprogressionchainidgetchain-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Chainsales
      - Progression
      - Role
  /api/progressionchain/{id}/create:
    post:
      summary: Create chain for sales progression role
      description: Create chain for sales progression role.
      operationId: ProgressionChain_CreateByid
      x-api-path-slug: apiprogressionchainidcreate-post
      parameters:
      - in: path
        name: id
        description: PurchasingRoleId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Chainsales
      - Progression
      - Role
  /api/progressionchain/{purchasingRoleId}/fallthrough:
    post:
      summary: Fall through the chain for purchasing role.
      description: Fall through the chain for purchasing role..
      operationId: ProgressionChain_FallThroughBypurchasingRoleId
      x-api-path-slug: apiprogressionchainpurchasingroleidfallthrough-post
      parameters:
      - in: path
        name: purchasingRoleId
        description: Purchasing Role Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Fall
      - Through
      - Chainpurchasing
      - Role
  /api/role/{id}:
    get:
      summary: Get a role by its Id
      description: Get a role by its id.
      operationId: Role_GetByid
      x-api-path-slug: apiroleid-get
      parameters:
      - in: path
        name: id
        description: The id of the role to get
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Role
      - By
      - Its
      - Id
  /api/role/{id}/events:
    get:
      summary: Get role events by its Id
      description: Get role events by its id.
      operationId: Role_EventsByidBypageSizeBypageNumberBybranchIdByfromBytoBytypeByeventCategoryTypeByexcludedTypesByi
      x-api-path-slug: apiroleidevents-get
      parameters:
      - in: query
        name: branchId
      - in: query
        name: eventCategoryType
        description: An event category type to return
      - in: query
        name: excludedTypes
        description: Bring back all except these types
      - in: query
        name: excludeRevised
      - in: query
        name: from
        description: the date from
      - in: path
        name: id
        description: The id of the role to get events for
      - in: query
        name: includeDrafts
      - in: query
        name: pageNumber
        description: The page of events to return
      - in: query
        name: pageSize
        description: The number of events to return
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: to
        description: the date to
      - in: query
        name: type
        description: The event type to get
      responses:
        200:
          description: OK
      tags:
      - Role
      - Events
      - By
      - Its
      - Id
  /api/role/{id}/descriptions:
    get:
      summary: Get the descriptions for a role by role id
      description: Get the descriptions for a role by role id.
      operationId: Role_DescriptionsByidBypageSizeBypageNumberBytypes
      x-api-path-slug: apiroleiddescriptions-get
      parameters:
      - in: path
        name: id
        description: The id of the role to get the descriptions for
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: types
      responses:
        200:
          description: OK
      tags:
      - Descriptionsa
      - Role
      - By
      - Role
      - Id
  /api/role/{id}/detachdescription:
    put:
      summary: Detaches a description from a role
      description: Detaches a description from a role.
      operationId: Role_DetachDescriptionByidBydescriptionId
      x-api-path-slug: apiroleiddetachdescription-put
      parameters:
      - in: query
        name: descriptionId
        description: The id of the description to detach
      - in: path
        name: id
        description: The id of the role to detach the description from
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Detaches
      - Description
      - From
      - Role
  /api/role/{id}/vendors:
    get:
      summary: Get the members of a role by the role Id
      description: Get the members of a role by the role id.
      operationId: Role_VendorsByid
      x-api-path-slug: apiroleidvendors-get
      parameters:
      - in: path
        name: id
        description: The id of the role to get the owner information for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Members
      - Of
      - Role
      - By
      - Role
      - Id
  /api/role/{id}/matches:
    get:
      summary: Get a list of groups that may be interested in this property role
      description: Get a list of groups that may be interested in this property role.
      operationId: Role_MatchesByidBypageSizeBypageNumberByadjustedAskingPriceBysortByminScore
      x-api-path-slug: apiroleidmatches-get
      parameters:
      - in: query
        name: adjustedAskingPrice
        description: Override the asking price to show a different set of potential
          matches
      - in: path
        name: id
        description: The id of the role to get the group matches for
      - in: query
        name: minScore
      - in: query
        name: pageNumber
        description: Page number
      - in: query
        name: pageSize
        description: Number of results per page
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: sort
        description: Sort order of results
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Groups
      - That
      - May
      - Be
      - Interested
      - In
      - This
      - Property
      - Role
    post:
      summary: Get a list of groups that may be interested in this property role
      description: Get a list of groups that may be interested in this property role.
      operationId: Role_MatchesByidByfilterBypageSizeBypageNumberByadjustedAskingPriceBysort
      x-api-path-slug: apiroleidmatches-post
      parameters:
      - in: query
        name: adjustedAskingPrice
        description: Override the asking price to show a different set of potential
          matches
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The id of the role to get the group matches for
      - in: query
        name: pageNumber
        description: Page number
      - in: query
        name: pageSize
        description: Number of results per page
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: sort
        description: Sort order of results
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Groups
      - That
      - May
      - Be
      - Interested
      - In
      - This
      - Property
      - Role
  /api/role/{id}/matchidsfiltered:
    post:
      summary: Get list of role ids
      description: Get list of role ids.
      operationId: Role_GetMatchListFilteredByidByfilter
      x-api-path-slug: apiroleidmatchidsfiltered-post
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Role
      - Ids
  /api/role/{id}/documents:
    get:
      summary: Get a list of documents belonging to a role
      description: Get a list of documents belonging to a role.
      operationId: Role_DocumentsByidBysubTypesBypageSizeBypageNumberBytypeByorderDesc
      x-api-path-slug: apiroleiddocuments-get
      parameters:
      - in: path
        name: id
        description: The id of the role to get the documents for
      - in: query
        name: orderDesc
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: subTypes
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Documents
      - Belonging
      - To
      - Role
  /api/role/{id}/images:
    get:
      summary: Get a list of ordered images belonging to a role
      description: Get a list of ordered images belonging to a role.
      operationId: Role_ImagesByidBypageSizeBypageNumberBysubtype
      x-api-path-slug: apiroleidimages-get
      parameters:
      - in: path
        name: id
        description: The id of the role to get the images for
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: subtype
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Ordered
      - Images
      - Belonging
      - To
      - Role
  /api/role/{id}/brochures:
    get:
      summary: Get a list of ordered brochures belonging to a role
      description: Get a list of ordered brochures belonging to a role.
      operationId: Role_BrochuresByidBypageSizeBypageNumber
      x-api-path-slug: apiroleidbrochures-get
      parameters:
      - in: path
        name: id
        description: The id of the role to get the images for
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Ordered
      - Brochures
      - Belonging
      - To
      - Role
  /api/role/{id}/SetRoleImageOrder:
    put:
      summary: Updates the image order on a role
      description: Updates the image order on a role.
      operationId: Role_SetRoleImageOrderByidByimageOrderCommandDataContract
      x-api-path-slug: apiroleidsetroleimageorder-put
      parameters:
      - in: path
        name: id
        description: The id of the role to update
      - in: body
        name: imageOrderCommandDataContract
        description: The role image order
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Image
      - Order
      - "On"
      - Role
  /api/role/{id}/setbrochureorder:
    put:
      summary: Updates the brochure order on a role
      description: Updates the brochure order on a role.
      operationId: Role_SetRoleBrochureOrderByidBydocumentOrderCommandDataContract
      x-api-path-slug: apiroleidsetbrochureorder-put
      parameters:
      - in: body
        name: documentOrderCommandDataContract
        description: The role image order
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The id of the role to update
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Brochure
      - Order
      - "On"
      - Role
  /api/role/{id}/attachdocument:
    put:
      summary: Attaches an existing document to a role
      description: Attaches an existing document to a role.
      operationId: Role_AttachDocumentByidBydocumentId
      x-api-path-slug: apiroleidattachdocument-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to attach
      - in: path
        name: id
        description: The id of the role to attach the document to
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Existing
      - Document
      - To
      - Role
  /api/role/{id}/detachdocument:
    put:
      summary: Detaches a document from a role
      description: Detaches a document from a role.
      operationId: Role_DetachDocumentByidBydocumentId
      x-api-path-slug: apiroleiddetachdocument-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to detach
      - in: path
        name: id
        description: The id of the role to detach the document from
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Detaches
      - Document
      - From
      - Role
  /api/role/{id}/uploadandattachdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a role.
      description: Allows you to upload a document and attach it directly to a role..
      operationId: Role_UploadAndAttachDocumentByidBydocumentDetailsContract
      x-api-path-slug: apiroleiduploadandattachdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Role
  /api/role/{id}/attachexternaldocument:
    post:
      summary: Attaches an externally hosted document to a role
      description: Attaches an externally hosted document to a role.
      operationId: Role_AttachExternalDocumentByidBydocumentDetails
      x-api-path-slug: apiroleidattachexternaldocument-post
      parameters:
      - in: body
        name: documentDetails
        description: Details of the document to associate
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Externally
      - Hosted
      - Document
      - To
      - Role
  /api/role/{id}/valuation:
    get:
      summary: Gets the valuation for a property marketing role
      description: Gets the valuation for a property marketing role.
      operationId: Role_GetValuationByid
      x-api-path-slug: apiroleidvaluation-get
      parameters:
      - in: path
        name: id
        description: The id of the property marketing role to find a valuation for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Valuationa
      - Property
      - Marketing
      - Role
  /api/role/{id}/valued:
    get:
      summary: Gets the valuation for a property marketing role
      description: Gets the valuation for a property marketing role.
      operationId: Role_GetValuedByid
      x-api-path-slug: apiroleidvalued-get
      parameters:
      - in: path
        name: id
        description: The id of the property marketing role to find a valuation for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Valuationa
      - Property
      - Marketing
      - Role
  /api/role/{id}/offers:
    get:
      summary: Get all of the offers associated to the current property marketing
        role.
      description: Get all of the offers associated to the current property marketing
        role..
      operationId: Role_OffersByidBypageSizeBypageNumberByexcludeDrafts
      x-api-path-slug: apiroleidoffers-get
      parameters:
      - in: query
        name: excludeDrafts
      - in: path
        name: id
        description: The id of the role to get the offers for
      - in: query
        name: pageNumber
        description: Page number to return
      - in: query
        name: pageSize
        description: Page size to return
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Of
      - Offers
      - Associated
      - To
      - Current
      - Property
      - Marketing
      - Role
  /api/role/{id}/offersbasic:
    get:
      summary: Get a basic list of offers associated to the current property marketing
        role.
      description: Get a basic list of offers associated to the current property marketing
        role..
      operationId: Role_OffersBasicByid
      x-api-path-slug: apiroleidoffersbasic-get
      parameters:
      - in: path
        name: id
        description: The id of the marketing role to get the offers for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Basic
      - List
      - Of
      - Offers
      - Associated
      - To
      - Current
      - Property
      - Marketing
      - Role
  /api/role/{roleId}/viewingsbasic:
    get:
      summary: Get a basic list of all viewings for a particular marketing role.
      description: Get a basic list of all viewings for a particular marketing role..
      operationId: Role_BasicViewingsByroleId
      x-api-path-slug: apiroleroleidviewingsbasic-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: The id of the marketing role to get the viewings for
      responses:
        200:
          description: OK
      tags:
      - Basic
      - List
      - Of
      - ""
      - Viewingsa
      - Particular
      - Marketing
      - Role
  /api/role/{id}/viewings:
    get:
      summary: Get all of the viewings associated to the current property marketing
        role.
      description: Get all of the viewings associated to the current property marketing
        role..
      operationId: Role_ViewingsByidBypageSizeBypageNumberByexcludeDrafts
      x-api-path-slug: apiroleidviewings-get
      parameters:
      - in: query
        name: excludeDrafts
      - in: path
        name: id
        description: The id of the role to get the offers for
      - in: query
        name: pageNumber
        description: Page number to return
      - in: query
        name: pageSize
        description: Page size to return
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Of
      - Viewings
      - Associated
      - To
      - Current
      - Property
      - Marketing
      - Role
  /api/role/{id}/setclosingdate:
    post:
      summary: Sets the role closing date
      description: Sets the role closing date.
      operationId: Role_SetClosingDateByidBydataContract
      x-api-path-slug: apiroleidsetclosingdate-post
      parameters:
      - in: body
        name: dataContract
        description: The closing data datacontract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Role
      - Closing
      - Date
  /api/role/{id}/setdefaultimage:
    put:
      summary: Sets the default image of a property marketing role
      description: Sets the default image of a property marketing role.
      operationId: Role_SetDefaultImageByidBydocumentId
      x-api-path-slug: apiroleidsetdefaultimage-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to set as the default image
      - in: path
        name: id
        description: The id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Default
      - Image
      - Of
      - Property
      - Marketing
      - Role
  /api/role/{id}/confirmcompliancechecks:
    put:
      summary: Confirms the compliance checks have been carried out on a marketing
        role
      description: Confirms the compliance checks have been carried out on a marketing
        role.
      operationId: Role_ConfirmComplianceChecksByidBynegotiatorId
      x-api-path-slug: apiroleidconfirmcompliancechecks-put
      parameters:
      - in: path
        name: id
        description: The id of the role
      - in: query
        name: negotiatorId
        description: The negotiator id who confirmed the checks
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Confirms
      - Compliance
      - Checks
      - Have
      - Been
      - Carried
      - Out
      - "On"
      - Marketing
      - Role
  /api/role/{id}/setflag:
    put:
      summary: Sets a flag on a property marketing role
      description: Sets a flag on a property marketing role.
      operationId: Role_SetFlagByidBysetMarketingFlagDataContract
      x-api-path-slug: apiroleidsetflag-put
      parameters:
      - in: path
        name: id
        description: The id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: setMarketingFlagDataContract
        description: The flag detail
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Flag
      - "On"
      - Property
      - Marketing
      - Role
  /api/role/{id}/setcompliancechecks:
    put:
      summary: Set the compliance checks on a property marketing role i.e. Valid Epc,
        Proof of ID or Proof of Ownership.
      description: Set the compliance checks on a property marketing role i.e. valid
        epc, proof of id or proof of ownership..
      operationId: Role_SetComplianceChecksByidBysetComplianceChecksDataContract
      x-api-path-slug: apiroleidsetcompliancechecks-put
      parameters:
      - in: path
        name: id
        description: The id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: setComplianceChecksDataContract
        description: The flag detail
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Set
      - Compliance
      - Checks
      - "On"
      - Property
      - Marketing
      - Role
      - I
      - E
      - ""
      - Valid
      - Epc
      - ""
      - Proof
      - Of
      - ID
      - Proof
      - Of
      - Ownership
  /api/role/{id}/changeteam:
    put:
      summary: Change the owining team of a Role
      description: Change the owining team of a role.
      operationId: Role_ChangeTeamByidByteamId
      x-api-path-slug: apiroleidchangeteam-put
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: teamId
      responses:
        200:
          description: OK
      tags:
      - Change
      - Owining
      - Team
      - Of
      - Role
  /api/role/{id}/changebranch:
    post:
      summary: Change the branch of a role
      description: Change the branch of a role.
      operationId: Role_ChangeBranchByidBybranchId
      x-api-path-slug: apiroleidchangebranch-post
      parameters:
      - in: query
        name: branchId
        description: Id of Branch
      - in: path
        name: id
        description: Id of Role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Change
      - Branch
      - Of
      - Role
  /api/role/{roleId}/setcontractenddate:
    post:
      summary: Change the branch of a role
      description: Change the branch of a role.
      operationId: Role_SetContractEndDateByroleIdByendDateDatContact
      x-api-path-slug: apiroleroleidsetcontractenddate-post
      parameters:
      - in: body
        name: endDateDatContact
        description: Id of Branch
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: The role id
      responses:
        200:
          description: OK
      tags:
      - Change
      - Branch
      - Of
      - Role
  /api/role/createreferralevent:
    post:
      summary: Creates a referral event on the role
      description: Creates a referral event on the role.
      operationId: Role_CreateReferralEventByreferralData
      x-api-path-slug: apirolecreatereferralevent-post
      parameters:
      - in: body
        name: referralData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Referral
      - Event
      - "On"
      - Role
  /api/role/{id}/copy:
    post:
      summary: Clones a property marketing role
      description: Clones a property marketing role.
      operationId: Role_CopySalesMarketingRoleByid
      x-api-path-slug: apiroleidcopy-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Clones
      - Property
      - Marketing
      - Role
  /api/role/{id}/setholdingdeposit:
    post:
      summary: Set holding deposit for marketing role
      description: Set holding deposit for marketing role.
      operationId: Role_SetHoldingDepositByidBysetHoldingDepositDataContract
      x-api-path-slug: apiroleidsetholdingdeposit-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: setHoldingDepositDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Set
      - Holding
      - Depositmarketing
      - Role
  /api/role/{id}/removeholdingdeposit:
    post:
      summary: Remove holding deposit from role
      description: Remove holding deposit from role.
      operationId: Role_RemoveHoldingDepositByidByrelatedRoleId
      x-api-path-slug: apiroleidremoveholdingdeposit-post
      parameters:
      - in: path
        name: id
      - in: query
        name: relatedRoleId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Holding
      - Deposit
      - From
      - Role
  /api/role/{id}/releaseholdingdeposit:
    post:
      summary: Reset the holding deposit for a role
      description: Reset the holding deposit for a role.
      operationId: Role_ReleaseHoldingDepositByidByrelatedRoleId
      x-api-path-slug: apiroleidreleaseholdingdeposit-post
      parameters:
      - in: path
        name: id
      - in: query
        name: relatedRoleId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Reset
      - Holding
      - Deposita
      - Role
  /api/progression/sales/instructtosell:
    post:
      summary: Instructs a role to be sold
      description: Instructs a role to be sold.
      operationId: SalesProgression_InstructToSellByinstructToSellCommandDataContract
      x-api-path-slug: apiprogressionsalesinstructtosell-post
      parameters:
      - in: body
        name: instructToSellCommandDataContract
        description: Details of the instruction
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Instructs
      - Role
      - To
      - Be
      - Sold
  /api/progression/sales/exchange:
    post:
      summary: Exchanges a sales role
      description: Exchanges a sales role.
      operationId: SalesProgression_ExchangeByexchangeCommandDataContract
      x-api-path-slug: apiprogressionsalesexchange-post
      parameters:
      - in: body
        name: exchangeCommandDataContract
        description: Details of the exchange
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Exchanges
      - Sales
      - Role
  /api/progression/sales/complete:
    post:
      summary: Completes a sales role
      description: Completes a sales role.
      operationId: SalesProgression_CompleteBycompleteCommandDataContract
      x-api-path-slug: apiprogressionsalescomplete-post
      parameters:
      - in: body
        name: completeCommandDataContract
        description: Details of the completion
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Completes
      - Sales
      - Role
  /api/progression/sales/setestimatedcompletiondate:
    put:
      summary: Set the estimated completion date on a purchasing role
      description: Set the estimated completion date on a purchasing role.
      operationId: SalesProgression_SetEstimatedCompletionDateByprogressionDateCommandDataContract
      x-api-path-slug: apiprogressionsalessetestimatedcompletiondate-put
      parameters:
      - in: body
        name: progressionDateCommandDataContract
        description: The id and datetime of the purchasing role to update the estimated
          completion date for
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Estimated
      - Completion
      - Date
      - "On"
      - Purchasing
      - Role
  /api/progression/sales/setestimatedexchangedate:
    put:
      summary: Set the estimated exchange date on a purchasing role
      description: Set the estimated exchange date on a purchasing role.
      operationId: SalesProgression_SetEstimatedExchangeDateByprogressionDateCommandDataContract
      x-api-path-slug: apiprogressionsalessetestimatedexchangedate-put
      parameters:
      - in: body
        name: progressionDateCommandDataContract
        description: The id and datetime of the purchasing role to update the estimated
          exchange date for
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Estimated
      - Exchange
      - Date
      - "On"
      - Purchasing
      - Role
  /api/progression/sales/fallenthrough:
    post:
      summary: Set Marketing Role as Fallen Through
      description: Set marketing role as fallen through.
      operationId: SalesProgression_FallenThroughByfallenThroughDataContract
      x-api-path-slug: apiprogressionsalesfallenthrough-post
      parameters:
      - in: body
        name: fallenThroughDataContract
        description: Details of the fallen though
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Marketing
      - Role
      - As
      - Fallen
      - Through
  /api/simplepropertyrole/{roleId}:
    get:
      summary: Get a property with an associated role by their Id's
      description: Get a property with an associated role by their id's.
      operationId: SimplePropertyRole_GetByroleId
      x-api-path-slug: apisimplepropertyroleroleid-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: The role Id
      responses:
        200:
          description: OK
      tags:
      - Property
      - Associated
      - Role
      - By
      - Their
      - Ids
  /api/admin/system/sendliveportalupdatemessage:
    post:
      summary: "Sends a message to the LivePortalJobHandler that says \r\nthe specified
        property marketing role has changed"
      description: "Sends a message to the liveportaljobhandler that says \r\nthe
        specified property marketing role has changed."
      operationId: System_SendLivePortalUpdateMessageBypropertyMarketingRoleId
      x-api-path-slug: apiadminsystemsendliveportalupdatemessage-post
      parameters:
      - in: query
        name: propertyMarketingRoleId
        description: The property marketing role ID
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sends
      - Message
      - To
      - LivePortalJobHandler
      - That
      - Says
      - The
      - Specified
      - Property
      - Marketing
      - Role
      - Has
      - Changed
  /api/tenancy/{id}/detachdocument:
    put:
      summary: Detaches a document from a tenancy role
      description: Detaches a document from a tenancy role.
      operationId: Tenancy_DetachDocumentByidBydocumentId
      x-api-path-slug: apitenancyiddetachdocument-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to detach
      - in: path
        name: id
        description: The id of the role to detach the document from
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Detaches
      - Document
      - From
      - Tenancy
      - Role
  /api/tenancy/{id}/rentdemands:
    get:
      summary: Get rent demands for the tenant role
      description: Get rent demands for the tenant role.
      operationId: Tenancy_GetRentDemandsByidBystartDateByendDateByincludeForecastBypageSizeBypageNumber
      x-api-path-slug: apitenancyidrentdemands-get
      parameters:
      - in: query
        name: endDate
      - in: path
        name: id
      - in: query
        name: includeForecast
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: startDate
      responses:
        200:
          description: OK
      tags:
      - Rent
      - Demandsthe
      - Tenant
      - Role
  /api/tenantreferncing/case/{tenancyRoleId}:
    get:
      summary: Gets a tenancy referencing case based on the role id supplied
      description: Gets a tenancy referencing case based on the role id supplied.
      operationId: TenantReferencing_GetCaseBytenancyRoleId
      x-api-path-slug: apitenantreferncingcasetenancyroleid-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The id of the tenancy role the case linked to
      responses:
        200:
          description: OK
      tags:
      - S
      - Tenancy
      - Referencing
      - Case
      - Based
      - "On"
      - Role
      - Id
      - Supplied
    post:
      summary: Creates a tenancy referencing case using the role id supplied
      description: Creates a tenancy referencing case using the role id supplied.
      operationId: TenantReferencing_CreateCaseBytenancyRoleId
      x-api-path-slug: apitenantreferncingcasetenancyroleid-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The tenancy id the created case will be linked to
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Tenancy
      - Referencing
      - Case
      - Using
      - Role
      - Id
      - Supplied
  /api/group/{id}/searching/{roleId}/matches:
    get:
      summary: Get property matches for a Searching Role for a Group
      description: Get property matches for a searching role for a group.
      operationId: Group_PropertyMatchesByidByroleIdBypageSizeBypageNumberBysort
      x-api-path-slug: apigroupidsearchingroleidmatches-get
      parameters:
      - in: path
        name: id
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
      - in: query
        name: sort
      responses:
        200:
          description: OK
      tags:
      - Property
      - Matchesa
      - Searching
      - Rolea
      - Group
    post:
      summary: Get property matches for a Searching Role for a Group
      description: Get property matches for a searching role for a group.
      operationId: Group_PropertyMatchesByidByroleIdByfilterBypageSizeBypageNumberBysort
      x-api-path-slug: apigroupidsearchingroleidmatches-post
      parameters:
      - in: body
        name: filter
        description: Match filter
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Group Id
      - in: query
        name: pageNumber
        description: Page number
      - in: query
        name: pageSize
        description: Amount of results per page
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: Role Id
      - in: query
        name: sort
        description: How to sort the results
      responses:
        200:
          description: OK
      tags:
      - Property
      - Matchesa
      - Searching
      - Rolea
      - Group
  /api/role/{id}/addgrouptopropertyrole:
    put:
      summary: Creates/Adds a group to the supplied roleId
      description: Creates/adds a group to the supplied roleid.
      operationId: Role_AddGroupToPropertyRoleByidBydatacontract
      x-api-path-slug: apiroleidaddgrouptopropertyrole-put
      parameters:
      - in: body
        name: datacontract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - S
      - Group
      - To
      - Supplied
      - RoleId
  /api/group/{id}/salessearching:
    get:
      summary: Get Sales Searching Roles for a Group
      description: Get sales searching roles for a group.
      operationId: Group_SearchingSalesRolesByidBypageSizeBypageNumber
      x-api-path-slug: apigroupidsalessearching-get
      parameters:
      - in: path
        name: id
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Searching
      - Rolesa
      - Group
  /api/group/{id}/lettingssearching:
    get:
      summary: Get Lettings Searching Roles for a Group
      description: Get lettings searching roles for a group.
      operationId: Group_SearchingLettingsRolesByidBypageSizeBypageNumber
      x-api-path-slug: apigroupidlettingssearching-get
      parameters:
      - in: path
        name: id
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Lettings
      - Searching
      - Rolesa
      - Group
  /api/group/{id}/roles:
    get:
      summary: Get the roles for a Group by Group id
      description: Get the roles for a group by group id.
      operationId: Group_RolesByidBypageSizeBypageNumberByroleTypesByroleStatuses
      x-api-path-slug: apigroupidroles-get
      parameters:
      - in: path
        name: id
        description: The id of the property to get the roles for
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roleStatuses
      - in: query
        name: roleTypes
      responses:
        200:
          description: OK
      tags:
      - Rolesa
      - Group
      - By
      - Group
      - Id
  /api/people/{id}/searching:
    get:
      summary: Get Searching Roles for a Person
      description: Get searching roles for a person.
      operationId: People_SearchingRolesByid
      x-api-path-slug: apipeopleidsearching-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Searching
      - Rolesa
      - Person
  /api/people/{id}/selling:
    get:
      summary: Get Selling Roles for a Person
      description: Get selling roles for a person.
      operationId: People_SellingRolesByid
      x-api-path-slug: apipeopleidselling-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Selling
      - Rolesa
      - Person
  /api/people/{id}/letting:
    get:
      summary: Get Letting Roles for a Person
      description: Get letting roles for a person.
      operationId: People_LettingRolesByid
      x-api-path-slug: apipeopleidletting-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Letting
      - Rolesa
      - Person
  /api/property/{id}/roles:
    get:
      summary: Get the roles for a property by property id
      description: Get the roles for a property by property id.
      operationId: Property_RolesByidBypageSizeBypageNumberByroleTypesByroleStatuses
      x-api-path-slug: apipropertyidroles-get
      parameters:
      - in: path
        name: id
        description: The id of the property to get the roles for
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roleStatuses
      - in: query
        name: roleTypes
      responses:
        200:
          description: OK
      tags:
      - Rolesa
      - Property
      - By
      - Property
      - Id
  /api/group/{id}/deletesearch/{searchingRoleId}:
    delete:
      summary: Deletes Search Criteria from a Group
      description: Deletes search criteria from a group.
      operationId: Group_DeleteSearchByidBysearchingRoleId
      x-api-path-slug: apigroupiddeletesearchsearchingroleid-delete
      parameters:
      - in: path
        name: id
        description: The id of the group
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: searchingRoleId
        description: The id of the searching role to delete
      responses:
        200:
          description: OK
      tags:
      - S
      - Search
      - Criteria
      - From
      - Group
  /api/progression/lettings/remarket:
    post:
      summary: Remarket a Letting. Completes the PropertyLettingRole and the TenantRole
        and creates a new PropertyLettingRole
      description: Remarket a letting. completes the propertylettingrole and the tenantrole
        and creates a new propertylettingrole.
      operationId: LettingsProgression_RemarketByremarketCommandDataContract
      x-api-path-slug: apiprogressionlettingsremarket-post
      parameters:
      - in: body
        name: remarketCommandDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Remarket
      - Letting
      - ""
      - Completes
      - PropertyLettingRole
      - TenantRole
      - Creates
      - New
      - PropertyLettingRole
  /api/progression/lettings/{tenantRoleId}/getguarantors:
    get:
      summary: ""
      description: .
      operationId: LettingsProgression_GetGuarantorsBytenantRoleId
      x-api-path-slug: apiprogressionlettingstenantroleidgetguarantors-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenantRoleId
      responses:
        200:
          description: OK
      tags:
      - ""
  /api/role/lettings/{id}/setheadlandlord:
    put:
      summary: Set the head landlord for PropertyLettingRole
      description: Set the head landlord for propertylettingrole.
      operationId: LettingRole_SetHeadLandlordByidBypersonIdBygroupId
      x-api-path-slug: apirolelettingsidsetheadlandlord-put
      parameters:
      - in: query
        name: groupId
      - in: path
        name: id
      - in: query
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Set
      - Head
      - LandlordPropertyLettingRole
  /api/role/lettings/{id}/setnrldetails:
    put:
      summary: Set the NRL details for a landlord on a PropertyLettingRole
      description: Set the nrl details for a landlord on a propertylettingrole.
      operationId: LettingRole_SetNRLDetailsByidBydataContract
      x-api-path-slug: apirolelettingsidsetnrldetails-put
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
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
      - NRL
      - Detailsa
      - Landlord
      - "On"
      - PropertyLettingRole
  /api/role/lettings/{id}/setrentshare:
    put:
      summary: Set the rent share for landlords on PropertyLettingRole
      description: Set the rent share for landlords on propertylettingrole.
      operationId: LettingRole_SetRentShareByidByshareDataContracts
      x-api-path-slug: apirolelettingsidsetrentshare-put
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: shareDataContracts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Set
      - Rent
      - Sharelandlords
      - "On"
      - PropertyLettingRole
  /api/role/lettings/{id}/settobsigned:
    put:
      summary: Set the terms of business for a landlord on a PropertyLettingRole
      description: Set the terms of business for a landlord on a propertylettingrole.
      operationId: LettingRole_SetTOBSignedByidBydataContract
      x-api-path-slug: apirolelettingsidsettobsigned-put
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
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
      - Terms
      - Of
      - Businessa
      - Landlord
      - "On"
      - PropertyLettingRole
  /api/role/sales/{id}/getepc:
    get:
      summary: Gets EPC from the supplied propertyRoleId
      description: Gets epc from the supplied propertyroleid.
      operationId: SalesRole_GetEPCByid
      x-api-path-slug: apirolesalesidgetepc-get
      parameters:
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - EPC
      - From
      - Supplied
      - PropertyRoleId
  /api/role/sales/{id}/saveepc:
    post:
      summary: Creates/Overrides the EPC for the supplied propertyRoleId
      description: Creates/overrides the epc for the supplied propertyroleid.
      operationId: SalesRole_SaveEPCByidBydatacontract
      x-api-path-slug: apirolesalesidsaveepc-post
      parameters:
      - in: body
        name: datacontract
        description: The EPC information
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Overrides
      - EPCthe
      - Supplied
      - PropertyRoleId
  /api/role/{id}/addfee:
    put:
      summary: Add a fee for a given PropertyMarketingRole.
      description: Add a fee for a given propertymarketingrole..
      operationId: Role_AddFeeByidByfeeDataContract
      x-api-path-slug: apiroleidaddfee-put
      parameters:
      - in: body
        name: feeDataContract
        description: The fee to add to the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: the id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Feea
      - Given
      - PropertyMarketingRole
  /api/role/{id}/removefee:
    put:
      summary: Remove a fee from a given PropertyMarketingRole.
      description: Remove a fee from a given propertymarketingrole..
      operationId: Role_RemoveFeeByidByfeeId
      x-api-path-slug: apiroleidremovefee-put
      parameters:
      - in: query
        name: feeId
        description: The Id of the fee to remove
      - in: path
        name: id
        description: the id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Fee
      - From
      - Given
      - PropertyMarketingRole
  /api/role/{id}/updatefees:
    put:
      summary: Update the fee for a given PropertyMarketingRole.
      description: Update the fee for a given propertymarketingrole..
      operationId: Role_UpdateFeesByidByfeeDataContracts
      x-api-path-slug: apiroleidupdatefees-put
      parameters:
      - in: body
        name: feeDataContracts
        description: The fees to apply to the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: the id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Feea
      - Given
      - PropertyMarketingRole
  /api/role/{id}/updateprice:
    put:
      summary: Update price for a given PropertySalesRole.
      description: Update price for a given propertysalesrole..
      operationId: Role_UpdatePriceByidByupdatePriceDataContract
      x-api-path-slug: apiroleidupdateprice-put
      parameters:
      - in: path
        name: id
        description: the id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: updatePriceDataContract
        description: UpdatePriceDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Pricea
      - Given
      - PropertySalesRole
  /api/roomdescription/{id}/attachtorole:
    put:
      summary: Attach a RoomDescription to a PropertyMarketingRole
      description: Attach a roomdescription to a propertymarketingrole.
      operationId: RoomDescription_AttachToRoleByidByroleId
      x-api-path-slug: apiroomdescriptionidattachtorole-put
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roleId
      responses:
        200:
          description: OK
      tags:
      - Attach
      - RoomDescription
      - To
      - PropertyMarketingRole
  /api/tenantreferncing/addapplication/{caseId}/{tenancyRoleId}/{personId}/{productId}:
    post:
      summary: Creates a tenancy referencing application for a case using the details
        supplied
      description: Creates a tenancy referencing application for a case using the
        details supplied.
      operationId: TenantReferencing_CreateApplicationBycaseIdBytenancyRoleIdBypersonIdByproductId
      x-api-path-slug: apitenantreferncingaddapplicationcaseidtenancyroleidpersonidproductid-post
      parameters:
      - in: path
        name: caseId
        description: The id of the case to add the Application to
      - in: path
        name: personId
        description: The id of the individual the application is for
      - in: path
        name: productId
        description: The id of the product the client has chosen
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The role id of the tenancy the case is linked to
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Tenancy
      - Referencing
      - Applicationa
      - Case
      - Using
      - Details
      - Supplied
  /api/tenantreferncing/addguarantor/{caseId}/{tenancyRoleId}/{personId}:
    post:
      summary: Adds a Guarantor to a tenancy referencing application for a case using
        the details supplied
      description: Adds a guarantor to a tenancy referencing application for a case
        using the details supplied.
      operationId: TenantReferencing_CreateApplicationBycaseIdBytenancyRoleIdBypersonId
      x-api-path-slug: apitenantreferncingaddguarantorcaseidtenancyroleidpersonid-post
      parameters:
      - in: path
        name: caseId
        description: The id of the case to add the Guarantor to
      - in: path
        name: personId
        description: The id of the individual the application is for
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The role id of the tenancy the case is linked to
      responses:
        200:
          description: OK
      tags:
      - S
      - Guarantor
      - To
      - Tenancy
      - Referencing
      - Applicationa
      - Case
      - Using
      - Details
      - Supplied
  /api/tenantreferncing/submitcase/{tenancyRoleId}/{caseId}:
    put:
      summary: Submits a tenant referencing case for processing
      description: Submits a tenant referencing case for processing.
      operationId: TenantReferencing_SubmitCaseForReferencingBytenancyRoleIdBycaseId
      x-api-path-slug: apitenantreferncingsubmitcasetenancyroleidcaseid-put
      parameters:
      - in: path
        name: caseId
        description: The id of the case to submit
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: tenancyRoleId
        description: The role id of the tenancy the case is linked to
      responses:
        200:
          description: OK
      tags:
      - Submits
      - Tenant
      - Referencing
      - Caseprocessing
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