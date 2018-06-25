---
name: CloudFlare
x-slug: cloudflare
description: Here at Cloudflare, we make the Internet work the way it should. Offering
  CDN, DNS, DDoS protection and security, find out how we can help your site.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
x-kinRank: "9"
x-alexaRank: "1685"
tags: Roles
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/cloudflare/apis.md
specificationVersion: "0.14"
apis:
- name: CloudFlare Get all available roles for an organization
  x-api-slug: cloudflare
  description: Get all available roles for an organization
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///organizations/:organization_identifier/roles
  tags: Organization Roles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/cloudflare/organizationsorganization-identifierroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/cloudflare/organizationsorganization-identifierroles-get-openapi.md
- name: CloudFlare Get information about a specific role for an organization
  x-api-slug: cloudflare
  description: Get information about a specific role for an organization
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https://///organizations/:organization_identifier/roles/:identifier
  tags: Organization Roles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/cloudflare/organizationsorganization-identifierrolesidentifier-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/cloudflare/organizationsorganization-identifierrolesidentifier-get-openapi.md
- name: CloudFlare
  x-api-slug: cloudflare
  description: Here at Cloudflare, we make the Internet work the way it should. Offering
    CDN, DNS, DDoS protection and security, find out how we can help your site.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18929-cloudflare.jpg
  humanURL: https://www.cloudflare.com
  baseURL: https:///
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/cloudflare/openapi.md
x-common:
- type: x-blog
  url: https://blog.cloudflare.com/
- type: x-blog-rss
  url: http://blog.cloudflare.com/rss/
- type: x-crunchbase
  url: https://crunchbase.com/organization/cloudflare
- type: x-developer
  url: https://www.cloudflare.com/docs/client-api.html
- type: x-github
  url: https://github.com/cloudflare
- type: x-partners
  url: https://www.cloudflare.com/partners/
- type: x-pricing
  url: https://www.cloudflare.com/plans/
- type: x-privacy
  url: https://www.cloudflare.com/security-policy
- type: x-security
  url: https://www.cloudflare.com/security-policy/
- type: x-terms-of-service
  url: https://www.cloudflare.com/terms/
- type: x-transparency-report
  url: https://www.cloudflare.com/transparency/
- type: x-twitter
  url: https://twitter.com/CloudFlare
- type: x-website
  url: https://www.cloudflare.com
- type: x-website
  url: http://cloudflare.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---