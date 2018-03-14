---
name: AWS Security Token Service
description: The AWS Security Token Service (STS) is a web service that enables you
  to request temporary, limited-privilege credentials for AWS Identity and Access
  Management (IAM) users or for users that you authenticate (federated users).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Security
- Authentication
- Amazon Web Services
created: "2018-03-14"
modified: "2018-03-14"
url: https://raw.githubusercontent.com/streamdata-gallery/roles/master/_listings/aws-security-token-service/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS Security Token Service API
  description: The AWS Security Token Service (STS) is a web service that enables
    you to request temporary, limited-privilege credentials for AWS Identity and Access
    Management (IAM) users or for users that you authenticate (federated users)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: ""
  baseURL: :///
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery/roles/master/_listings/aws-security-token-service/action-assumerolewithsaml-get.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/STS/latest/APIReference/
- type: x-errors
  url: http://docs.aws.amazon.com/STS/latest/APIReference/CommonErrors.html
- type: x-website
  url: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---