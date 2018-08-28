---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Projects
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: Jira Cloud REST API - Get permitted projects
  x-api-slug: api2permissionsproject-post
  description: Returns all projects where currently logged in user was granted ALL
    requested project permissions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissionsproject-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissionsproject-post-openapi.md
- name: Jira Cloud REST API - Get all projects
  x-api-slug: api2project-get
  description: |-
    Returns all projects visible to the currently logged in user. For projects to be visible, the authenticated user must be granted either _Browse projects_ or _Administer projects_ permissions. If no user is logged in, it returns all projects that are visible for anonymous users.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-get-openapi.md
- name: Jira Cloud REST API - Find users assignable to projects
  x-api-slug: api2userassignablemultiprojectsearch-get
  description: |-
    Returns a list of users who fulfill both of these criteria:

    *   their user attributes match a string.
    *   they can be assigned issues in one or more projects.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userassignablemultiprojectsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userassignablemultiprojectsearch-get-openapi.md
- name: Jira Cloud REST API - Create project
  x-api-slug: api2project-post
  description: |-
    Creates a new project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-post-openapi.md
- name: Jira Cloud REST API - Get all project types
  x-api-slug: api2projecttype-get
  description: |-
    Returns all [project types](https://confluence.atlassian.com/x/Var1Nw), whether or not the instance has a valid license for each type.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttype-get-openapi.md
- name: Jira Cloud REST API - Get project type by key
  x-api-slug: api2projecttypeprojecttypekey-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekey-get-openapi.md
- name: Jira Cloud REST API - Get accessible project type by key
  x-api-slug: api2projecttypeprojecttypekeyaccessible-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-openapi.md
- name: Jira Cloud REST API - Get project
  x-api-slug: api2projectprojectidorkey-get
  description: |-
    Returns the [project details](https://confluence.atlassian.com/x/ahLpNw) for the specified project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-openapi.md
- name: Jira Cloud REST API - Update project
  x-api-slug: api2projectprojectidorkey-put
  description: |-
    Updates the [project details](https://confluence.atlassian.com/x/ahLpNw) of an existing project.

    All parameters are optional in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-put-openapi.md
- name: Jira Cloud REST API - Delete project
  x-api-slug: api2projectprojectidorkey-delete
  description: |-
    Deletes an existing project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-delete-openapi.md
- name: Jira Cloud REST API - Update project avatar
  x-api-slug: api2projectprojectidorkeyavatar-put
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar-put-openapi.md
- name: Jira Cloud REST API - Delete project avatar
  x-api-slug: api2projectprojectidorkeyavatarid-delete
  description: Deletes an avatar of a single project. It is only possible to delete
    custom avatars.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatarid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatarid-delete-openapi.md
- name: Jira Cloud REST API - Create project avatar
  x-api-slug: api2projectprojectidorkeyavatar2-post
  description: Creates an avatar for a single project. Use it to upload an image to
    be be set as a project's avatar. The uploaded image will be cropped according
    to the crop parameters defined in the request. If no crop parameters are specified,
    the image will be cropped to a square. The square will originate at the top left
    of the image and the length of each side will be set to the smaller of the height
    or width of the image.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar2-post-openapi.md
- name: Jira Cloud REST API - Get all project avatars
  x-api-slug: api2projectprojectidorkeyavatars-get
  description: Returns all project avatars visible for the currently logged in user.
    The avatars are grouped into system avatars and custom avatars.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatars-get-openapi.md
- name: Jira Cloud REST API - Get project components paginated
  x-api-slug: api2projectprojectidorkeycomponent-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all components existing in a single project. See the [Get project components](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-components-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-openapi.md
- name: Jira Cloud REST API - Get project components
  x-api-slug: api2projectprojectidorkeycomponents-get
  description: |-
    Returns all components existing in a single project. See the [Get project components paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-component-get) resource if you want to get a full list of components with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-openapi.md
- name: Jira Cloud REST API - Get project property keys
  x-api-slug: api2projectprojectidorkeyproperties-get
  description: |-
    Returns all [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-get
  description: |-
    Returns the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Set project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). You can use project properties to store custom data against the project.

    The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 bytes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Delete project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-delete
  description: |-
    Removes the [property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) from the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Get project roles for project
  x-api-slug: api2projectprojectidorkeyrole-get
  description: |-
    Returns a list of [project roles](https://confluence.atlassian.com/x/3odKLg) for the project.

    Note that all project roles are shared with all projects in Jira Cloud. See the [Get all project roles](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-get) resource for more information.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-openapi.md
- name: Jira Cloud REST API - Get project role for project
  x-api-slug: api2projectprojectidorkeyroleid-get
  description: |-
    Returns the project role's details and actors associated with the project. The list of actors is sorted by display name.

    If you would like to check to see whether a user belongs to a role based on their group memberships, use the [Get user](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-user-get) resource with the `groups` expand parameter selected. Then check whether the user keys and groups match with the actors returned for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-openapi.md
- name: Jira Cloud REST API - Add actors to project role
  x-api-slug: api2projectprojectidorkeyroleid-post
  description: |-
    Adds additional actors to a project role for the project.

    If you want to replace all actors for the project, then use [Set actors for project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-put).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-openapi.md
- name: Jira Cloud REST API - Delete actors from project role
  x-api-slug: api2projectprojectidorkeyroleid-delete
  description: |-
    Deletes actors from a project role for the project.

    If you want to remove default actors from the project role, see the [Delete default actors from project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-delete) resource.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-openapi.md
- name: Jira Cloud REST API - Get project role details
  x-api-slug: api2projectprojectidorkeyroledetails-get
  description: Returns all [project roles](https://confluence.atlassian.com/x/3odKLg)
    and the details for each role. Note that the list of project roles is common to
    all projects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-openapi.md
- name: Jira Cloud REST API - Update project type
  x-api-slug: api2projectprojectidorkeytypenewprojecttypekey-put
  description: |-
    Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-openapi.md
- name: Jira Cloud REST API - Get project versions paginated
  x-api-slug: api2projectprojectidorkeyversion-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all versions existing in a single project. See the [Get project versions](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-versions-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-openapi.md
- name: Jira Cloud REST API - Get project versions
  x-api-slug: api2projectprojectidorkeyversions-get
  description: |-
    Returns all versions existing in a single project. The response is not paginated. Use [Get project versions paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-version-get) if you want to get the versions in a project with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversions-get-openapi.md
- name: Jira Cloud REST API - Get project issue security scheme
  x-api-slug: api2projectprojectkeyoridissuesecuritylevelscheme-get
  description: |-
    Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or the _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-openapi.md
- name: Jira Cloud REST API - Get project notification scheme
  x-api-slug: api2projectprojectkeyoridnotificationscheme-get
  description: |-
    Gets a [notification scheme](https://confluence.atlassian.com/x/8YdKLg) associated with the project. See the [Get notification scheme](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-notificationscheme-id-get) resource for more information about notification schemes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get all project categories
  x-api-slug: api2projectcategory-get
  description: Returns all project categories
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-openapi.md
- name: Jira Cloud REST API - Create project category
  x-api-slug: api2projectcategory-post
  description: Create a project category via POST.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-openapi.md
- name: Jira Cloud REST API - Get project category by id
  x-api-slug: api2projectcategoryid-get
  description: Contains a representation of a project category in JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-openapi.md
- name: Jira Cloud REST API - Update project category
  x-api-slug: api2projectcategoryid-put
  description: Modify a project category via PUT. Any fields present in the PUT will
    override existing values. As a convenience, if a field is not present, it is silently
    ignored.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-put-openapi.md
- name: Jira Cloud REST API - Remove project category
  x-api-slug: api2projectcategoryid-delete
  description: Delete a project category.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-delete-openapi.md
- name: Jira Cloud REST API - Validate project key
  x-api-slug: api2projectvalidatekey-get
  description: Validates a project key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatekey-get-openapi.md
- name: Jira Cloud REST API - Get valid project key
  x-api-slug: api2projectvalidatevalidprojectkey-get
  description: Validates the project key and generated a valid project key if the
    supplied key is invalid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-openapi.md
- name: Jira Cloud REST API - Get valid project name
  x-api-slug: api2projectvalidatevalidprojectname-get
  description: Validates a project name. If the name is invalid, an attempt is made
    to produce a valid name based on the supplied one. If no such valid name can be
    found, an empty string is returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-openapi.md
- name: Jira Cloud REST API - Get all project roles
  x-api-slug: api2role-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-openapi.md
- name: Jira Cloud REST API - Create project role
  x-api-slug: api2role-post
  description: |-
    Creates a new project role with no [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get). You can use the [Add default actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-post) the project method to add default actors to the project role after creating it.

    _Note that although a new project role is available to all projects upon creation, any default actors that are associated with the project role are not added to projects that existed prior to the role being created._<

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-post-openapi.md
- name: Jira Cloud REST API - Get project role by ID
  x-api-slug: api2roleid-get
  description: |-
    Gets the project role details and the default actors associated with the role. The list of default actors is sorted by display name.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-get-openapi.md
- name: Jira Cloud REST API - Partial update project role
  x-api-slug: api2roleid-post
  description: |-
    Update either the project role's name or its description.

    You cannot update both the name and description at the same time using this method. If you send a request with both a name and a description, then only the name will be updated, regardless of the order of appearance in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-openapi.md
- name: Jira Cloud REST API - Fully update project role
  x-api-slug: api2roleid-put
  description: |-
    Update the project role's name and description. You must include both a name and a description in the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-openapi.md
- name: Jira Cloud REST API - Delete project role
  x-api-slug: api2roleid-delete
  description: |-
    Deletes a project role. You must specify a replacement project role if you wish to delete a project role that is in use.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-delete-openapi.md
- name: Jira Cloud REST API - Add default actors to project role
  x-api-slug: api2roleidactors-post
  description: |-
    Adds [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) to the given role. You may add either groups or users, but you cannot add groups and users in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-openapi.md
- name: Jira Cloud REST API - Delete default actors from project role
  x-api-slug: api2roleidactors-delete
  description: |-
    Removes [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) from the project role. You may remove either a group or user, but you cannot remove a group and a user in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-openapi.md
- name: Jira Cloud REST API - Get create issue meta
  x-api-slug: api2issuecreatemeta-get
  description: |-
    Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

    The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

    Fields will only be returned if `expand=projects.issuetypes.fields` is set.

    The results can be filtered by project and/or issue type, controlled by the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2issuecreatemeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2issuecreatemeta-get-openapi.md
- name: Jira Cloud REST API - Set actors for project role
  x-api-slug: api2projectprojectidorkeyroleid-put
  description: |-
    Associates actors with the project role for the project, replacing all existing actors.

    If you want to add actors to the project without overwriting the existing list, then use [Add actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-post).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-put-openapi.md
- name: Jira Cloud REST API - Get all statuses
  x-api-slug: api2projectprojectidorkeystatuses-get
  description: |-
    Returns the valid statuses for a project. The statuses are grouped by issue type, as each project has a set of valid issue types and each issue type has a set of valid statuses.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeystatuses-get-openapi.md
- name: Jira Cloud REST API - Find users with permissions
  x-api-slug: api2userpermissionsearch-get
  description: |-
    Returns a list of users who fulfill both of these criteria:

    *   their user attributes match a search string.
    *   they have a set of permissions for a project or issue.

    If no search string is provided, a list of all users with the permissions is returned. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   Get users for any project, _Administer Jira_ [global permission](href=).
    *   Get users for a project, _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userpermissionsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userpermissionsearch-get-openapi.md
- name: Jira Cloud REST API - Create version
  x-api-slug: api2version-post
  description: Creates a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2version-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2version-post-openapi.md
- name: Jira Cloud REST API - Update version
  x-api-slug: api2versionid-put
  description: Modifies a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-put-openapi.md
- name: Jira Cloud REST API - Delete version
  x-api-slug: api2versionid-delete
  description: Deletes a project version. Deprecated, use [Delete and replace version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
    that supports swapping version values in custom fields, in addition to the swapping
    for `fixVersion` and `affectedVersion` provided in this resource. Alternative
    versions can be provided to update issues that use the deleted version in `fixVersion`
    or `affectedVersion`. If alternatives are not provided, occurrences of `fixVersion`
    and `affectedVersion` that contain the deleted version are cleared. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-delete-openapi.md
- name: Jira Cloud REST API - Merge versions
  x-api-slug: api2versionidmergetomoveissuesto-put
  description: Merges two project versions. The merge is completed by deleting the
    version specified in `id` and replacing any occurrences of its ID in `fixVersion`
    with the version ID specified in `moveIssuesTo`. Consider using [Delete and replace
    version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
    instead. This resource supports swapping version values in `fixVersion`, `affectedVersion`,
    and custom fields. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-openapi.md
- name: Jira Cloud REST API - Move version
  x-api-slug: api2versionidmove-post
  description: Modifies the version's sequence within the project, which affects the
    display order of the versions in Jira. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmove-post-openapi.md
- name: Jira Cloud REST API - Delete and replace version
  x-api-slug: api2versionidremoveandswap-post
  description: Deletes a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
    Alternative versions can be provided to update issues that use the deleted version
    in `fixVersion`, `affectedVersion`, or any version picker custom fields. If alternatives
    are not provided, occurrences of `fixVersion`, `affectedVersion`, and any version
    picker custom field, that contain the deleted version, are cleared. Any replacement
    version must be in the same project as the version being deleted and cannot be
    the version being deleted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidremoveandswap-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidremoveandswap-post-openapi.md
- name: Jira Cloud REST API - Create project
  x-api-slug: api2project-post
  description: |-
    Creates a new project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-post-openapi.md
- name: Jira Cloud REST API - Get all project types
  x-api-slug: api2projecttype-get
  description: |-
    Returns all [project types](https://confluence.atlassian.com/x/Var1Nw), whether or not the instance has a valid license for each type.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttype-get-openapi.md
- name: Jira Cloud REST API - Get project type by key
  x-api-slug: api2projecttypeprojecttypekey-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekey-get-openapi.md
- name: Jira Cloud REST API - Get accessible project type by key
  x-api-slug: api2projecttypeprojecttypekeyaccessible-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-openapi.md
- name: Jira Cloud REST API - Get project
  x-api-slug: api2projectprojectidorkey-get
  description: |-
    Returns the [project details](https://confluence.atlassian.com/x/ahLpNw) for the specified project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-openapi.md
- name: Jira Cloud REST API - Update project
  x-api-slug: api2projectprojectidorkey-put
  description: |-
    Updates the [project details](https://confluence.atlassian.com/x/ahLpNw) of an existing project.

    All parameters are optional in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-put-openapi.md
- name: Jira Cloud REST API - Delete project
  x-api-slug: api2projectprojectidorkey-delete
  description: |-
    Deletes an existing project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-delete-openapi.md
- name: Jira Cloud REST API - Update project avatar
  x-api-slug: api2projectprojectidorkeyavatar-put
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar-put-openapi.md
- name: Jira Cloud REST API - Delete project avatar
  x-api-slug: api2projectprojectidorkeyavatarid-delete
  description: Deletes an avatar of a single project. It is only possible to delete
    custom avatars.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatarid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatarid-delete-openapi.md
- name: Jira Cloud REST API - Create project avatar
  x-api-slug: api2projectprojectidorkeyavatar2-post
  description: Creates an avatar for a single project. Use it to upload an image to
    be be set as a project's avatar. The uploaded image will be cropped according
    to the crop parameters defined in the request. If no crop parameters are specified,
    the image will be cropped to a square. The square will originate at the top left
    of the image and the length of each side will be set to the smaller of the height
    or width of the image.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar2-post-openapi.md
- name: Jira Cloud REST API - Get all project avatars
  x-api-slug: api2projectprojectidorkeyavatars-get
  description: Returns all project avatars visible for the currently logged in user.
    The avatars are grouped into system avatars and custom avatars.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatars-get-openapi.md
- name: Jira Cloud REST API - Get project components paginated
  x-api-slug: api2projectprojectidorkeycomponent-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all components existing in a single project. See the [Get project components](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-components-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-openapi.md
- name: Jira Cloud REST API - Get project components
  x-api-slug: api2projectprojectidorkeycomponents-get
  description: |-
    Returns all components existing in a single project. See the [Get project components paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-component-get) resource if you want to get a full list of components with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-openapi.md
- name: Jira Cloud REST API - Get project property keys
  x-api-slug: api2projectprojectidorkeyproperties-get
  description: |-
    Returns all [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-get
  description: |-
    Returns the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Set project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). You can use project properties to store custom data against the project.

    The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 bytes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Delete project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-delete
  description: |-
    Removes the [property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) from the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Get project roles for project
  x-api-slug: api2projectprojectidorkeyrole-get
  description: |-
    Returns a list of [project roles](https://confluence.atlassian.com/x/3odKLg) for the project.

    Note that all project roles are shared with all projects in Jira Cloud. See the [Get all project roles](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-get) resource for more information.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-openapi.md
- name: Jira Cloud REST API - Get project role for project
  x-api-slug: api2projectprojectidorkeyroleid-get
  description: |-
    Returns the project role's details and actors associated with the project. The list of actors is sorted by display name.

    If you would like to check to see whether a user belongs to a role based on their group memberships, use the [Get user](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-user-get) resource with the `groups` expand parameter selected. Then check whether the user keys and groups match with the actors returned for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-openapi.md
- name: Jira Cloud REST API - Add actors to project role
  x-api-slug: api2projectprojectidorkeyroleid-post
  description: |-
    Adds additional actors to a project role for the project.

    If you want to replace all actors for the project, then use [Set actors for project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-put).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-openapi.md
- name: Jira Cloud REST API - Delete actors from project role
  x-api-slug: api2projectprojectidorkeyroleid-delete
  description: |-
    Deletes actors from a project role for the project.

    If you want to remove default actors from the project role, see the [Delete default actors from project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-delete) resource.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-openapi.md
- name: Jira Cloud REST API - Get project role details
  x-api-slug: api2projectprojectidorkeyroledetails-get
  description: Returns all [project roles](https://confluence.atlassian.com/x/3odKLg)
    and the details for each role. Note that the list of project roles is common to
    all projects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-openapi.md
- name: Jira Cloud REST API - Update project type
  x-api-slug: api2projectprojectidorkeytypenewprojecttypekey-put
  description: |-
    Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-openapi.md
- name: Jira Cloud REST API - Get project versions paginated
  x-api-slug: api2projectprojectidorkeyversion-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all versions existing in a single project. See the [Get project versions](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-versions-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-openapi.md
- name: Jira Cloud REST API - Get project versions
  x-api-slug: api2projectprojectidorkeyversions-get
  description: |-
    Returns all versions existing in a single project. The response is not paginated. Use [Get project versions paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-version-get) if you want to get the versions in a project with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversions-get-openapi.md
- name: Jira Cloud REST API - Get project issue security scheme
  x-api-slug: api2projectprojectkeyoridissuesecuritylevelscheme-get
  description: |-
    Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or the _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-openapi.md
- name: Jira Cloud REST API - Get project notification scheme
  x-api-slug: api2projectprojectkeyoridnotificationscheme-get
  description: |-
    Gets a [notification scheme](https://confluence.atlassian.com/x/8YdKLg) associated with the project. See the [Get notification scheme](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-notificationscheme-id-get) resource for more information about notification schemes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get all project categories
  x-api-slug: api2projectcategory-get
  description: Returns all project categories
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-openapi.md
- name: Jira Cloud REST API - Create project category
  x-api-slug: api2projectcategory-post
  description: Create a project category via POST.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-openapi.md
- name: Jira Cloud REST API - Get project category by id
  x-api-slug: api2projectcategoryid-get
  description: Contains a representation of a project category in JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-openapi.md
- name: Jira Cloud REST API - Update project category
  x-api-slug: api2projectcategoryid-put
  description: Modify a project category via PUT. Any fields present in the PUT will
    override existing values. As a convenience, if a field is not present, it is silently
    ignored.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-put-openapi.md
- name: Jira Cloud REST API - Remove project category
  x-api-slug: api2projectcategoryid-delete
  description: Delete a project category.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-delete-openapi.md
- name: Jira Cloud REST API - Validate project key
  x-api-slug: api2projectvalidatekey-get
  description: Validates a project key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatekey-get-openapi.md
- name: Jira Cloud REST API - Get valid project key
  x-api-slug: api2projectvalidatevalidprojectkey-get
  description: Validates the project key and generated a valid project key if the
    supplied key is invalid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-openapi.md
- name: Jira Cloud REST API - Get valid project name
  x-api-slug: api2projectvalidatevalidprojectname-get
  description: Validates a project name. If the name is invalid, an attempt is made
    to produce a valid name based on the supplied one. If no such valid name can be
    found, an empty string is returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-openapi.md
- name: Jira Cloud REST API - Get all project roles
  x-api-slug: api2role-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-openapi.md
- name: Jira Cloud REST API - Create project role
  x-api-slug: api2role-post
  description: |-
    Creates a new project role with no [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get). You can use the [Add default actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-post) the project method to add default actors to the project role after creating it.

    _Note that although a new project role is available to all projects upon creation, any default actors that are associated with the project role are not added to projects that existed prior to the role being created._<

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-post-openapi.md
- name: Jira Cloud REST API - Get project role by ID
  x-api-slug: api2roleid-get
  description: |-
    Gets the project role details and the default actors associated with the role. The list of default actors is sorted by display name.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-get-openapi.md
- name: Jira Cloud REST API - Partial update project role
  x-api-slug: api2roleid-post
  description: |-
    Update either the project role's name or its description.

    You cannot update both the name and description at the same time using this method. If you send a request with both a name and a description, then only the name will be updated, regardless of the order of appearance in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-openapi.md
- name: Jira Cloud REST API - Fully update project role
  x-api-slug: api2roleid-put
  description: |-
    Update the project role's name and description. You must include both a name and a description in the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-openapi.md
- name: Jira Cloud REST API - Delete project role
  x-api-slug: api2roleid-delete
  description: |-
    Deletes a project role. You must specify a replacement project role if you wish to delete a project role that is in use.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-delete-openapi.md
- name: Jira Cloud REST API - Add default actors to project role
  x-api-slug: api2roleidactors-post
  description: |-
    Adds [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) to the given role. You may add either groups or users, but you cannot add groups and users in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-openapi.md
- name: Jira Cloud REST API - Delete default actors from project role
  x-api-slug: api2roleidactors-delete
  description: |-
    Removes [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) from the project role. You may remove either a group or user, but you cannot remove a group and a user in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-openapi.md
- name: Jira Cloud REST API - Get create issue meta
  x-api-slug: api2issuecreatemeta-get
  description: |-
    Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

    The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

    Fields will only be returned if `expand=projects.issuetypes.fields` is set.

    The results can be filtered by project and/or issue type, controlled by the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2issuecreatemeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2issuecreatemeta-get-openapi.md
- name: Jira Cloud REST API - Get notification schemes paginated
  x-api-slug: api2notificationscheme-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2notificationscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2notificationscheme-get-openapi.md
- name: Jira Cloud REST API - Get all permissions
  x-api-slug: api2permissions-get
  description: Returns all permissions that are present in the Jira instance - Global,
    Project and the global ones added by plugins
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissions-get-openapi.md
- name: Jira Cloud REST API - Get all permission schemes
  x-api-slug: api2permissionscheme-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissionscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissionscheme-get-openapi.md
- name: Jira Cloud REST API - Get all projects
  x-api-slug: api2project-get
  description: |-
    Returns all projects visible to the currently logged in user. For projects to be visible, the authenticated user must be granted either _Browse projects_ or _Administer projects_ permissions. If no user is logged in, it returns all projects that are visible for anonymous users.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-get-openapi.md
- name: Jira Cloud REST API - Set actors for project role
  x-api-slug: api2projectprojectidorkeyroleid-put
  description: |-
    Associates actors with the project role for the project, replacing all existing actors.

    If you want to add actors to the project without overwriting the existing list, then use [Add actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-post).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-put-openapi.md
- name: Jira Cloud REST API - Get all statuses
  x-api-slug: api2projectprojectidorkeystatuses-get
  description: |-
    Returns the valid statuses for a project. The statuses are grouped by issue type, as each project has a set of valid issue types and each issue type has a set of valid statuses.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeystatuses-get-openapi.md
- name: Jira Cloud REST API - Find users assignable to projects
  x-api-slug: api2userassignablemultiprojectsearch-get
  description: |-
    Returns a list of users who fulfill both of these criteria:

    *   their user attributes match a string.
    *   they can be assigned issues in one or more projects.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userassignablemultiprojectsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userassignablemultiprojectsearch-get-openapi.md
- name: Jira Cloud REST API - Find users with permissions
  x-api-slug: api2userpermissionsearch-get
  description: |-
    Returns a list of users who fulfill both of these criteria:

    *   their user attributes match a search string.
    *   they have a set of permissions for a project or issue.

    If no search string is provided, a list of all users with the permissions is returned. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   Get users for any project, _Administer Jira_ [global permission](href=).
    *   Get users for a project, _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userpermissionsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userpermissionsearch-get-openapi.md
- name: Jira Cloud REST API - Create version
  x-api-slug: api2version-post
  description: Creates a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2version-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2version-post-openapi.md
- name: Jira Cloud REST API - Update version
  x-api-slug: api2versionid-put
  description: Modifies a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-put-openapi.md
- name: Jira Cloud REST API - Delete version
  x-api-slug: api2versionid-delete
  description: Deletes a project version. Deprecated, use [Delete and replace version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
    that supports swapping version values in custom fields, in addition to the swapping
    for `fixVersion` and `affectedVersion` provided in this resource. Alternative
    versions can be provided to update issues that use the deleted version in `fixVersion`
    or `affectedVersion`. If alternatives are not provided, occurrences of `fixVersion`
    and `affectedVersion` that contain the deleted version are cleared. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-delete-openapi.md
- name: Jira Cloud REST API - Merge versions
  x-api-slug: api2versionidmergetomoveissuesto-put
  description: Merges two project versions. The merge is completed by deleting the
    version specified in `id` and replacing any occurrences of its ID in `fixVersion`
    with the version ID specified in `moveIssuesTo`. Consider using [Delete and replace
    version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
    instead. This resource supports swapping version values in `fixVersion`, `affectedVersion`,
    and custom fields. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-openapi.md
- name: Jira Cloud REST API - Move version
  x-api-slug: api2versionidmove-post
  description: Modifies the version's sequence within the project, which affects the
    display order of the versions in Jira. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmove-post-openapi.md
- name: Jira Cloud REST API - Delete and replace version
  x-api-slug: api2versionidremoveandswap-post
  description: Deletes a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
    Alternative versions can be provided to update issues that use the deleted version
    in `fixVersion`, `affectedVersion`, or any version picker custom fields. If alternatives
    are not provided, occurrences of `fixVersion`, `affectedVersion`, and any version
    picker custom field, that contain the deleted version, are cleared. Any replacement
    version must be in the same project as the version being deleted and cannot be
    the version being deleted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidremoveandswap-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidremoveandswap-post-openapi.md
- name: Jira Cloud REST API - Get create issue meta
  x-api-slug: api2issuecreatemeta-get
  description: |-
    Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

    The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

    Fields will only be returned if `expand=projects.issuetypes.fields` is set.

    The results can be filtered by project and/or issue type, controlled by the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2issuecreatemeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2issuecreatemeta-get-openapi.md
- name: Jira Cloud REST API - Get notification schemes paginated
  x-api-slug: api2notificationscheme-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2notificationscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2notificationscheme-get-openapi.md
- name: Jira Cloud REST API - Get all permissions
  x-api-slug: api2permissions-get
  description: Returns all permissions that are present in the Jira instance - Global,
    Project and the global ones added by plugins
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissions-get-openapi.md
- name: Jira Cloud REST API - Get all permission schemes
  x-api-slug: api2permissionscheme-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissionscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2permissionscheme-get-openapi.md
- name: Jira Cloud REST API - Get all projects
  x-api-slug: api2project-get
  description: |-
    Returns all projects visible to the currently logged in user. For projects to be visible, the authenticated user must be granted either _Browse projects_ or _Administer projects_ permissions. If no user is logged in, it returns all projects that are visible for anonymous users.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-get-openapi.md
- name: Jira Cloud REST API - Get project
  x-api-slug: api2projectprojectidorkey-get
  description: |-
    Returns the [project details](https://confluence.atlassian.com/x/ahLpNw) for the specified project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-openapi.md
- name: Jira Cloud REST API - Get project components paginated
  x-api-slug: api2projectprojectidorkeycomponent-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all components existing in a single project. See the [Get project components](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-components-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-openapi.md
- name: Jira Cloud REST API - Get project components
  x-api-slug: api2projectprojectidorkeycomponents-get
  description: |-
    Returns all components existing in a single project. See the [Get project components paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-component-get) resource if you want to get a full list of components with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-openapi.md
- name: Jira Cloud REST API - Get project property keys
  x-api-slug: api2projectprojectidorkeyproperties-get
  description: |-
    Returns all [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-get
  description: |-
    Returns the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Set project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). You can use project properties to store custom data against the project.

    The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 bytes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Get project roles for project
  x-api-slug: api2projectprojectidorkeyrole-get
  description: |-
    Returns a list of [project roles](https://confluence.atlassian.com/x/3odKLg) for the project.

    Note that all project roles are shared with all projects in Jira Cloud. See the [Get all project roles](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-get) resource for more information.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-openapi.md
- name: Jira Cloud REST API - Get project role for project
  x-api-slug: api2projectprojectidorkeyroleid-get
  description: |-
    Returns the project role's details and actors associated with the project. The list of actors is sorted by display name.

    If you would like to check to see whether a user belongs to a role based on their group memberships, use the [Get user](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-user-get) resource with the `groups` expand parameter selected. Then check whether the user keys and groups match with the actors returned for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-openapi.md
- name: Jira Cloud REST API - Add actors to project role
  x-api-slug: api2projectprojectidorkeyroleid-post
  description: |-
    Adds additional actors to a project role for the project.

    If you want to replace all actors for the project, then use [Set actors for project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-put).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-openapi.md
- name: Jira Cloud REST API - Set actors for project role
  x-api-slug: api2projectprojectidorkeyroleid-put
  description: |-
    Associates actors with the project role for the project, replacing all existing actors.

    If you want to add actors to the project without overwriting the existing list, then use [Add actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-post).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-put-openapi.md
- name: Jira Cloud REST API - Delete actors from project role
  x-api-slug: api2projectprojectidorkeyroleid-delete
  description: |-
    Deletes actors from a project role for the project.

    If you want to remove default actors from the project role, see the [Delete default actors from project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-delete) resource.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-openapi.md
- name: Jira Cloud REST API - Get all statuses
  x-api-slug: api2projectprojectidorkeystatuses-get
  description: |-
    Returns the valid statuses for a project. The statuses are grouped by issue type, as each project has a set of valid issue types and each issue type has a set of valid statuses.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeystatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeystatuses-get-openapi.md
- name: Jira Cloud REST API - Update project type
  x-api-slug: api2projectprojectidorkeytypenewprojecttypekey-put
  description: |-
    Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-openapi.md
- name: Jira Cloud REST API - Get project versions paginated
  x-api-slug: api2projectprojectidorkeyversion-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all versions existing in a single project. See the [Get project versions](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-versions-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-openapi.md
- name: Jira Cloud REST API - Get project versions
  x-api-slug: api2projectprojectidorkeyversions-get
  description: |-
    Returns all versions existing in a single project. The response is not paginated. Use [Get project versions paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-version-get) if you want to get the versions in a project with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversions-get-openapi.md
- name: Jira Cloud REST API - Get project issue security scheme
  x-api-slug: api2projectprojectkeyoridissuesecuritylevelscheme-get
  description: |-
    Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or the _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-openapi.md
- name: Jira Cloud REST API - Get project notification scheme
  x-api-slug: api2projectprojectkeyoridnotificationscheme-get
  description: |-
    Gets a [notification scheme](https://confluence.atlassian.com/x/8YdKLg) associated with the project. See the [Get notification scheme](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-notificationscheme-id-get) resource for more information about notification schemes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-openapi.md
- name: Jira Cloud REST API - Get valid project key
  x-api-slug: api2projectvalidatevalidprojectkey-get
  description: Validates the project key and generated a valid project key if the
    supplied key is invalid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-openapi.md
- name: Jira Cloud REST API - Get valid project name
  x-api-slug: api2projectvalidatevalidprojectname-get
  description: Validates a project name. If the name is invalid, an attempt is made
    to produce a valid name based on the supplied one. If no such valid name can be
    found, an empty string is returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-openapi.md
- name: Jira Cloud REST API - Get all project roles
  x-api-slug: api2role-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-openapi.md
- name: Jira Cloud REST API - Find users assignable to projects
  x-api-slug: api2userassignablemultiprojectsearch-get
  description: |-
    Returns a list of users who fulfill both of these criteria:

    *   their user attributes match a string.
    *   they can be assigned issues in one or more projects.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userassignablemultiprojectsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userassignablemultiprojectsearch-get-openapi.md
- name: Jira Cloud REST API - Find users with permissions
  x-api-slug: api2userpermissionsearch-get
  description: |-
    Returns a list of users who fulfill both of these criteria:

    *   their user attributes match a search string.
    *   they have a set of permissions for a project or issue.

    If no search string is provided, a list of all users with the permissions is returned. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   Get users for any project, _Administer Jira_ [global permission](href=).
    *   Get users for a project, _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userpermissionsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2userpermissionsearch-get-openapi.md
- name: Jira Cloud REST API - Create version
  x-api-slug: api2version-post
  description: Creates a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2version-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2version-post-openapi.md
- name: Jira Cloud REST API - Update version
  x-api-slug: api2versionid-put
  description: Modifies a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-put-openapi.md
- name: Jira Cloud REST API - Delete version
  x-api-slug: api2versionid-delete
  description: Deletes a project version. Deprecated, use [Delete and replace version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
    that supports swapping version values in custom fields, in addition to the swapping
    for `fixVersion` and `affectedVersion` provided in this resource. Alternative
    versions can be provided to update issues that use the deleted version in `fixVersion`
    or `affectedVersion`. If alternatives are not provided, occurrences of `fixVersion`
    and `affectedVersion` that contain the deleted version are cleared. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionid-delete-openapi.md
- name: Jira Cloud REST API - Merge versions
  x-api-slug: api2versionidmergetomoveissuesto-put
  description: Merges two project versions. The merge is completed by deleting the
    version specified in `id` and replacing any occurrences of its ID in `fixVersion`
    with the version ID specified in `moveIssuesTo`. Consider using [Delete and replace
    version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
    instead. This resource supports swapping version values in `fixVersion`, `affectedVersion`,
    and custom fields. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-openapi.md
- name: Jira Cloud REST API - Move version
  x-api-slug: api2versionidmove-post
  description: Modifies the version's sequence within the project, which affects the
    display order of the versions in Jira. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidmove-post-openapi.md
- name: Jira Cloud REST API - Delete and replace version
  x-api-slug: api2versionidremoveandswap-post
  description: Deletes a project version. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
    Alternative versions can be provided to update issues that use the deleted version
    in `fixVersion`, `affectedVersion`, or any version picker custom fields. If alternatives
    are not provided, occurrences of `fixVersion`, `affectedVersion`, and any version
    picker custom field, that contain the deleted version, are cleared. Any replacement
    version must be in the same project as the version being deleted and cannot be
    the version being deleted.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidremoveandswap-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2versionidremoveandswap-post-openapi.md
- name: Jira Cloud REST API - Delete default actors from project role
  x-api-slug: api2roleidactors-delete
  description: |-
    Removes [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) from the project role. You may remove either a group or user, but you cannot remove a group and a user in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-openapi.md
- name: Jira Cloud REST API - Delete default actors from project role
  x-api-slug: api2roleidactors-delete
  description: |-
    Removes [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) from the project role. You may remove either a group or user, but you cannot remove a group and a user in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-openapi.md
- name: Jira Cloud REST API - Delete default actors from project role
  x-api-slug: api2roleidactors-delete
  description: |-
    Removes [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) from the project role. You may remove either a group or user, but you cannot remove a group and a user in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-openapi.md
- name: Jira Cloud REST API - Delete default actors from project role
  x-api-slug: api2roleidactors-delete
  description: |-
    Removes [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) from the project role. You may remove either a group or user, but you cannot remove a group and a user in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-openapi.md
- name: Jira Cloud REST API - Delete default actors from project role
  x-api-slug: api2roleidactors-delete
  description: |-
    Removes [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) from the project role. You may remove either a group or user, but you cannot remove a group and a user in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-delete-openapi.md
- name: Jira Cloud REST API - Add default actors to project role
  x-api-slug: api2roleidactors-post
  description: |-
    Adds [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) to the given role. You may add either groups or users, but you cannot add groups and users in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-openapi.md
- name: Jira Cloud REST API - Add default actors to project role
  x-api-slug: api2roleidactors-post
  description: |-
    Adds [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) to the given role. You may add either groups or users, but you cannot add groups and users in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-openapi.md
- name: Jira Cloud REST API - Add default actors to project role
  x-api-slug: api2roleidactors-post
  description: |-
    Adds [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) to the given role. You may add either groups or users, but you cannot add groups and users in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-openapi.md
- name: Jira Cloud REST API - Add default actors to project role
  x-api-slug: api2roleidactors-post
  description: |-
    Adds [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) to the given role. You may add either groups or users, but you cannot add groups and users in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-openapi.md
- name: Jira Cloud REST API - Add default actors to project role
  x-api-slug: api2roleidactors-post
  description: |-
    Adds [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get) to the given role. You may add either groups or users, but you cannot add groups and users in the same request.

    Changing a project role's default actors does not affect project role members for projects already created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleidactors-post-openapi.md
- name: Jira Cloud REST API - Delete project role
  x-api-slug: api2roleid-delete
  description: |-
    Deletes a project role. You must specify a replacement project role if you wish to delete a project role that is in use.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-delete-openapi.md
- name: Jira Cloud REST API - Delete project role
  x-api-slug: api2roleid-delete
  description: |-
    Deletes a project role. You must specify a replacement project role if you wish to delete a project role that is in use.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-delete-openapi.md
- name: Jira Cloud REST API - Fully update project role
  x-api-slug: api2roleid-put
  description: |-
    Update the project role's name and description. You must include both a name and a description in the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-openapi.md
- name: Jira Cloud REST API - Fully update project role
  x-api-slug: api2roleid-put
  description: |-
    Update the project role's name and description. You must include both a name and a description in the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-openapi.md
- name: Jira Cloud REST API - Fully update project role
  x-api-slug: api2roleid-put
  description: |-
    Update the project role's name and description. You must include both a name and a description in the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-openapi.md
- name: Jira Cloud REST API - Fully update project role
  x-api-slug: api2roleid-put
  description: |-
    Update the project role's name and description. You must include both a name and a description in the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-openapi.md
- name: Jira Cloud REST API - Fully update project role
  x-api-slug: api2roleid-put
  description: |-
    Update the project role's name and description. You must include both a name and a description in the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-put-openapi.md
- name: Jira Cloud REST API - Partial update project role
  x-api-slug: api2roleid-post
  description: |-
    Update either the project role's name or its description.

    You cannot update both the name and description at the same time using this method. If you send a request with both a name and a description, then only the name will be updated, regardless of the order of appearance in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-openapi.md
- name: Jira Cloud REST API - Partial update project role
  x-api-slug: api2roleid-post
  description: |-
    Update either the project role's name or its description.

    You cannot update both the name and description at the same time using this method. If you send a request with both a name and a description, then only the name will be updated, regardless of the order of appearance in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-openapi.md
- name: Jira Cloud REST API - Partial update project role
  x-api-slug: api2roleid-post
  description: |-
    Update either the project role's name or its description.

    You cannot update both the name and description at the same time using this method. If you send a request with both a name and a description, then only the name will be updated, regardless of the order of appearance in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-openapi.md
- name: Jira Cloud REST API - Partial update project role
  x-api-slug: api2roleid-post
  description: |-
    Update either the project role's name or its description.

    You cannot update both the name and description at the same time using this method. If you send a request with both a name and a description, then only the name will be updated, regardless of the order of appearance in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-post-openapi.md
- name: Jira Cloud REST API - Get project role by ID
  x-api-slug: api2roleid-get
  description: |-
    Gets the project role details and the default actors associated with the role. The list of default actors is sorted by display name.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-get-openapi.md
- name: Jira Cloud REST API - Get project role by ID
  x-api-slug: api2roleid-get
  description: |-
    Gets the project role details and the default actors associated with the role. The list of default actors is sorted by display name.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2roleid-get-openapi.md
- name: Jira Cloud REST API - Create project role
  x-api-slug: api2role-post
  description: |-
    Creates a new project role with no [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get). You can use the [Add default actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-post) the project method to add default actors to the project role after creating it.

    _Note that although a new project role is available to all projects upon creation, any default actors that are associated with the project role are not added to projects that existed prior to the role being created._<

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-post-openapi.md
- name: Jira Cloud REST API - Create project role
  x-api-slug: api2role-post
  description: |-
    Creates a new project role with no [default actors](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-resolution-get). You can use the [Add default actors to project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-post) the project method to add default actors to the project role after creating it.

    _Note that although a new project role is available to all projects upon creation, any default actors that are associated with the project role are not added to projects that existed prior to the role being created._<

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-post-openapi.md
- name: Jira Cloud REST API - Get all project roles
  x-api-slug: api2role-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-openapi.md
- name: Jira Cloud REST API - Get all project roles
  x-api-slug: api2role-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2role-get-openapi.md
- name: Jira Cloud REST API - Get valid project name
  x-api-slug: api2projectvalidatevalidprojectname-get
  description: Validates a project name. If the name is invalid, an attempt is made
    to produce a valid name based on the supplied one. If no such valid name can be
    found, an empty string is returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-openapi.md
- name: Jira Cloud REST API - Get valid project name
  x-api-slug: api2projectvalidatevalidprojectname-get
  description: Validates a project name. If the name is invalid, an attempt is made
    to produce a valid name based on the supplied one. If no such valid name can be
    found, an empty string is returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectname-get-openapi.md
- name: Jira Cloud REST API - Get valid project key
  x-api-slug: api2projectvalidatevalidprojectkey-get
  description: Validates the project key and generated a valid project key if the
    supplied key is invalid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-openapi.md
- name: Jira Cloud REST API - Get valid project key
  x-api-slug: api2projectvalidatevalidprojectkey-get
  description: Validates the project key and generated a valid project key if the
    supplied key is invalid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatevalidprojectkey-get-openapi.md
- name: Jira Cloud REST API - Validate project key
  x-api-slug: api2projectvalidatekey-get
  description: Validates a project key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatekey-get-openapi.md
- name: Jira Cloud REST API - Validate project key
  x-api-slug: api2projectvalidatekey-get
  description: Validates a project key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectvalidatekey-get-openapi.md
- name: Jira Cloud REST API - Remove project category
  x-api-slug: api2projectcategoryid-delete
  description: Delete a project category.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-delete-openapi.md
- name: Jira Cloud REST API - Remove project category
  x-api-slug: api2projectcategoryid-delete
  description: Delete a project category.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-delete-openapi.md
- name: Jira Cloud REST API - Update project category
  x-api-slug: api2projectcategoryid-put
  description: Modify a project category via PUT. Any fields present in the PUT will
    override existing values. As a convenience, if a field is not present, it is silently
    ignored.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-put-openapi.md
- name: Jira Cloud REST API - Update project category
  x-api-slug: api2projectcategoryid-put
  description: Modify a project category via PUT. Any fields present in the PUT will
    override existing values. As a convenience, if a field is not present, it is silently
    ignored.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-put-openapi.md
- name: Jira Cloud REST API - Get project category by id
  x-api-slug: api2projectcategoryid-get
  description: Contains a representation of a project category in JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-openapi.md
- name: Jira Cloud REST API - Get project category by id
  x-api-slug: api2projectcategoryid-get
  description: Contains a representation of a project category in JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-openapi.md
- name: Jira Cloud REST API - Get project category by id
  x-api-slug: api2projectcategoryid-get
  description: Contains a representation of a project category in JSON format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategoryid-get-openapi.md
- name: Jira Cloud REST API - Create project category
  x-api-slug: api2projectcategory-post
  description: Create a project category via POST.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-openapi.md
- name: Jira Cloud REST API - Create project category
  x-api-slug: api2projectcategory-post
  description: Create a project category via POST.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-openapi.md
- name: Jira Cloud REST API - Create project category
  x-api-slug: api2projectcategory-post
  description: Create a project category via POST.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-openapi.md
- name: Jira Cloud REST API - Create project category
  x-api-slug: api2projectcategory-post
  description: Create a project category via POST.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-post-openapi.md
- name: Jira Cloud REST API - Get all project categories
  x-api-slug: api2projectcategory-get
  description: Returns all project categories
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-openapi.md
- name: Jira Cloud REST API - Get all project categories
  x-api-slug: api2projectcategory-get
  description: Returns all project categories
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-openapi.md
- name: Jira Cloud REST API - Get all project categories
  x-api-slug: api2projectcategory-get
  description: Returns all project categories
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-openapi.md
- name: Jira Cloud REST API - Get all project categories
  x-api-slug: api2projectcategory-get
  description: Returns all project categories
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectcategory-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get project notification scheme
  x-api-slug: api2projectprojectkeyoridnotificationscheme-get
  description: |-
    Gets a [notification scheme](https://confluence.atlassian.com/x/8YdKLg) associated with the project. See the [Get notification scheme](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-notificationscheme-id-get) resource for more information about notification schemes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-openapi.md
- name: Jira Cloud REST API - Get project notification scheme
  x-api-slug: api2projectprojectkeyoridnotificationscheme-get
  description: |-
    Gets a [notification scheme](https://confluence.atlassian.com/x/8YdKLg) associated with the project. See the [Get notification scheme](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-notificationscheme-id-get) resource for more information about notification schemes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridnotificationscheme-get-openapi.md
- name: Jira Cloud REST API - Get project issue security scheme
  x-api-slug: api2projectprojectkeyoridissuesecuritylevelscheme-get
  description: |-
    Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or the _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-openapi.md
- name: Jira Cloud REST API - Get project versions
  x-api-slug: api2projectprojectidorkeyversions-get
  description: |-
    Returns all versions existing in a single project. The response is not paginated. Use [Get project versions paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-version-get) if you want to get the versions in a project with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversions-get-openapi.md
- name: Jira Cloud REST API - Get project versions paginated
  x-api-slug: api2projectprojectidorkeyversion-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all versions existing in a single project. See the [Get project versions](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-versions-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-openapi.md
- name: Jira Cloud REST API - Get project versions paginated
  x-api-slug: api2projectprojectidorkeyversion-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all versions existing in a single project. See the [Get project versions](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-versions-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyversion-get-openapi.md
- name: Jira Cloud REST API - Update project type
  x-api-slug: api2projectprojectidorkeytypenewprojecttypekey-put
  description: |-
    Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-openapi.md
- name: Jira Cloud REST API - Update project type
  x-api-slug: api2projectprojectidorkeytypenewprojecttypekey-put
  description: |-
    Updates the [project type](https://confluence.atlassian.com/x/GwiiLQ).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeytypenewprojecttypekey-put-openapi.md
- name: Jira Cloud REST API - Get project role details
  x-api-slug: api2projectprojectidorkeyroledetails-get
  description: Returns all [project roles](https://confluence.atlassian.com/x/3odKLg)
    and the details for each role. Note that the list of project roles is common to
    all projects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-openapi.md
- name: Jira Cloud REST API - Get project role details
  x-api-slug: api2projectprojectidorkeyroledetails-get
  description: Returns all [project roles](https://confluence.atlassian.com/x/3odKLg)
    and the details for each role. Note that the list of project roles is common to
    all projects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-openapi.md
- name: Jira Cloud REST API - Get project role details
  x-api-slug: api2projectprojectidorkeyroledetails-get
  description: Returns all [project roles](https://confluence.atlassian.com/x/3odKLg)
    and the details for each role. Note that the list of project roles is common to
    all projects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroledetails-get-openapi.md
- name: Jira Cloud REST API - Delete actors from project role
  x-api-slug: api2projectprojectidorkeyroleid-delete
  description: |-
    Deletes actors from a project role for the project.

    If you want to remove default actors from the project role, see the [Delete default actors from project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-delete) resource.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-openapi.md
- name: Jira Cloud REST API - Delete actors from project role
  x-api-slug: api2projectprojectidorkeyroleid-delete
  description: |-
    Deletes actors from a project role for the project.

    If you want to remove default actors from the project role, see the [Delete default actors from project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-delete) resource.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-openapi.md
- name: Jira Cloud REST API - Delete actors from project role
  x-api-slug: api2projectprojectidorkeyroleid-delete
  description: |-
    Deletes actors from a project role for the project.

    If you want to remove default actors from the project role, see the [Delete default actors from project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-id-actors-delete) resource.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-delete-openapi.md
- name: Jira Cloud REST API - Add actors to project role
  x-api-slug: api2projectprojectidorkeyroleid-post
  description: |-
    Adds additional actors to a project role for the project.

    If you want to replace all actors for the project, then use [Set actors for project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-put).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-openapi.md
- name: Jira Cloud REST API - Add actors to project role
  x-api-slug: api2projectprojectidorkeyroleid-post
  description: |-
    Adds additional actors to a project role for the project.

    If you want to replace all actors for the project, then use [Set actors for project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-put).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-openapi.md
- name: Jira Cloud REST API - Add actors to project role
  x-api-slug: api2projectprojectidorkeyroleid-post
  description: |-
    Adds additional actors to a project role for the project.

    If you want to replace all actors for the project, then use [Set actors for project role](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-role-id-put).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-post-openapi.md
- name: Jira Cloud REST API - Get project role for project
  x-api-slug: api2projectprojectidorkeyroleid-get
  description: |-
    Returns the project role's details and actors associated with the project. The list of actors is sorted by display name.

    If you would like to check to see whether a user belongs to a role based on their group memberships, use the [Get user](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-user-get) resource with the `groups` expand parameter selected. Then check whether the user keys and groups match with the actors returned for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-openapi.md
- name: Jira Cloud REST API - Get project role for project
  x-api-slug: api2projectprojectidorkeyroleid-get
  description: |-
    Returns the project role's details and actors associated with the project. The list of actors is sorted by display name.

    If you would like to check to see whether a user belongs to a role based on their group memberships, use the [Get user](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-user-get) resource with the `groups` expand parameter selected. Then check whether the user keys and groups match with the actors returned for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-openapi.md
- name: Jira Cloud REST API - Get project role for project
  x-api-slug: api2projectprojectidorkeyroleid-get
  description: |-
    Returns the project role's details and actors associated with the project. The list of actors is sorted by display name.

    If you would like to check to see whether a user belongs to a role based on their group memberships, use the [Get user](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-user-get) resource with the `groups` expand parameter selected. Then check whether the user keys and groups match with the actors returned for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyroleid-get-openapi.md
- name: Jira Cloud REST API - Get project roles for project
  x-api-slug: api2projectprojectidorkeyrole-get
  description: |-
    Returns a list of [project roles](https://confluence.atlassian.com/x/3odKLg) for the project.

    Note that all project roles are shared with all projects in Jira Cloud. See the [Get all project roles](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-get) resource for more information.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-openapi.md
- name: Jira Cloud REST API - Get project roles for project
  x-api-slug: api2projectprojectidorkeyrole-get
  description: |-
    Returns a list of [project roles](https://confluence.atlassian.com/x/3odKLg) for the project.

    Note that all project roles are shared with all projects in Jira Cloud. See the [Get all project roles](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-get) resource for more information.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-openapi.md
- name: Jira Cloud REST API - Get project roles for project
  x-api-slug: api2projectprojectidorkeyrole-get
  description: |-
    Returns a list of [project roles](https://confluence.atlassian.com/x/3odKLg) for the project.

    Note that all project roles are shared with all projects in Jira Cloud. See the [Get all project roles](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-role-get) resource for more information.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyrole-get-openapi.md
- name: Jira Cloud REST API - Delete project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-delete
  description: |-
    Removes the [property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) from the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Set project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). You can use project properties to store custom data against the project.

    The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 bytes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Get project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-get
  description: |-
    Returns the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Get project property keys
  x-api-slug: api2projectprojectidorkeyproperties-get
  description: |-
    Returns all [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get project property keys
  x-api-slug: api2projectprojectidorkeyproperties-get
  description: |-
    Returns all [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get project property keys
  x-api-slug: api2projectprojectidorkeyproperties-get
  description: |-
    Returns all [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys for the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get project components
  x-api-slug: api2projectprojectidorkeycomponents-get
  description: |-
    Returns all components existing in a single project. See the [Get project components paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-component-get) resource if you want to get a full list of components with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-openapi.md
- name: Jira Cloud REST API - Get project components
  x-api-slug: api2projectprojectidorkeycomponents-get
  description: |-
    Returns all components existing in a single project. See the [Get project components paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-component-get) resource if you want to get a full list of components with pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponents-get-openapi.md
- name: Jira Cloud REST API - Get project components paginated
  x-api-slug: api2projectprojectidorkeycomponent-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all components existing in a single project. See the [Get project components](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-components-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-openapi.md
- name: Jira Cloud REST API - Get project components paginated
  x-api-slug: api2projectprojectidorkeycomponent-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) representation of all components existing in a single project. See the [Get project components](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-project-projectIdOrKey-components-get) resource if you want to get a full list of versions without pagination.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeycomponent-get-openapi.md
- name: Jira Cloud REST API - Get all project avatars
  x-api-slug: api2projectprojectidorkeyavatars-get
  description: Returns all project avatars visible for the currently logged in user.
    The avatars are grouped into system avatars and custom avatars.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatars-get-openapi.md
- name: Jira Cloud REST API - Get all project avatars
  x-api-slug: api2projectprojectidorkeyavatars-get
  description: Returns all project avatars visible for the currently logged in user.
    The avatars are grouped into system avatars and custom avatars.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatars-get-openapi.md
- name: Jira Cloud REST API - Create project avatar
  x-api-slug: api2projectprojectidorkeyavatar2-post
  description: Creates an avatar for a single project. Use it to upload an image to
    be be set as a project's avatar. The uploaded image will be cropped according
    to the crop parameters defined in the request. If no crop parameters are specified,
    the image will be cropped to a square. The square will originate at the top left
    of the image and the length of each side will be set to the smaller of the height
    or width of the image.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar2-post-openapi.md
- name: Jira Cloud REST API - Create project avatar
  x-api-slug: api2projectprojectidorkeyavatar2-post
  description: Creates an avatar for a single project. Use it to upload an image to
    be be set as a project's avatar. The uploaded image will be cropped according
    to the crop parameters defined in the request. If no crop parameters are specified,
    the image will be cropped to a square. The square will originate at the top left
    of the image and the length of each side will be set to the smaller of the height
    or width of the image.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar2-post-openapi.md
- name: Jira Cloud REST API - Delete project avatar
  x-api-slug: api2projectprojectidorkeyavatarid-delete
  description: Deletes an avatar of a single project. It is only possible to delete
    custom avatars.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatarid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatarid-delete-openapi.md
- name: Jira Cloud REST API - Delete project avatar
  x-api-slug: api2projectprojectidorkeyavatarid-delete
  description: Deletes an avatar of a single project. It is only possible to delete
    custom avatars.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatarid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatarid-delete-openapi.md
- name: Jira Cloud REST API - Update project avatar
  x-api-slug: api2projectprojectidorkeyavatar-put
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar-put-openapi.md
- name: Jira Cloud REST API - Update project avatar
  x-api-slug: api2projectprojectidorkeyavatar-put
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkeyavatar-put-openapi.md
- name: Jira Cloud REST API - Delete project
  x-api-slug: api2projectprojectidorkey-delete
  description: |-
    Deletes an existing project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-delete-openapi.md
- name: Jira Cloud REST API - Delete project
  x-api-slug: api2projectprojectidorkey-delete
  description: |-
    Deletes an existing project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-delete-openapi.md
- name: Jira Cloud REST API - Update project
  x-api-slug: api2projectprojectidorkey-put
  description: |-
    Updates the [project details](https://confluence.atlassian.com/x/ahLpNw) of an existing project.

    All parameters are optional in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-put-openapi.md
- name: Jira Cloud REST API - Update project
  x-api-slug: api2projectprojectidorkey-put
  description: |-
    Updates the [project details](https://confluence.atlassian.com/x/ahLpNw) of an existing project.

    All parameters are optional in the body of the request.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-put-openapi.md
- name: Jira Cloud REST API - Get project
  x-api-slug: api2projectprojectidorkey-get
  description: |-
    Returns the [project details](https://confluence.atlassian.com/x/ahLpNw) for the specified project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-openapi.md
- name: Jira Cloud REST API - Get project
  x-api-slug: api2projectprojectidorkey-get
  description: |-
    Returns the [project details](https://confluence.atlassian.com/x/ahLpNw) for the specified project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Browse Projects_ project permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projectprojectidorkey-get-openapi.md
- name: Jira Cloud REST API - Get accessible project type by key
  x-api-slug: api2projecttypeprojecttypekeyaccessible-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-openapi.md
- name: Jira Cloud REST API - Get accessible project type by key
  x-api-slug: api2projecttypeprojecttypekeyaccessible-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekeyaccessible-get-openapi.md
- name: Jira Cloud REST API - Get project type by key
  x-api-slug: api2projecttypeprojecttypekey-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekey-get-openapi.md
- name: Jira Cloud REST API - Get project type by key
  x-api-slug: api2projecttypeprojecttypekey-get
  description: |-
    Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttypeprojecttypekey-get-openapi.md
- name: Jira Cloud REST API - Get all project types
  x-api-slug: api2projecttype-get
  description: |-
    Returns all [project types](https://confluence.atlassian.com/x/Var1Nw), whether or not the instance has a valid license for each type.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttype-get-openapi.md
- name: Jira Cloud REST API - Get all project types
  x-api-slug: api2projecttype-get
  description: |-
    Returns all [project types](https://confluence.atlassian.com/x/Var1Nw), whether or not the instance has a valid license for each type.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira (that is, member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2projecttype-get-openapi.md
- name: Jira Cloud REST API - Create project
  x-api-slug: api2project-post
  description: |-
    Creates a new project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-post-openapi.md
- name: Jira Cloud REST API - Create project
  x-api-slug: api2project-post
  description: |-
    Creates a new project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/atlassian/api2project-post-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---