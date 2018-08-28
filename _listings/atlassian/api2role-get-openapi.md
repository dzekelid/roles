---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get all project roles
  description: |-
    Gets a list of all project roles, complete with project role details and default actors.

    ### About project roles

    [Project roles](https://confluence.atlassian.com/x/3odKLg) are a flexible way to to associate users and groups with projects. In Jira Cloud, the list of project roles is shared globally with all projects, but each project can have a different set of actors associated with it (unlike groups, which have the same membership throughout all Jira applications).

    Project roles can be used in [permission schemes](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-permissionscheme-get), [email notification schemes](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-notificationscheme-get), [issue security levels](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuesecurityschemes-get), [comment visibility](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-comment-list-post), and workflow conditions.

    #### Members and actors

    In the Jira REST API, a member of a project role is called an _actor_. An _actor_ is a group or user associated with a project role.

    Actors may be set as [default members](https://confluence.atlassian.com/x/3odKLg#Managingprojectroles-Specifying'defaultmembers'foraprojectrole) of the project role or set at the project level:

    *   Default actors: Users and groups that are assigned to the project role for all newly created projects. The default actors can be removed at the project level later if desired.
    *   Actors: Users and groups that are associated with a project role for a particular project, which may differ from the default actors. This allows you to assign a particular user to different roles in different projects.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/applicationrole:
    get:
      summary: Get all application roles
      description: Returns all ApplicationRoles in the system. Will also return an
        ETag header containing a version hash of the collection of ApplicationRoles.
      operationId: com.atlassian.jira.rest.v2.admin.applicationrole.ApplicationRoleResource.getAllApplicationRoles_get
      x-api-path-slug: api2applicationrole-get
      responses:
        200:
          description: OK
      tags:
      - Application
      - Roles
  /api/2/role:
    get:
      summary: Get all project roles
      description: |-
        Gets a list of all project roles, complete with project role details and default actors.

        ### About project roles

        [Project roles](https://confluence.atlassian.com/x/3odKLg) are a flexible way to to associate users and groups with projects. In Jira Cloud, the list of project roles is shared globally with all projects, but each project can have a different set of actors associated with it (unlike groups, which have the same membership throughout all Jira applications).

        Project roles can be used in [permission schemes](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-permissionscheme-get), [email notification schemes](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-notificationscheme-get), [issue security levels](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuesecurityschemes-get), [comment visibility](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-comment-list-post), and workflow conditions.

        #### Members and actors

        In the Jira REST API, a member of a project role is called an _actor_. An _actor_ is a group or user associated with a project role.

        Actors may be set as [default members](https://confluence.atlassian.com/x/3odKLg#Managingprojectroles-Specifying'defaultmembers'foraprojectrole) of the project role or set at the project level:

        *   Default actors: Users and groups that are assigned to the project role for all newly created projects. The default actors can be removed at the project level later if desired.
        *   Actors: Users and groups that are associated with a project role for a particular project, which may differ from the default actors. This allows you to assign a particular user to different roles in different projects.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.RoleResource.getAllProjectRoles_get
      x-api-path-slug: api2role-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Roles
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