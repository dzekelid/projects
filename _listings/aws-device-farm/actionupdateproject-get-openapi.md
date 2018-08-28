---
swagger: "2.0"
x-collection-name: AWS Device Farm
x-complete: 0
info:
  title: AWS Device Farm API Update Project
  version: 1.0.0
  description: Modifies the specified project name, given the project ARN and a new
    name.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteProject:
    get:
      summary: Delete Project
      description: Deletes an AWS Device Farm project, given the project ARN.
      operationId: deleteProject
      x-api-path-slug: actiondeleteproject-get
      parameters:
      - in: query
        name: arn
        description: Represents the Amazon Resource Name (ARN) of the Device Farm
          project you wish to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=GetProject:
    get:
      summary: Get Project
      description: Gets information about a project.
      operationId: getProject
      x-api-path-slug: actiongetproject-get
      parameters:
      - in: query
        name: arn
        description: The projects ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=ListProjects:
    get:
      summary: List Projects
      description: Gets information about projects.
      operationId: listProjects
      x-api-path-slug: actionlistprojects-get
      parameters:
      - in: query
        name: arn
        description: Optional
        type: string
      - in: query
        name: nextToken
        description: An identifier that was returned from the previous call to this
          operation, which can be used to return the next set of items in the list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=UpdateProject:
    get:
      summary: Update Project
      description: Modifies the specified project name, given the project ARN and
        a new name.
      operationId: updateProject
      x-api-path-slug: actionupdateproject-get
      parameters:
      - in: query
        name: arn
        description: The Amazon Resource Name (ARN) of the project whose name you
          wish to update
        type: string
      - in: query
        name: name
        description: A string representing the new name of the project that you are
          updating
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=CreateProject:
    get:
      summary: Create Project
      description: Creates a new project.
      operationId: createProject
      x-api-path-slug: actioncreateproject-get
      parameters:
      - in: query
        name: name
        description: The projects name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Project
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