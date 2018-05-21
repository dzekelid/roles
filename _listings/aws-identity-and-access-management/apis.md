---
name: AWS Identity and Access Management
x-slug: aws-identity-and-access-management
description: AWS Identity and Access Management (IAM) enables you to securely control
  access to AWS services and resources for your users. Using IAM, you can create and
  manage AWS users and groups, and use permissions to allow and deny their access
  to AWS resources.IAM is a feature of your AWS account offered at no additional charge.
  You will be charged only for use of other AWS services by your users.To get started
  using IAM, orif you have already registered with AWS, go to theAWS Management Consoleand
  get started with theseIAM Best Practices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
x-kinRank: "10"
x-alexaRank: ""
tags: Roles
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Identity and Access Management API Create Role
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new role for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateRole
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actioncreaterole-get-openapi.md
- name: AWS Identity and Access Management API Delete Role
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteRole
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondeleterole-get-openapi.md
- name: AWS Identity and Access Management API Get Role
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about the specified role, including the role's path, GUID, ARN,
          and the role's trust policy that grants permission to assume the role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetRole
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiongetrole-get-openapi.md
- name: AWS Identity and Access Management API List Roles
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the IAM roles that have the specified path prefix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListRoles
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistroles-get-openapi.md
- name: AWS Identity and Access Management API
  x-api-slug: aws-identity-and-access-management-api
  description: AWS Identity and Access Management (IAM) enables you to securely control
    access to AWS services and resources for your users. Using IAM, you can create
    and manage AWS users and groups, and use permissions to allow and deny their access
    to AWS resources.IAM is a feature of your AWS account offered at no additional
    charge. You will be charged only for use of other AWS services by your users.To
    get started using IAM, orif you have already registered with AWS, go to theAWS
    Management Consoleand get started with theseIAM Best Practices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/openapi.md
x-common:
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=323
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/sts/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/IAM/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/iam/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=76
- type: x-getting-started
  url: https://aws.amazon.com/iam/getting-started/
- type: x-partners
  url: https://aws.amazon.com/iam/partners/
- type: x-tools
  url: http://aws.amazon.com/cli
- type: x-website
  url: https://aws.amazon.com/iam/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---