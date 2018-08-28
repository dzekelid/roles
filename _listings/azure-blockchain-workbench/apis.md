---
name: Azure Blockchain Workbench
x-slug: azure-blockchain-workbench
description: Azure Blockchain Workbench helps organizations build rich, integrated
  multi-party blockchain applications quickly and easily. Azure Blockchain Workbench
  REST API provides developers and information workers a way to integrate to blockchain
  applications. For example, a developer can use the REST API to enable IoT devices
  to send data to a blockchain application. Or, an information worker can use the
  REST API and Power BI to create visualization of blockchain data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
x-kinRank: "7"
x-alexaRank: ""
tags: Roles
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-get
  description: |-
    Get a role assignment of the specified blockchain application matching a specific user role assignment ID.
                 Users who are Workbench administrators get the role assignment. Non-Workbench administrators get the role assignment
                 if they are associated in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Put Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-put
  description: Updates the specified role assignment. This method can only be performed
    by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-put-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Roleassignments
    Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete
  description: |-
    Deletes the specified role assignment. This method can only be performed by users who are
                 Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-get
  description: |-
    List all role assignments of the specified blockchain application. Users who are Workbench administrators
                 get all role assignments. Non-Workbench administrators get all their role assignments. Roles are specified
                 in the Workbench application configuration and can be retrieved from GET /applications/{applicationID}.
                 Also, user information can be retrieved from GET /users/{userID}.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-openapi.md
- name: Azure Blockchain Workbench REST API - Post Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-post
  description: |-
    Creates a user-to-role mapping in the specified blockchain application. This method can only be performed by
                 users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-post-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-get
  description: |-
    Get a role assignment of the specified blockchain application matching a specific user role assignment ID.
                 Users who are Workbench administrators get the role assignment. Non-Workbench administrators get the role assignment
                 if they are associated in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Put Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-put
  description: Updates the specified role assignment. This method can only be performed
    by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-put-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Roleassignments
    Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete
  description: |-
    Deletes the specified role assignment. This method can only be performed by users who are
                 Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-get
  description: |-
    List all role assignments of the specified blockchain application. Users who are Workbench administrators
                 get all role assignments. Non-Workbench administrators get all their role assignments. Roles are specified
                 in the Workbench application configuration and can be retrieved from GET /applications/{applicationID}.
                 Also, user information can be retrieved from GET /users/{userID}.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-openapi.md
- name: Azure Blockchain Workbench REST API - Post Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-post
  description: |-
    Creates a user-to-role mapping in the specified blockchain application. This method can only be performed by
                 users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-post-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-get
  description: |-
    Get a role assignment of the specified blockchain application matching a specific user role assignment ID.
                 Users who are Workbench administrators get the role assignment. Non-Workbench administrators get the role assignment
                 if they are associated in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Put Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-put
  description: Updates the specified role assignment. This method can only be performed
    by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-put-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Roleassignments
    Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete
  description: |-
    Deletes the specified role assignment. This method can only be performed by users who are
                 Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-get
  description: |-
    List all role assignments of the specified blockchain application. Users who are Workbench administrators
                 get all role assignments. Non-Workbench administrators get all their role assignments. Roles are specified
                 in the Workbench application configuration and can be retrieved from GET /applications/{applicationID}.
                 Also, user information can be retrieved from GET /users/{userID}.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-openapi.md
- name: Azure Blockchain Workbench REST API - Post Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-post
  description: |-
    Creates a user-to-role mapping in the specified blockchain application. This method can only be performed by
                 users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-post-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-get
  description: |-
    Get a role assignment of the specified blockchain application matching a specific user role assignment ID.
                 Users who are Workbench administrators get the role assignment. Non-Workbench administrators get the role assignment
                 if they are associated in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Put Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-put
  description: Updates the specified role assignment. This method can only be performed
    by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-put-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Roleassignments
    Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete
  description: |-
    Deletes the specified role assignment. This method can only be performed by users who are
                 Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-get
  description: |-
    Get a role assignment of the specified blockchain application matching a specific user role assignment ID.
                 Users who are Workbench administrators get the role assignment. Non-Workbench administrators get the role assignment
                 if they are associated in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Put Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-put
  description: Updates the specified role assignment. This method can only be performed
    by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-put-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Roleassignments
    Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete
  description: |-
    Deletes the specified role assignment. This method can only be performed by users who are
                 Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-get
  description: |-
    List all role assignments of the specified blockchain application. Users who are Workbench administrators
                 get all role assignments. Non-Workbench administrators get all their role assignments. Roles are specified
                 in the Workbench application configuration and can be retrieved from GET /applications/{applicationID}.
                 Also, user information can be retrieved from GET /users/{userID}.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-openapi.md
- name: Azure Blockchain Workbench REST API - Post Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-post
  description: |-
    Creates a user-to-role mapping in the specified blockchain application. This method can only be performed by
                 users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-post-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-get
  description: |-
    Get a role assignment of the specified blockchain application matching a specific user role assignment ID.
                 Users who are Workbench administrators get the role assignment. Non-Workbench administrators get the role assignment
                 if they are associated in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Put Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-put
  description: Updates the specified role assignment. This method can only be performed
    by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-put-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Roleassignments
    Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete
  description: |-
    Deletes the specified role assignment. This method can only be performed by users who are
                 Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Roleassignments
    Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete
  description: |-
    Deletes the specified role assignment. This method can only be performed by users who are
                 Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Put Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-put
  description: Updates the specified role assignment. This method can only be performed
    by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-put-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-get
  description: |-
    Get a role assignment of the specified blockchain application matching a specific user role assignment ID.
                 Users who are Workbench administrators get the role assignment. Non-Workbench administrators get the role assignment
                 if they are associated in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Roleassignments
    Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete
  description: |-
    Deletes the specified role assignment. This method can only be performed by users who are
                 Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Put Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-put
  description: Updates the specified role assignment. This method can only be performed
    by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-put-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments Roleassignmentid
  x-api-slug: apiv1applicationsapplicationidroleassignmentsroleassignmentid-get
  description: |-
    Get a role assignment of the specified blockchain application matching a specific user role assignment ID.
                 Users who are Workbench administrators get the role assignment. Non-Workbench administrators get the role assignment
                 if they are associated in the application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignmentsroleassignmentid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Post Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-post
  description: |-
    Creates a user-to-role mapping in the specified blockchain application. This method can only be performed by
                 users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-post-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Roleassignments
  x-api-slug: apiv1applicationsapplicationidroleassignments-get
  description: |-
    List all role assignments of the specified blockchain application. Users who are Workbench administrators
                 get all role assignments. Non-Workbench administrators get all their role assignments. Roles are specified
                 in the Workbench application configuration and can be retrieved from GET /applications/{applicationID}.
                 Also, user information can be retrieved from GET /users/{userID}.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidroleassignments-get-openapi.md
x-common:
- type: x-blog
  url: https://azure.microsoft.com/en-us/blog/topics/blockchain/
- type: x-blog-rss
  url: https://azurecomcdn.azureedge.net/en-us/blog/topics/blockchain/feed/
- type: x-openapi
  url: https://raw.githubusercontent.com/Azure-Samples/blockchain/master/blockchain-workbench/rest-api-samples/swagger/swagger.json
- type: x-website
  url: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
- type: x-api-gallery
  url: http://azure.billing.api.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.blockchain.workbench.stack.network
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---