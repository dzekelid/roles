---
name: Mattermost
x-slug: mattermost
description: Open source, private cloud Slack-alternative, Workplace messaging for
  web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
  configurable, and scalable from teams to the enterprise.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
x-kinRank: "8"
x-alexaRank: "95684"
tags: Roles
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/apis.md
specificationVersion: "0.14"
apis:
- name: Mattermost API Reference - Update a user's roles
  x-api-slug: usersuser-idroles-put
  description: |-
    Update a user's system-level roles. Valid user roles are "system_user", "system_admin" or both of them. Overwrites any previously assigned system-level roles.
    ##### Permissions
    Must have the `manage_roles` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/usersuser-idroles-put-openapi.md
- name: Mattermost API Reference - Update a team member roles
  x-api-slug: teamsteam-idmembersuser-idroles-put
  description: |-
    Update a team member roles. Valid team roles are "team_user", "team_admin" or both of them. Overwrites any previously assigned team roles.
    ##### Permissions
    Must be authenticated and have the `manage_team_roles` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/teamsteam-idmembersuser-idroles-put-openapi.md
- name: Mattermost API Reference - Update channel roles
  x-api-slug: channelschannel-idmembersuser-idroles-put
  description: |-
    Update a user's roles for a channel.
    ##### Permissions
    Must have `manage_channel_roles` permission for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/channelschannel-idmembersuser-idroles-put-openapi.md
- name: Mattermost API Reference - Get a list of roles by name
  x-api-slug: rolesnames-post
  description: |-
    Get a list of roles from their names.

    ##### Permissions
    Requires an active session but no other permissions.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesnames-post-openapi.md
- name: Mattermost API Reference - Get a role
  x-api-slug: rolesrole-id-get
  description: |-
    Get a role from the provided role id.

    ##### Permissions
    Requires an active session but no other permissions.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesrole-id-get-openapi.md
- name: Mattermost API Reference - Get a role
  x-api-slug: rolesnamerole-name-get
  description: |-
    Get a role from the provided role name.

    ##### Permissions
    Requires an active session but no other permissions.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesnamerole-name-get-openapi.md
- name: Mattermost API Reference - Patch a role
  x-api-slug: rolesrole-idpatch-put
  description: |-
    Partially update a role by providing only the fields you want to update. Omitted fields will not be updated. The fields that can be updated are defined in the request body, all other provided fields will be ignored.

    ##### Permissions
    `manage_system` permission is required.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesrole-idpatch-put-openapi.md
- name: Mattermost API Reference - Get a role
  x-api-slug: rolesrole-id-get
  description: |-
    Get a role from the provided role id.

    ##### Permissions
    Requires an active session but no other permissions.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesrole-id-get-openapi.md
- name: Mattermost API Reference - Get a role
  x-api-slug: rolesnamerole-name-get
  description: |-
    Get a role from the provided role name.

    ##### Permissions
    Requires an active session but no other permissions.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesnamerole-name-get-openapi.md
- name: Mattermost API Reference - Patch a role
  x-api-slug: rolesrole-idpatch-put
  description: |-
    Partially update a role by providing only the fields you want to update. Omitted fields will not be updated. The fields that can be updated are defined in the request body, all other provided fields will be ignored.

    ##### Permissions
    `manage_system` permission is required.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesrole-idpatch-put-openapi.md
- name: Mattermost API Reference - Patch a role
  x-api-slug: rolesrole-idpatch-put
  description: |-
    Partially update a role by providing only the fields you want to update. Omitted fields will not be updated. The fields that can be updated are defined in the request body, all other provided fields will be ignored.

    ##### Permissions
    `manage_system` permission is required.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesrole-idpatch-put-openapi.md
- name: Mattermost API Reference - Get a role
  x-api-slug: rolesnamerole-name-get
  description: |-
    Get a role from the provided role name.

    ##### Permissions
    Requires an active session but no other permissions.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesnamerole-name-get-openapi.md
- name: Mattermost API Reference - Get a role
  x-api-slug: rolesrole-id-get
  description: |-
    Get a role from the provided role id.

    ##### Permissions
    Requires an active session but no other permissions.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/mattermost/rolesrole-id-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://matrix.api.gallery.streamdata.io
- type: x-api-stack
  url: http://mattermost.stack.network
- type: x-blog
  url: https://about.mattermost.com/blog/
- type: x-blog-rss
  url: https://about.mattermost.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/mattermost
- type: x-developer
  url: https://api.mattermost.com/
- type: x-github
  url: https://github.com/mattermost
- type: x-pricing
  url: https://about.mattermost.com/pricing/
- type: x-security
  url: https://docs.mattermost.com/overview/security.html
- type: x-twitter
  url: https://twitter.com/mattermosthq
- type: x-website
  url: https://mattermost.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---