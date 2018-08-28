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
x-alexaRank: "0"
tags: Roles
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Identity and Access Management API - Create Role
  x-api-slug: actioncreaterole-get
  description: Creates a new role for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actioncreaterole-get-openapi.md
- name: AWS Identity and Access Management API - Delete Role
  x-api-slug: actiondeleterole-get
  description: Deletes the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondeleterole-get-openapi.md
- name: AWS Identity and Access Management API - Get Role
  x-api-slug: actiongetrole-get
  description: |-
    Retrieves information about the specified role, including the role's path, GUID, ARN,
          and the role's trust policy that grants permission to assume the role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiongetrole-get-openapi.md
- name: AWS Identity and Access Management API - List Roles
  x-api-slug: actionlistroles-get
  description: Lists the IAM roles that have the specified path prefix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistroles-get-openapi.md
- name: AWS Identity and Access Management API - Remove Role From Instance Profile
  x-api-slug: actionremoverolefrominstanceprofile-get
  description: Removes the specified IAM role from the specified EC2 instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionremoverolefrominstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API - Add Role To Instance Profile
  x-api-slug: actionaddroletoinstanceprofile-get
  description: Adds the specified IAM role to the specified instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API - Attach Role Policy
  x-api-slug: actionattachrolepolicy-get
  description: Attaches the specified managed policy to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionattachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Delete Role Policy
  x-api-slug: actiondeleterolepolicy-get
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondeleterolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Detach Role Policy
  x-api-slug: actiondetachrolepolicy-get
  description: Removes the specified managed policy from the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondetachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Role Policy
  x-api-slug: actiongetrolepolicy-get
  description: |-
    Retrieves the specified inline policy document that is embedded with the specified
          IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiongetrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - List Role Policies
  x-api-slug: actionlistrolepolicies-get
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API - Put Role Policy
  x-api-slug: actionputrolepolicy-get
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionputrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Add Role To Instance Profile
  x-api-slug: actionaddroletoinstanceprofile-get
  description: Adds the specified IAM role to the specified instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API - Attach Role Policy
  x-api-slug: actionattachrolepolicy-get
  description: Attaches the specified managed policy to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionattachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Create Role
  x-api-slug: actioncreaterole-get
  description: Creates a new role for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actioncreaterole-get-openapi.md
- name: AWS Identity and Access Management API - Delete Role
  x-api-slug: actiondeleterole-get
  description: Deletes the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondeleterole-get-openapi.md
- name: AWS Identity and Access Management API - Delete Role Policy
  x-api-slug: actiondeleterolepolicy-get
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondeleterolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Detach Role Policy
  x-api-slug: actiondetachrolepolicy-get
  description: Removes the specified managed policy from the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondetachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Role
  x-api-slug: actiongetrole-get
  description: |-
    Retrieves information about the specified role, including the role's path, GUID, ARN,
          and the role's trust policy that grants permission to assume the role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiongetrole-get-openapi.md
- name: AWS Identity and Access Management API - Get Role Policy
  x-api-slug: actiongetrolepolicy-get
  description: |-
    Retrieves the specified inline policy document that is embedded with the specified
          IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiongetrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - List Attached Role Policies
  x-api-slug: actionlistattachedrolepolicies-get
  description: Lists all managed policies that are attached to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistattachedrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API - List Instance Profiles For Role
  x-api-slug: actionlistinstanceprofilesforrole-get
  description: Lists the instance profiles that have the specified associated IAM
    role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistinstanceprofilesforrole-get-openapi.md
- name: AWS Identity and Access Management API - List Role Policies
  x-api-slug: actionlistrolepolicies-get
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API - List Roles
  x-api-slug: actionlistroles-get
  description: Lists the IAM roles that have the specified path prefix.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistroles-get-openapi.md
- name: AWS Identity and Access Management API - Put Role Policy
  x-api-slug: actionputrolepolicy-get
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionputrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Remove Role From Instance Profile
  x-api-slug: actionremoverolefrominstanceprofile-get
  description: Removes the specified IAM role from the specified EC2 instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionremoverolefrominstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API - Update Assume Role Policy
  x-api-slug: actionupdateassumerolepolicy-get
  description: Updates the policy that grants an IAM entity permission to assume a
    role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionupdateassumerolepolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionupdateassumerolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Remove Role From Instance Profile
  x-api-slug: actionremoverolefrominstanceprofile-get
  description: Removes the specified IAM role from the specified EC2 instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionremoverolefrominstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API - Add Role To Instance Profile
  x-api-slug: actionaddroletoinstanceprofile-get
  description: Adds the specified IAM role to the specified instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API - Attach Role Policy
  x-api-slug: actionattachrolepolicy-get
  description: Attaches the specified managed policy to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionattachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Delete Role Policy
  x-api-slug: actiondeleterolepolicy-get
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondeleterolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Detach Role Policy
  x-api-slug: actiondetachrolepolicy-get
  description: Removes the specified managed policy from the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondetachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Role Policy
  x-api-slug: actiongetrolepolicy-get
  description: |-
    Retrieves the specified inline policy document that is embedded with the specified
          IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiongetrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - List Role Policies
  x-api-slug: actionlistrolepolicies-get
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API - Put Role Policy
  x-api-slug: actionputrolepolicy-get
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionputrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - List Attached Role Policies
  x-api-slug: actionlistattachedrolepolicies-get
  description: Lists all managed policies that are attached to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistattachedrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API - Remove Role From Instance Profile
  x-api-slug: actionremoverolefrominstanceprofile-get
  description: Removes the specified IAM role from the specified EC2 instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionremoverolefrominstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API - Add Role To Instance Profile
  x-api-slug: actionaddroletoinstanceprofile-get
  description: Adds the specified IAM role to the specified instance profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionaddroletoinstanceprofile-get-openapi.md
- name: AWS Identity and Access Management API - Attach Role Policy
  x-api-slug: actionattachrolepolicy-get
  description: Attaches the specified managed policy to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionattachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Delete Role Policy
  x-api-slug: actiondeleterolepolicy-get
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondeleterolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Detach Role Policy
  x-api-slug: actiondetachrolepolicy-get
  description: Removes the specified managed policy from the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiondetachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Role Policy
  x-api-slug: actiongetrolepolicy-get
  description: |-
    Retrieves the specified inline policy document that is embedded with the specified
          IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actiongetrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - List Role Policies
  x-api-slug: actionlistrolepolicies-get
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionlistrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API - Put Role Policy
  x-api-slug: actionputrolepolicy-get
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/aws-identity-and-access-management/actionputrolepolicy-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.glacier.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.identity.and.access.management.stack.network
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