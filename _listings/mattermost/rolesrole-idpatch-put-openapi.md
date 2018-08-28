---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Patch a role
  description: |-
    Partially update a role by providing only the fields you want to update. Omitted fields will not be updated. The fields that can be updated are defined in the request body, all other provided fields will be ignored.

    ##### Permissions
    `manage_system` permission is required.

    __Minimum server version__: 4.9
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/roles:
    put:
      summary: Update a user's roles
      description: |-
        Update a user's system-level roles. Valid user roles are "system_user", "system_admin" or both of them. Overwrites any previously assigned system-level roles.
        ##### Permissions
        Must have the `manage_roles` permission.
      operationId: update-a-users-systemlevel-roles-valid-user-roles-are-system-user-system-admin-or-both-of-them-overw
      x-api-path-slug: usersuser-idroles-put
      parameters:
      - in: body
        name: roles
        description: Space-delimited system roles to assign to the user
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Users
      - Roles
  /teams/{team_id}/members/{user_id}/roles:
    put:
      summary: Update a team member roles
      description: |-
        Update a team member roles. Valid team roles are "team_user", "team_admin" or both of them. Overwrites any previously assigned team roles.
        ##### Permissions
        Must be authenticated and have the `manage_team_roles` permission.
      operationId: update-a-team-member-roles-valid-team-roles-are-team-user-team-admin-or-both-of-them-overwrites-any-
      x-api-path-slug: teamsteam-idmembersuser-idroles-put
      parameters:
      - in: body
        name: body
        description: Space-delimited team roles to assign to the user
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: team_id
        description: Team GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Team
      - Member
      - Roles
  /channels/{channel_id}/members/{user_id}/roles:
    put:
      summary: Update channel roles
      description: |-
        Update a user's roles for a channel.
        ##### Permissions
        Must have `manage_channel_roles` permission for the channel.
      operationId: update-a-users-roles-for-a-channel-permissionsmust-have-manage-channel-roles-permission-for-the-chan
      x-api-path-slug: channelschannel-idmembersuser-idroles-put
      parameters:
      - in: path
        name: channel_id
        description: Channel GUID
      - in: body
        name: roles
        description: Space-delimited channel roles to assign to the user
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Channel
      - Roles
  /roles/names:
    post:
      summary: Get a list of roles by name
      description: |-
        Get a list of roles from their names.

        ##### Permissions
        Requires an active session but no other permissions.

        __Minimum server version__: 4.9
      operationId: get-a-list-of-roles-from-their-names-permissionsrequires-an-active-session-but-no-other-permissions-
      x-api-path-slug: rolesnames-post
      parameters:
      - in: body
        name: body
        description: List of role names
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Roles
      - By
      - Name
  /roles/{role_id}:
    get:
      summary: Get a role
      description: |-
        Get a role from the provided role id.

        ##### Permissions
        Requires an active session but no other permissions.

        __Minimum server version__: 4.9
      operationId: get-a-role-from-the-provided-role-id-permissionsrequires-an-active-session-but-no-other-permissions-
      x-api-path-slug: rolesrole-id-get
      parameters:
      - in: path
        name: role_id
        description: Role GUID
      responses:
        200:
          description: OK
      tags:
      - Role
  /roles/name/{role_name}:
    get:
      summary: Get a role
      description: |-
        Get a role from the provided role name.

        ##### Permissions
        Requires an active session but no other permissions.

        __Minimum server version__: 4.9
      operationId: get-a-role-from-the-provided-role-name-permissionsrequires-an-active-session-but-no-other-permission
      x-api-path-slug: rolesnamerole-name-get
      parameters:
      - in: path
        name: role_name
        description: Role Name
      responses:
        200:
          description: OK
      tags:
      - Role
  /roles/{role_id}/patch:
    put:
      summary: Patch a role
      description: |-
        Partially update a role by providing only the fields you want to update. Omitted fields will not be updated. The fields that can be updated are defined in the request body, all other provided fields will be ignored.

        ##### Permissions
        `manage_system` permission is required.

        __Minimum server version__: 4.9
      operationId: partially-update-a-role-by-providing-only-the-fields-you-want-to-update-omitted-fields-will-not-be-u
      x-api-path-slug: rolesrole-idpatch-put
      parameters:
      - in: body
        name: body
        description: Role object to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: role_id
        description: Role GUID
      responses:
        200:
          description: OK
      tags:
      - Role
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