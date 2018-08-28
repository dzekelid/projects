---
swagger: "2.0"
x-collection-name: Hewlett Packard Enterprise (HPE)
x-complete: 0
info:
  title: HPE OneSphere API Patch Projects
  description: Updates a project. It requires the **administrator** global role or
    the **project owner** role on a project.
  termsOfService: http://www.hpe.com/onesphere
  contact:
    name: HPE OneSphere API team
    url: http://www.hpe.com/onesphere
  version: 1.0.0
host: deic02-hpe.hpeonesphere.com
basePath: /rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects:
    get:
      summary: Get Projects
      description: Returns projects. It requires any project role or non-'consumer'
        global role.
      operationId: FindProjects
      x-api-path-slug: projects-get
      parameters:
      - in: query
        name: userQuery
        description: Filters the projects returned
      - in: query
        name: view
        description: 'Return related resources:  * `full` - Any deployments in the
          project; any tags referred to by tagUris (**not implemented**)'
      responses:
        200:
          description: OK
      tags:
      - Projects
    post:
      summary: Post Projects
      description: Creates a new project. It requires the **project-owner** project
        role, or **administrator** or **project creator** global role.
      operationId: CreateProject
      x-api-path-slug: projects-post
      parameters:
      - in: body
        name: project
        description: Add new project
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
  /projects/{id}:
    delete:
      summary: Delete Projects
      description: Deletes a project. If resources (currently Deployments) exist within
        the project they must first be deleted. In this case, the response will be
        a 409 Conflict with the body listing the first ten offending items. It requires
        **administratpor** global role or **owner** project role. **not implemented**
      operationId: deletes-a-project-if-resources-currently-deployments-exist-within-the-project-they-must-first-be-del
      x-api-path-slug: projectsid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Projects
    get:
      summary: Get Projects
      description: Returns a project based on its id. It requires any project role
        or non-consumer global role.
      operationId: GetProjectById
      x-api-path-slug: projectsid-get
      parameters:
      - in: path
        name: id
        description: ID of project to fetch
      - in: query
        name: view
        description: 'Return related resources:  * `full` - Any deployments in the
          project; any tags referred to by tagUris (**not implemented**)'
      responses:
        200:
          description: OK
      tags:
      - Projects
    patch:
      summary: Patch Projects
      description: Updates a project. It requires the **administrator** global role
        or the **project owner** role on a project.
      operationId: UpdateProject
      x-api-path-slug: projectsid-patch
      parameters:
      - in: path
        name: id
        description: ID of project to update
      - in: body
        name: project
        description: Update project
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
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