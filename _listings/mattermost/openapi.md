---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost API Reference
  description: -api-v4-is-stable-with-the-mattermost-server-40-release-api-v3-was-deprecated-on-january-16th-2018-and-scheduled-for-removal-in-mattermost-v50-details-heretagapiv3deprecation-looking-for-the-api-v3-reference-it-has-moved-herehttpsapimattermostcomv3
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
---