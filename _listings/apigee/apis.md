---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Roles
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Userroles
  x-api-slug: apigee-edge
  description: Gets a list of roles available to users in an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles
  tags: Organizations,Userroles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserroles-get-openapi.md
- name: Apigee Edge Post Organizations Name Userroles
  x-api-slug: apigee-edge
  description: Creates a role in an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles
  tags: Organizations,Userroles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserroles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserroles-post-openapi.md
- name: Apigee Edge Get Organizations Name Userroles Role Name
  x-api-slug: apigee-edge
  description: Gets a role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles/{role_name}
  tags: Organizations,Userroles,Role
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-name-get-openapi.md
- name: Apigee Edge Delete Organizations Name Userroles Role Name
  x-api-slug: apigee-edge
  description: Deletes a role from an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles/{role_name}
  tags: Organizations,Userroles,Role
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-name-delete-openapi.md
- name: Apigee Edge Get Userroles
  x-api-slug: apigee-edge
  description: Gets a list of roles available to users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles
  tags: Userroles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userroles-get-openapi.md
- name: Apigee Edge Post Userroles
  x-api-slug: apigee-edge
  description: Creates a role at global level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles
  tags: Userroles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userroles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userroles-post-openapi.md
- name: Apigee Edge Get Userroles Role Name
  x-api-slug: apigee-edge
  description: Gets a role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}
  tags: Userroles,Role
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-name-get-openapi.md
- name: Apigee Edge Delete Userroles Role Name
  x-api-slug: apigee-edge
  description: Deletes a role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}
  tags: Userroles,Role
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-name-delete-openapi.md
- name: Apigee Edge Get Users User Email Userroles
  x-api-slug: apigee-edge
  description: Gets roles for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///users/{user_email}/userroles
  tags: Users,User,Email,Userroles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/usersuser-emailuserroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/usersuser-emailuserroles-get-openapi.md
- name: Apigee Edge Post Users User Email Userroles
  x-api-slug: apigee-edge
  description: Associates a user with a organizational user role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///users/{user_email}/userroles
  tags: Users,User,Email,Userroles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/usersuser-emailuserroles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/usersuser-emailuserroles-post-openapi.md
- name: Apigee Edge Get Userroles Role Name Users
  x-api-slug: apigee-edge
  description: Lists users for a role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/users
  tags: Userroles,Role,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameusers-get-openapi.md
- name: Apigee Edge Post Userroles Role Name Users
  x-api-slug: apigee-edge
  description: Adds user to role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/users
  tags: Userroles,Role,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameusers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameusers-post-openapi.md
- name: Apigee Edge Get Userroles Role Name Users User Email
  x-api-slug: apigee-edge
  description: Checks user in a given system role
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/users/{user_email}
  tags: Userroles,Role,Users,User,Email
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameusersuser-email-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameusersuser-email-get-openapi.md
- name: Apigee Edge Delete Userroles Role Name Users User Email
  x-api-slug: apigee-edge
  description: Deletes user for a role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/users/{user_email}
  tags: Userroles,Role,Users,User,Email
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameusersuser-email-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameusersuser-email-delete-openapi.md
- name: Apigee Edge Delete Users User Email Userroles Role Name
  x-api-slug: apigee-edge
  description: Deletes organizational role for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///users/{user_email}/userroles/{role_name}
  tags: Users,User,Email,Userroles,Role
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/usersuser-emailuserrolesrole-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/usersuser-emailuserrolesrole-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Userroles Role Name Permissions
  x-api-slug: apigee-edge
  description: Gets a list of permissions associated with the specified resource for
    a single resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles/{role_name}/permissions
  tags: Organizations,Userroles,Role,Permissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-namepermissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-namepermissions-get-openapi.md
- name: Apigee Edge Post Organizations Name Userroles Role Name Permissions
  x-api-slug: apigee-edge
  description: Associates permissions for a resource with a user role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles/{role_name}/permissions
  tags: Organizations,Userroles,Role,Permissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-namepermissions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-namepermissions-post-openapi.md
- name: Apigee Edge Get Organizations Name Userroles Role Name Permissions Get
  x-api-slug: apigee-edge
  description: Checks the particular userrole permission of a resource at organization
    level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles/{role_name}/permissions/get
  tags: Organizations,Userroles,Role,Permissions,Get
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-namepermissionsget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-namepermissionsget-get-openapi.md
- name: Apigee Edge Delete Organizations Name Userroles Role Name Permissions Get
  x-api-slug: apigee-edge
  description: Deletes particular userrole permission at organization level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles/{role_name}/permissions/get
  tags: Organizations,Userroles,Role,Permissions,Get
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-namepermissionsget-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-namepermissionsget-delete-openapi.md
- name: Apigee Edge Post Organizations Name Userroles Role Name Resourcepermissions
  x-api-slug: apigee-edge
  description: Adds multiple resource permissions for resource at organization level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/userroles/{role_name}/resourcepermissions
  tags: Organizations,Userroles,Role,Resourcepermissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-nameresourcepermissions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/organizationsorg-nameuserrolesrole-nameresourcepermissions-post-openapi.md
- name: Apigee Edge Get Userroles Role Name Permissions
  x-api-slug: apigee-edge
  description: Gets permission for a specific resource at global level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/permissions
  tags: Userroles,Role,Permissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-namepermissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-namepermissions-get-openapi.md
- name: Apigee Edge Post Userroles Role Name Permissions
  x-api-slug: apigee-edge
  description: Adds permissions for resource at global level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/permissions
  tags: Userroles,Role,Permissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-namepermissions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-namepermissions-post-openapi.md
- name: Apigee Edge Get Userroles Role Name Permissions Get
  x-api-slug: apigee-edge
  description: Checks particular userrole permission for a resource at global level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/permissions/get
  tags: Userroles,Role,Permissions,Get
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-namepermissionsget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-namepermissionsget-get-openapi.md
- name: Apigee Edge Delete Userroles Role Name Permissions Get
  x-api-slug: apigee-edge
  description: Deletes particular userrole permission for a resource at global level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/permissions/get
  tags: Userroles,Role,Permissions,Get
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-namepermissionsget-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-namepermissionsget-delete-openapi.md
- name: Apigee Edge Post Userroles Role Name Resourcepermissions
  x-api-slug: apigee-edge
  description: Adds multiple resource permissions for resource at global level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///userroles/{role_name}/resourcepermissions
  tags: Userroles,Role,Resourcepermissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameresourcepermissions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/userrolesrole-nameresourcepermissions-post-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/roles/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---