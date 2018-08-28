---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API List Role Policies
  version: 1.0.0
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          role.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateRole:
    get:
      summary: Create Role
      description: Creates a new role for your AWS account.
      operationId: createRole
      x-api-path-slug: actioncreaterole-get
      parameters:
      - in: query
        name: AssumeRolePolicyDocument
        description: The trust relationship policy document that grants an entity
          permission to assume the      role
        type: string
      - in: query
        name: Path
        description: The path to the role
        type: string
      - in: query
        name: RoleName
        description: The name of the role to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
  /?Action=DeleteRole:
    get:
      summary: Delete Role
      description: Deletes the specified role.
      operationId: deleteRole
      x-api-path-slug: actiondeleterole-get
      parameters:
      - in: query
        name: RoleName
        description: The name of the role to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
  /?Action=GetRole:
    get:
      summary: Get Role
      description: |-
        Retrieves information about the specified role, including the role's path, GUID, ARN,
              and the role's trust policy that grants permission to assume the role.
      operationId: getRole
      x-api-path-slug: actiongetrole-get
      parameters:
      - in: query
        name: RoleName
        description: The name of the IAM role to get information about
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
  /?Action=ListRoles:
    get:
      summary: List Roles
      description: Lists the IAM roles that have the specified path prefix.
      operationId: listRoles
      x-api-path-slug: actionlistroles-get
      parameters:
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only after     you
          receive a response indicating that the results are truncated
        type: string
      - in: query
        name: MaxItems
        description: (Optional) Use this only when paginating results to indicate
          the     maximum number of items you want in the response
        type: string
      - in: query
        name: PathPrefix
        description: The path prefix for filtering the results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
  /?Action=RemoveRoleFromInstanceProfile:
    get:
      summary: Remove Role From Instance Profile
      description: Removes the specified IAM role from the specified EC2 instance
        profile.
      operationId: removeRoleFromInstanceProfile
      x-api-path-slug: actionremoverolefrominstanceprofile-get
      parameters:
      - in: query
        name: InstanceProfileName
        description: The name of the instance profile to update
        type: string
      - in: query
        name: RoleName
        description: The name of the role to remove
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role From Instance Profiles
  /?Action=AddRoleToInstanceProfile:
    get:
      summary: Add Role To Instance Profile
      description: Adds the specified IAM role to the specified instance profile.
      operationId: addRoleToInstanceProfile
      x-api-path-slug: actionaddroletoinstanceprofile-get
      parameters:
      - in: query
        name: InstanceProfileName
        description: The name of the instance profile to update
        type: string
      - in: query
        name: RoleName
        description: The name of the role to add
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Instance
  /?Action=AttachRolePolicy:
    get:
      summary: Attach Role Policy
      description: Attaches the specified managed policy to the specified IAM role.
      operationId: attachRolePolicy
      x-api-path-slug: actionattachrolepolicy-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          attach
        type: string
      - in: query
        name: RoleName
        description: The name (friendly name, not ARN) of the role to attach the policy
          to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=DeleteRolePolicy:
    get:
      summary: Delete Role Policy
      description: |-
        Deletes the specified inline policy that is embedded in the specified IAM
              role.
      operationId: deleteRolePolicy
      x-api-path-slug: actiondeleterolepolicy-get
      parameters:
      - in: query
        name: PolicyName
        description: The name of the inline policy to delete from the specified IAM
          role
        type: string
      - in: query
        name: RoleName
        description: The name (friendly name, not ARN) identifying the role that the
          policy is embedded      in
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=DetachRolePolicy:
    get:
      summary: Detach Role Policy
      description: Removes the specified managed policy from the specified role.
      operationId: detachRolePolicy
      x-api-path-slug: actiondetachrolepolicy-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          detach
        type: string
      - in: query
        name: RoleName
        description: The name (friendly name, not ARN) of the IAM role to detach the
          policy      from
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=GetRolePolicy:
    get:
      summary: Get Role Policy
      description: |-
        Retrieves the specified inline policy document that is embedded with the specified
              IAM role.
      operationId: getRolePolicy
      x-api-path-slug: actiongetrolepolicy-get
      parameters:
      - in: query
        name: PolicyName
        description: The name of the policy document to get
        type: string
      - in: query
        name: RoleName
        description: The name of the role associated with the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=ListRolePolicies:
    get:
      summary: List Role Policies
      description: |-
        Lists the names of the inline policies that are embedded in the specified IAM
              role.
      operationId: listRolePolicies
      x-api-path-slug: actionlistrolepolicies-get
      parameters:
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only after     you
          receive a response indicating that the results are truncated
        type: string
      - in: query
        name: MaxItems
        description: (Optional) Use this only when paginating results to indicate
          the     maximum number of items you want in the response
        type: string
      - in: query
        name: RoleName
        description: The name of the role to list policies for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=PutRolePolicy:
    get:
      summary: Put Role Policy
      description: |-
        Adds or updates an inline policy document that is embedded in the specified IAM
              role.
      operationId: putRolePolicy
      x-api-path-slug: actionputrolepolicy-get
      parameters:
      - in: query
        name: PolicyDocument
        description: The policy document
        type: string
      - in: query
        name: PolicyName
        description: The name of the policy document
        type: string
      - in: query
        name: RoleName
        description: The name of the role to associate the policy with
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=ListAttachedRolePolicies:
    get:
      summary: List Attached Role Policies
      description: Lists all managed policies that are attached to the specified IAM
        role.
      operationId: listAttachedRolePolicies
      x-api-path-slug: actionlistattachedrolepolicies-get
      parameters:
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only after     you
          receive a response indicating that the results are truncated
        type: string
      - in: query
        name: MaxItems
        description: (Optional) Use this only when paginating results to indicate
          the     maximum number of items you want in the response
        type: string
      - in: query
        name: PathPrefix
        description: The path prefix for filtering the results
        type: string
      - in: query
        name: RoleName
        description: The name (friendly name, not ARN) of the role to list attached
          policies for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attached Role Policies
  /?Action=ListInstanceProfilesForRole:
    get:
      summary: List Instance Profiles For Role
      description: Lists the instance profiles that have the specified associated
        IAM role.
      operationId: listInstanceProfilesForRole
      x-api-path-slug: actionlistinstanceprofilesforrole-get
      parameters:
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only after     you
          receive a response indicating that the results are truncated
        type: string
      - in: query
        name: MaxItems
        description: (Optional) Use this only when paginating results to indicate
          the     maximum number of items you want in the response
        type: string
      - in: query
        name: RoleName
        description: The name of the role to list instance profiles for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Profiles For Role
  /?Action=UpdateAssumeRolePolicy:
    get:
      summary: Update Assume Role Policy
      description: Updates the policy that grants an IAM entity permission to assume
        a role.
      operationId: updateAssumeRolePolicy
      x-api-path-slug: actionupdateassumerolepolicy-get
      parameters:
      - in: query
        name: PolicyDocument
        description: The policy that grants an entity permission to assume the role
        type: string
      - in: query
        name: RoleName
        description: The name of the role to update with the new policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assume Role Policy
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