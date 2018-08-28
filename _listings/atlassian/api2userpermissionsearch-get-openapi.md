---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Find users with permissions
  description: |-
    Returns a list of users who fulfill both of these criteria:

    *   their user attributes match a search string.
    *   they have a set of permissions for a project or issue.

    If no search string is provided, a list of all users with the permissions is returned. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   Get users for any project, _Administer Jira_ [global permission](href=).
    *   Get users for a project, _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
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
  /api/2/permissions/project:
    post:
      summary: Get permitted projects
      description: Returns all projects where currently logged in user was granted
        ALL requested project permissions.
      operationId: com.atlassian.jira.rest.v2.permission.PermissionsResource.getPermittedProjects_post
      x-api-path-slug: api2permissionsproject-post
      responses:
        200:
          description: OK
      tags:
      - Permitted
      - Projects
  /api/2/project:
    get:
      summary: Get all projects
      description: |-
        Returns all projects visible to the currently logged in user. For projects to be visible, the authenticated user must be granted either _Browse projects_ or _Administer projects_ permissions. If no user is logged in, it returns all projects that are visible for anonymous users.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.getAllProjects_get
      x-api-path-slug: api2project-get
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      - in: query
        name: recent
        description: Returns the most recently accessed projects for the current user
      responses:
        200:
          description: OK
      tags:
      - Projects
    post:
      summary: Create project
      description: |-
        Creates a new project.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.createProject_post
      x-api-path-slug: api2project-post
      parameters:
      - in: header
        name: force-account-id
      responses:
        200:
          description: OK
      tags:
      - Project
  /api/2/user/assignable/multiProjectSearch:
    get:
      summary: Find users assignable to projects
      description: |-
        Returns a list of users who fulfill both of these criteria:

        *   their user attributes match a string.
        *   they can be assigned issues in one or more projects.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None.
      operationId: com.atlassian.jira.rest.v2.issue.UserResource.findBulkAssignableUsers_get
      x-api-path-slug: api2userassignablemultiprojectsearch-get
      parameters:
      - in: header
        name: force-account-id
      - in: query
        name: maxResults
        description: The maximum number of items to return per page
      - in: query
        name: projectKeys
        description: A comma-separated list of project keys (case sensitive)
      - in: query
        name: query
        description: A search input that is matched against appropriate user attributes
          to find relevant users
      - in: query
        name: startAt
        description: The index of the first item to return in a page of results (page
          offset)
      - in: query
        name: username
        description: The search string
      responses:
        200:
          description: OK
      tags:
      - Find
      - Users
      - Assignable
      - To
      - Projects
  /api/2/project/type:
    get:
      summary: Get all project types
      description: |-
        Returns all [project types](https://confluence.atlassian.com/x/Var1Nw), whether or not the instance has a valid license for each type.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
      operationId: com.atlassian.jira.rest.v2.project.type.ProjectTypeResource.getAllProjectTypes_get
      x-api-path-slug: api2projecttype-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Types
  /api/2/project/type/{projectTypeKey}:
    get:
      summary: Get project type by key
      description: |-
        Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
      operationId: com.atlassian.jira.rest.v2.project.type.ProjectTypeResource.getProjectTypeByKey_get
      x-api-path-slug: api2projecttypeprojecttypekey-get
      parameters:
      - in: path
        name: projectTypeKey
        description: The key of the project type
      responses:
        200:
          description: OK
      tags:
      - Project
      - Type
      - By
      - Key
  /api/2/project/type/{projectTypeKey}/accessible:
    get:
      summary: Get accessible project type by key
      description: |-
        Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
      operationId: com.atlassian.jira.rest.v2.project.type.ProjectTypeResource.getAccessibleProjectTypeByKey_get
      x-api-path-slug: api2projecttypeprojecttypekeyaccessible-get
      parameters:
      - in: path
        name: projectTypeKey
        description: The key of the project type
      responses:
        200:
          description: OK
      tags:
      - Accessible
      - Project
      - Type
      - By
      - Key
  /api/2/project/{projectIdOrKey}:
    get:
      summary: Get project
      description: |-
        Returns the [project details](https://confluence.atlassian.com/x/ahLpNw) for the specified project.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.getProject_get
      x-api-path-slug: api2projectprojectidorkey-get
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
    put:
      summary: Update project
      description: |-
        Updates the [project details](https://confluence.atlassian.com/x/ahLpNw) of an existing project.

        All parameters are optional in the body of the request.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.updateProject_put
      x-api-path-slug: api2projectprojectidorkey-put
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      - in: header
        name: force-account-id
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
    delete:
      summary: Delete project
      description: |-
        Deletes an existing project.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.deleteProject_delete
      x-api-path-slug: api2projectprojectidorkey-delete
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
  /api/2/project/{projectIdOrKey}/avatar:
    put:
      summary: Update project avatar
      description: ""
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.updateProjectAvatar_put
      x-api-path-slug: api2projectprojectidorkeyavatar-put
      parameters:
      - in: path
        name: projectIdOrKey
      responses:
        200:
          description: OK
      tags:
      - Project
      - Avatar
  /api/2/project/{projectIdOrKey}/avatar/{id}:
    delete:
      summary: Delete project avatar
      description: Deletes an avatar of a single project. It is only possible to delete
        custom avatars.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.deleteProjectAvatar_delete
      x-api-path-slug: api2projectprojectidorkeyavatarid-delete
      parameters:
      - in: path
        name: id
        description: ID of the avatar
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Avatar
  /api/2/project/{projectIdOrKey}/avatar2:
    post:
      summary: Create project avatar
      description: Creates an avatar for a single project. Use it to upload an image
        to be be set as a project's avatar. The uploaded image will be cropped according
        to the crop parameters defined in the request. If no crop parameters are specified,
        the image will be cropped to a square. The square will originate at the top
        left of the image and the length of each side will be set to the smaller of
        the height or width of the image.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.createProjectAvatar_post
      x-api-path-slug: api2projectprojectidorkeyavatar2-post
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      - in: query
        name: size
        description: (optional) Length of each side of the crop region
      - in: query
        name: x
        description: (optional) X coordinate of the top-left corner of the crop region
      - in: query
        name: "y"
        description: (optional) Y coordinate of the top-left corner of the crop region
      responses:
        200:
          description: OK
      tags:
      - Project
      - Avatar
  /api/2/project/{projectIdOrKey}/avatars:
    get:
      summary: Get all project avatars
      description: Returns all project avatars visible for the currently logged in
        user. The avatars are grouped into system avatars and custom avatars.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.getAllProjectAvatars_get
      x-api-path-slug: api2projectprojectidorkeyavatars-get
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Avatars
  /api/2/project/{projectIdOrKey}/component:
    get:
      summary: Get project components paginated
      description: |-
        Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all components existing in a single project. See the [Get project components](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-components-get) resource if you want to get a full list of versions without pagination.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.getProjectComponentsPaginated_get
      x-api-path-slug: api2projectprojectidorkeycomponent-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of components to return per page
      - in: query
        name: orderBy
        description: '[Order](https://developer'
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      - in: query
        name: query
        description: Filter the results using a literal string
      - in: query
        name: startAt
        description: The starting index of the returned list of components
      responses:
        200:
          description: OK
      tags:
      - Project
      - Components
      - Paginated
  /api/2/project/{projectIdOrKey}/components:
    get:
      summary: Get project components
      description: |-
        Returns all components existing in a single project. See the [Get project components paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-component-get) resource if you want to get a full list of components with pagination.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.getProjectComponents_get
      x-api-path-slug: api2projectprojectidorkeycomponents-get
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Components
  /api/2/project/{projectIdOrKey}/properties:
    get:
      summary: Get project property keys
      description: |-
        Returns all [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys for the project.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.ProjectPropertyResource.getProjectPropertyKeys_get
      x-api-path-slug: api2projectprojectidorkeyproperties-get
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Property
      - Keys
  /api/2/project/{projectIdOrKey}/properties/{propertyKey}:
    get:
      summary: Get project property
      description: |-
        Returns the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.ProjectPropertyResource.getProjectProperty_get
      x-api-path-slug: api2projectprojectidorkeypropertiespropertykey-get
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      - in: path
        name: propertyKey
        description: The project property key
      responses:
        200:
          description: OK
      tags:
      - Project
      - Property
    put:
      summary: Set project property
      description: |-
        Sets the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). You can use project properties to store custom data against the project.

        The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 bytes.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.ProjectPropertyResource.setProjectProperty_put
      x-api-path-slug: api2projectprojectidorkeypropertiespropertykey-put
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      - in: path
        name: propertyKey
        description: The key of the project property
      responses:
        200:
          description: OK
      tags:
      - Set
      - Project
      - Property
    delete:
      summary: Delete project property
      description: |-
        Removes the [property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) from the project.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.ProjectPropertyResource.deleteProjectProperty_delete
      x-api-path-slug: api2projectprojectidorkeypropertiespropertykey-delete
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      - in: path
        name: propertyKey
        description: The project property key
      responses:
        200:
          description: OK
      tags:
      - Project
      - Property
  /api/2/project/{projectIdOrKey}/role:
    get:
      summary: Get project roles for project
      description: |-
        Returns a list of [project roles](https://confluence.atlassian.com/x/3odKLg) for the project.

        Note that all project roles are shared with all projects in Jira Cloud. See the [Get all project roles](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-get) resource for more information.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.ProjectRoleResource.getProjectRoles_get
      x-api-path-slug: api2projectprojectidorkeyrole-get
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Rolesproject
  /api/2/project/{projectIdOrKey}/role/{id}:
    get:
      summary: Get project role for project
      description: |-
        Returns the project role's details and actors associated with the project. The list of actors is sorted by display name.

        If you would like to check to see whether a user belongs to a role based on their group memberships, use the [Get user](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-user-get) resource with the `groups` expand parameter selected. Then check whether the user keys and groups match with the actors returned for the project.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.ProjectRoleResource.getProjectRole_get
      x-api-path-slug: api2projectprojectidorkeyroleid-get
      parameters:
      - in: path
        name: id
        description: The ID of the project role
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Roleproject
    post:
      summary: Add actors to project role
      description: |-
        Adds additional actors to a project role for the project.

        If you want to replace all actors for the project, then use [Set actors for project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-put).

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.ProjectRoleResource.addActorUsers_post
      x-api-path-slug: api2projectprojectidorkeyroleid-post
      parameters:
      - in: header
        name: force-account-id
      - in: path
        name: id
        description: The ID of the project role
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Actors
      - To
      - Project
      - Role
    delete:
      summary: Delete actors from project role
      description: |-
        Deletes actors from a project role for the project.

        If you want to remove default actors from the project role, see the [Delete default actors from project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-delete) resource.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.ProjectRoleResource.deleteActor_delete
      x-api-path-slug: api2projectprojectidorkeyroleid-delete
      parameters:
      - in: header
        name: force-account-id
      - in: query
        name: group
        description: The name of the group to remove from the project role
      - in: path
        name: id
        description: The ID of the project role
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      - in: query
        name: user
        description: The user account ID of the user to remove from the project role
      responses:
        200:
          description: OK
      tags:
      - Actors
      - From
      - Project
      - Role
    put:
      summary: Set actors for project role
      description: |-
        Associates actors with the project role for the project, replacing all existing actors.

        If you want to add actors to the project without overwriting the existing list, then use [Add actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-post).

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.ProjectRoleResource.setActors_put
      x-api-path-slug: api2projectprojectidorkeyroleid-put
      parameters:
      - in: header
        name: force-account-id
      - in: path
        name: id
        description: The ID of the project role
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Set
      - Actorsproject
      - Role
  /api/2/project/{projectIdOrKey}/roledetails:
    get:
      summary: Get project role details
      description: Returns all [project roles](https://confluence.atlassian.com/x/3odKLg)
        and the details for each role. Note that the list of project roles is common
        to all projects.
      operationId: com.atlassian.jira.rest.v2.issue.project.ProjectRoleDetailsResource.getProjectRoleDetails_get
      x-api-path-slug: api2projectprojectidorkeyroledetails-get
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Role
      - Details
  /api/2/project/{projectIdOrKey}/type/{newProjectTypeKey}:
    put:
      summary: Update project type
      description: |-
        Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.updateProjectType_put
      x-api-path-slug: api2projectprojectidorkeytypenewprojecttypekey-put
      parameters:
      - in: path
        name: newProjectTypeKey
        description: The key of the new project type
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Type
  /api/2/project/{projectIdOrKey}/version:
    get:
      summary: Get project versions paginated
      description: |-
        Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all versions existing in a single project. See the [Get project versions](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-versions-get) resource if you want to get a full list of versions without pagination.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.getProjectVersionsPaginated_get
      x-api-path-slug: api2projectprojectidorkeyversion-get
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      - in: query
        name: maxResults
        description: The maximum number of versions to return per page
      - in: query
        name: orderBy
        description: '[Order](https://developer'
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      - in: query
        name: query
        description: Filter the results using a literal string
      - in: query
        name: startAt
        description: The starting index of the returned list of versions (page offset)
      - in: query
        name: status
        description: A comma separated string used to filter the results by version
          status
      responses:
        200:
          description: OK
      tags:
      - Project
      - Versions
      - Paginated
  /api/2/project/{projectIdOrKey}/versions:
    get:
      summary: Get project versions
      description: |-
        Returns all versions existing in a single project. The response is not paginated. Use [Get project versions paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-version-get) if you want to get the versions in a project with pagination.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.getProjectVersions_get
      x-api-path-slug: api2projectprojectidorkeyversions-get
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Versions
  /api/2/project/{projectKeyOrId}/issuesecuritylevelscheme:
    get:
      summary: Get project issue security scheme
      description: |-
        Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or the _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.ProjectIssueSecurityLevelSchemeResource.getIssueSecurityScheme_get
      x-api-path-slug: api2projectprojectkeyoridissuesecuritylevelscheme-get
      parameters:
      - in: path
        name: projectKeyOrId
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Issue
      - Security
      - Scheme
  /api/2/project/{projectKeyOrId}/notificationscheme:
    get:
      summary: Get project notification scheme
      description: |-
        Gets a [notification scheme](https://confluence.atlassian.com/x/8YdKLg) associated with the project. See the [Get notification scheme](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-notificationscheme-id-get) resource for more information about notification schemes.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.notification.ProjectNotificationSchemeResource.getNotificationScheme_get
      x-api-path-slug: api2projectprojectkeyoridnotificationscheme-get
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      - in: path
        name: projectKeyOrId
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Notification
      - Scheme
  /api/2/project/{projectKeyOrId}/securitylevel:
    get:
      summary: Get project issue security levels
      description: |-
        Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.securitylevel.ProjectSecurityLevelResource.getSecurityLevelsForProject_ge
      x-api-path-slug: api2projectprojectkeyoridsecuritylevel-get
      parameters:
      - in: path
        name: projectKeyOrId
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Project
      - Issue
      - Security
      - Levels
  /api/2/projectCategory:
    get:
      summary: Get all project categories
      description: Returns all project categories
      operationId: com.atlassian.jira.rest.v2.issue.ProjectCategoryResource.getAllProjectCategories_get
      x-api-path-slug: api2projectcategory-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Categories
    post:
      summary: Create project category
      description: Create a project category via POST.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectCategoryResource.createProjectCategory_post
      x-api-path-slug: api2projectcategory-post
      responses:
        200:
          description: OK
      tags:
      - Project
      - Category
  /api/2/projectCategory/{id}:
    get:
      summary: Get project category by id
      description: Contains a representation of a project category in JSON format.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectCategoryResource.getProjectCategoryById_get
      x-api-path-slug: api2projectcategoryid-get
      parameters:
      - in: path
        name: id
        description: project category id
      responses:
        200:
          description: OK
      tags:
      - Project
      - Category
      - By
      - Id
    put:
      summary: Update project category
      description: Modify a project category via PUT. Any fields present in the PUT
        will override existing values. As a convenience, if a field is not present,
        it is silently ignored.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectCategoryResource.updateProjectCategory_put
      x-api-path-slug: api2projectcategoryid-put
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Project
      - Category
    delete:
      summary: Remove project category
      description: Delete a project category.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectCategoryResource.removeProjectCategory_delete
      x-api-path-slug: api2projectcategoryid-delete
      parameters:
      - in: path
        name: id
        description: Id of the project category to delete
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Project
      - Category
  /api/2/projectvalidate/key:
    get:
      summary: Validate project key
      description: Validates a project key.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectValidateResource.validateProjectKey_get
      x-api-path-slug: api2projectvalidatekey-get
      parameters:
      - in: query
        name: key
        description: the project key
      responses:
        200:
          description: OK
      tags:
      - Validate
      - Project
      - Key
  /api/2/projectvalidate/validProjectKey:
    get:
      summary: Get valid project key
      description: Validates the project key and generated a valid project key if
        the supplied key is invalid.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectValidateResource.getValidProjectKey_get
      x-api-path-slug: api2projectvalidatevalidprojectkey-get
      parameters:
      - in: query
        name: key
        description: the project key
      responses:
        200:
          description: OK
      tags:
      - Valid
      - Project
      - Key
  /api/2/projectvalidate/validProjectName:
    get:
      summary: Get valid project name
      description: Validates a project name. If the name is invalid, an attempt is
        made to produce a valid name based on the supplied one. If no such valid name
        can be found, an empty string is returned.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectValidateResource.getValidProjectName_get
      x-api-path-slug: api2projectvalidatevalidprojectname-get
      parameters:
      - in: query
        name: name
        description: the project name
      responses:
        200:
          description: OK
      tags:
      - Valid
      - Project
      - Name
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
    post:
      summary: Create project role
      description: |-
        Creates a new project role with no [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get). You can use the [Add default actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-post) the project method to add default actors to the project role after creating it.

        _Note that although a new project role is available to all projects upon creation, any default actors that are associated with the project role are not added to projects that existed prior to the role being created._<

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.RoleResource.createProjectRole_post
      x-api-path-slug: api2role-post
      responses:
        200:
          description: OK
      tags:
      - Project
      - Role
  /api/2/role/{id}:
    get:
      summary: Get project role by ID
      description: |-
        Gets the project role details and the default actors associated with the role. The list of default actors is sorted by display name.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.RoleResource.getProjectRoleById_get
      x-api-path-slug: api2roleid-get
      parameters:
      - in: path
        name: id
        description: The ID of the project role
      responses:
        200:
          description: OK
      tags:
      - Project
      - Role
      - By
      - ID
    post:
      summary: Partial update project role
      description: |-
        Update either the project role's name or its description.

        You cannot update both the name and description at the same time using this method. If you send a request with both a name and a description, then only the name will be updated, regardless of the order of appearance in the body of the request.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.RoleResource.partialUpdateProjectRole_post
      x-api-path-slug: api2roleid-post
      parameters:
      - in: path
        name: id
        description: The ID of the project role
      responses:
        200:
          description: OK
      tags:
      - Partial
      - Update
      - Project
      - Role
    put:
      summary: Fully update project role
      description: |-
        Update the project role's name and description. You must include both a name and a description in the request.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.RoleResource.fullyUpdateProjectRole_put
      x-api-path-slug: api2roleid-put
      parameters:
      - in: path
        name: id
        description: The ID of the project role
      responses:
        200:
          description: OK
      tags:
      - Fully
      - Update
      - Project
      - Role
    delete:
      summary: Delete project role
      description: |-
        Deletes a project role. You must specify a replacement project role if you wish to delete a project role that is in use.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.RoleResource.deleteProjectRole_delete
      x-api-path-slug: api2roleid-delete
      parameters:
      - in: path
        name: id
        description: The ID of the project role to delete
      - in: query
        name: swap
        description: The ID of the project role that will replace the one being deleted
      responses:
        200:
          description: OK
      tags:
      - Project
      - Role
  /api/2/role/{id}/actors:
    post:
      summary: Add default actors to project role
      description: |-
        Adds [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) to the given role. You may add either groups or users, but you cannot add groups and users in the same request.

        Changing a project role's default actors does not affect project role members for projects already created.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.RoleResource.addProjectRoleActorsToRole_post
      x-api-path-slug: api2roleidactors-post
      parameters:
      - in: header
        name: force-account-id
      - in: path
        name: id
        description: The ID of the project role
      responses:
        200:
          description: OK
      tags:
      - Default
      - Actors
      - To
      - Project
      - Role
    delete:
      summary: Delete default actors from project role
      description: |-
        Removes [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) from the project role. You may remove either a group or user, but you cannot remove a group and a user in the same request.

        Changing a project role's default actors does not affect project role members for projects already created.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
      operationId: com.atlassian.jira.rest.v2.issue.project.RoleResource.deleteProjectRoleActorsFromRole_delete
      x-api-path-slug: api2roleidactors-delete
      parameters:
      - in: header
        name: force-account-id
      - in: query
        name: group
        description: The group name of the group to be removed as a default actor
      - in: path
        name: id
        description: The ID of the project role
      - in: query
        name: user
        description: The user account ID of the user to remove as a default actor
      responses:
        200:
          description: OK
      tags:
      - Default
      - Actors
      - From
      - Project
      - Role
  /api/2/issue/createmeta:
    get:
      summary: Get create issue meta
      description: |-
        Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

        The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

        Fields will only be returned if `expand=projects.issuetypes.fields` is set.

        The results can be filtered by project and/or issue type, controlled by the query parameters.
      operationId: com.atlassian.jira.rest.v2.issue.IssueResource.getCreateIssueMeta_get
      x-api-path-slug: api2issuecreatemeta-get
      parameters:
      - in: query
        name: issuetypeIds
        description: Multi-value parameter defining issue type IDs to be used for
          the results filtering
      - in: query
        name: issuetypeNames
        description: Multi-value parameter defining issue type names to be used for
          the results filtering
      - in: query
        name: projectIds
        description: Multi-value parameter defining project IDs to be used for the
          results filtering
      - in: query
        name: projectKeys
        description: Multi-value parameter defining project keys to be used for the
          results filtering
      responses:
        200:
          description: OK
      tags:
      - Create
      - Issue
      - Meta
  /api/2/project/{projectIdOrKey}/statuses:
    get:
      summary: Get all statuses
      description: |-
        Returns the valid statuses for a project. The statuses are grouped by issue type, as each project has a set of valid issue types and each issue type has a set of valid statuses.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.getAllStatuses_get
      x-api-path-slug: api2projectprojectidorkeystatuses-get
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      responses:
        200:
          description: OK
      tags:
      - Statuses
  /api/2/user/permission/search:
    get:
      summary: Find users with permissions
      description: |-
        Returns a list of users who fulfill both of these criteria:

        *   their user attributes match a search string.
        *   they have a set of permissions for a project or issue.

        If no search string is provided, a list of all users with the permissions is returned. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

        *   Get users for any project, _Administer Jira_ [global permission](href=).
        *   Get users for a project, _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
      operationId: com.atlassian.jira.rest.v2.issue.UserResource.findUsersWithAllPermissions_get
      x-api-path-slug: api2userpermissionsearch-get
      parameters:
      - in: header
        name: force-account-id
      - in: query
        name: issueKey
        description: The issue key for the issue
      - in: query
        name: maxResults
        description: The maximum number of items to return per page
      - in: query
        name: permissions
        description: A comma-separated list of permissions
      - in: query
        name: projectKey
        description: The project key for the project (case sensitive)
      - in: query
        name: query
        description: A search input that is matched against appropriate user attributes
          to find relevant users
      - in: query
        name: startAt
        description: The index of the first item to return in a page of results (page
          offset)
      - in: query
        name: username
        description: The search string
      responses:
        200:
          description: OK
      tags:
      - Find
      - Users
      - Permissions
  /api/2/version:
    post:
      summary: Create version
      description: Creates a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
        or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.createVersion_post
      x-api-path-slug: api2version-post
      responses:
        200:
          description: OK
      tags:
      - Version
  /api/2/version/{id}:
    put:
      summary: Update version
      description: Modifies a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
        or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.updateVersion_put
      x-api-path-slug: api2versionid-put
      parameters:
      - in: path
        name: id
        description: The ID of the version
      responses:
        200:
          description: OK
      tags:
      - Version
    delete:
      summary: Delete version
      description: Deletes a project version. Deprecated, use [Delete and replace
        version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
        that supports swapping version values in custom fields, in addition to the
        swapping for `fixVersion` and `affectedVersion` provided in this resource.
        Alternative versions can be provided to update issues that use the deleted
        version in `fixVersion` or `affectedVersion`. If alternatives are not provided,
        occurrences of `fixVersion` and `affectedVersion` that contain the deleted
        version are cleared. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
        or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.deleteVersion_delete
      x-api-path-slug: api2versionid-delete
      parameters:
      - in: path
        name: id
        description: The ID of the version
      - in: query
        name: moveAffectedIssuesTo
        description: The ID of the version to update `affectedVersion` to when the
          field contains the deleted version
      - in: query
        name: moveFixIssuesTo
        description: The ID of the version to update `fixVersion` to when the field
          contains the deleted version
      responses:
        200:
          description: OK
      tags:
      - Version
  /api/2/version/{id}/mergeto/{moveIssuesTo}:
    put:
      summary: Merge versions
      description: Merges two project versions. The merge is completed by deleting
        the version specified in `id` and replacing any occurrences of its ID in `fixVersion`
        with the version ID specified in `moveIssuesTo`. Consider using [Delete and
        replace version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
        instead. This resource supports swapping version values in `fixVersion`, `affectedVersion`,
        and custom fields. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
        or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.mergeVersions_put
      x-api-path-slug: api2versionidmergetomoveissuesto-put
      parameters:
      - in: path
        name: id
        description: The ID of the version to delete
      - in: path
        name: moveIssuesTo
        description: The ID of the version to merge into
      responses:
        200:
          description: OK
      tags:
      - Merge
      - Versions
  /api/2/version/{id}/move:
    post:
      summary: Move version
      description: Modifies the version's sequence within the project, which affects
        the display order of the versions in Jira. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
        or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.moveVersion_post
      x-api-path-slug: api2versionidmove-post
      parameters:
      - in: path
        name: id
        description: The ID of the version to be moved
      responses:
        200:
          description: OK
      tags:
      - Move
      - Version
  /api/2/version/{id}/removeAndSwap:
    post:
      summary: Delete and replace version
      description: Deletes a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
        or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
        Alternative versions can be provided to update issues that use the deleted
        version in `fixVersion`, `affectedVersion`, or any version picker custom fields.
        If alternatives are not provided, occurrences of `fixVersion`, `affectedVersion`,
        and any version picker custom field, that contain the deleted version, are
        cleared. Any replacement version must be in the same project as the version
        being deleted and cannot be the version being deleted.
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.deleteAndReplaceVersion_post
      x-api-path-slug: api2versionidremoveandswap-post
      parameters:
      - in: path
        name: id
        description: The ID of the version
      responses:
        200:
          description: OK
      tags:
      - Replace
      - Version
  /api/2/notificationscheme:
    get:
      summary: Get notification schemes paginated
      description: |-
        Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) list of [notification schemes](https://confluence.atlassian.com/x/8YdKLg) in order by display name.

        ### About notification schemes

        A notification scheme is a list of events and recipients who will receive notifications for those events. The list is contained within the `notificationSchemeEvents` object and contains pairs of `events` and `notifications`:

        *   `event` Identifies the type of event. The events can be [Jira system events](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-eventsEvents) or [custom events](https://confluence.atlassian.com/x/AIlKLg).
        *   `notifications` Identifies the [recipients](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-recipientsRecipients) of notifications for each event. Recipients can be any of the following types:

        *   `CurrentAssignee`
        *   `Reporter`
        *   `CurrentUser`
        *   `ProjectLead`
        *   `ComponentLead`
        *   `User` (the `parameter` is the user key)
        *   `Group` (the `parameter` is the group name)
        *   `ProjectRole` (the `parameter` is the project role ID)
        *   `EmailAddress`
        *   `AllWatchers`
        *   `UserCustomField` (the `parameter` is the ID of the custom field)
        *   `GroupCustomField`(the `parameter` is the ID of the custom field)

        _Note that you should allow for events without recipients to appear in responses._

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None, however the requesting user must have permission to administer at least one project associated with a notification scheme for it to be returned.
      operationId: com.atlassian.jira.rest.v2.notification.NotificationSchemeResource.getNotificationSchemes_get
      x-api-path-slug: api2notificationscheme-get
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      - in: query
        name: maxResults
        description: The maximum number of items to return per page
      - in: query
        name: startAt
        description: The index of the first item to return in a page of results (page
          offset)
      responses:
        200:
          description: OK
      tags:
      - Notification
      - Schemes
      - Paginated
  /api/2/permissions:
    get:
      summary: Get all permissions
      description: Returns all permissions that are present in the Jira instance -
        Global, Project and the global ones added by plugins
      operationId: com.atlassian.jira.rest.v2.permission.PermissionsResource.getAllPermissions_get
      x-api-path-slug: api2permissions-get
      responses:
        200:
          description: OK
      tags:
      - Permissions
  /api/2/permissionscheme:
    get:
      summary: Get all permission schemes
      description: |-
        Returns all permission schemes.

        ### About permission schemes and grants

        A permission scheme is a collection of permission grants. A permission grant consists of a `holder` and a `permission`.

        #### Holder

        The `holder` object contains information about the user or group being granted the permission. For example, the _Administer projects_ permission is granted to a group named _Teams in space administrators_. In this case, the type is `"type": "group"`, and the parameter is the group name, `"parameter": "Teams in space administrators"`. The `holder` object is defined by the following properties:

        *   `type` Identifies the user or group (see the list of types below).
        *   `parameter` The value of this property depends on the `type`. For example, if the `type` is a group, then you need to specify the group name.

        The following `types` are available. The expected values for the `parameter` are given in parenthesis (some `types` may not have a `parameter`):

        *   `anyone` Grant for anonymous users.
        *   `applicationRole` Grant for users with access to the specified application (application name). See [Manage application access](https://confluence.atlassian.com/cloud/manage-application-access-744721629.html) for more information.
        *   `assignee` Grant for the user currently assigned to an issue.
        *   `group` Grant for the specified group (group name).
        *   `groupCustomField` Grant for a user in the group selected in the specified custom field (custom field ID).
        *   `projectLead` Grant for a project lead.
        *   `projectRole` Grant for the specified project role (project role ID).
        *   `reporter` Grant for the user who reported the issue.
        *   `sd.customer.portal.only` Jira Service Desk only. Grants customers permission to access the customer portal but not Jira. See [Customizing Jira Service Desk permissions](https://confluence.atlassian.com/x/24dKLg) for more information.
        *   `user` Grant for the specified user (user ID).
        *   `userCustomField` Grant for a user selected in the specified custom field (custom field ID).

        #### Permissions

        The [built-in Jira permissions](https://confluence.atlassian.com/x/yodKLg) are listed below. Apps can also define custom permissions. See the [project permission](https://developer.atlassian.com/cloud/jira/platform/modules/project-permission/) and [global permission](https://developer.atlassian.com/cloud/jira/platform/modules/global-permission/) module documentation for more information.

        **Project permissions**

        *   `ADMINISTER_PROJECTS`
        *   `BROWSE_PROJECTS`
        *   `MANAGE_SPRINTS_PERMISSION` (Jira Software only)
        *   `SERVICEDESK_AGENT` (Jira Service Desk only)
        *   `VIEW_DEV_TOOLS` (Jira Software only)
        *   `VIEW_READONLY_WORKFLOW`

        **Issue permissions**

        *   `ASSIGNABLE_USER`
        *   `ASSIGN_ISSUES`
        *   `CLOSE_ISSUES`
        *   `CREATE_ISSUES`
        *   `DELETE_ISSUES`
        *   `EDIT_ISSUES`
        *   `LINK_ISSUES`
        *   `MODIFY_REPORTER`
        *   `MOVE_ISSUES`
        *   `RESOLVE_ISSUES`
        *   `SCHEDULE_ISSUES`
        *   `SET_ISSUE_SECURITY`
        *   `TRANSITION_ISSUES`

        **Voters and watchers permissions**

        *   `MANAGE_WATCHERS`
        *   `VIEW_VOTERS_AND_WATCHERS`

        **Comments permissions**

        *   `ADD_COMMENTS`
        *   `DELETE_ALL_COMMENTS`
        *   `DELETE_OWN_COMMENTS`
        *   `EDIT_ALL_COMMENTS`
        *   `EDIT_OWN_COMMENTS`

        **Attachments permissions**

        *   `CREATE_ATTACHMENTS`
        *   `DELETE_ALL_ATTACHMENTS`
        *   `DELETE_OWN_ATTACHMENTS`

        **Time tracking permissions**

        *   `DELETE_ALL_WORKLOGS`
        *   `DELETE_OWN_WORKLOGS`
        *   `EDIT_ALL_WORKLOGS`
        *   `EDIT_OWN_WORKLOGS`
        *   `WORK_ON_ISSUES`

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira.
      operationId: com.atlassian.jira.rest.v2.admin.permissionscheme.PermissionSchemeResource.getAllPermissionSchemes_g
      x-api-path-slug: api2permissionscheme-get
      parameters:
      - in: query
        name: expand
        description: Use expand to include additional information in the response
      responses:
        200:
          description: OK
      tags:
      - Permission
      - Schemes
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