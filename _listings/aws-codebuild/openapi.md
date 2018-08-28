swagger: "2.0"
x-collection-name: AWS CodeBuild
x-complete: 1
info:
  title: AWS CodeBuild API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=BatchGetProjects:
    get:
      summary: Batch Get Projects
      description: Gets information about one or more build projects.
      operationId: batchGetProjects
      x-api-path-slug: actionbatchgetprojects-get
      parameters:
      - in: query
        name: names
        description: The names of the build projects to get information about
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=CreateProject:
    get:
      summary: Create Project
      description: Creates a build project.
      operationId: createProject
      x-api-path-slug: actioncreateproject-get
      parameters:
      - in: query
        name: artifacts
        description: Information about the build projects build output artifacts
        type: string
      - in: query
        name: description
        description: A meaningful description of the build project
        type: string
      - in: query
        name: encryptionKey
        description: The AWS Key Management Service (AWS KMS) customer master key
          (CMK) to be used for encrypting the build projects build output artifacts
        type: string
      - in: query
        name: environment
        description: Information about the build projects build environment
        type: string
      - in: query
        name: name
        description: The build projects name
        type: string
      - in: query
        name: serviceRole
        description: The Amazon Resource Name (ARN) of the AWS Identity and Access
          Management (IAM) role that enables AWS CodeBuild to interact with dependent
          AWS services on behalf of the AWS account
        type: string
      - in: query
        name: source
        description: Information about the build projects build input source code
        type: string
      - in: query
        name: tags
        description: A set of tags for this build project
        type: string
      - in: query
        name: timeoutInMinutes
        description: How long in minutes, from 5 to 480 (8 hours), for AWS CodeBuild
          to wait until timing out any related build that does not get marked as completed
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=DeleteProject:
    get:
      summary: Delete Project
      description: Deletes a build project.
      operationId: deleteProject
      x-api-path-slug: actiondeleteproject-get
      parameters:
      - in: query
        name: name
        description: The name of the build project to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=ListProjects:
    get:
      summary: List Projects
      description: Gets a list of build project names, with each build project name
        representing a single build project.
      operationId: listProjects
      x-api-path-slug: actionlistprojects-get
      parameters:
      - in: query
        name: nextToken
        description: During a previous call, if there are more than 100 items in the
          list, only the first 100 items are returned, along with a unique string
          called a next token
        type: string
      - in: query
        name: sortBy
        description: The criterion to be used to list build project names
        type: string
      - in: query
        name: sortOrder
        description: The order in which to list build projects
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=UpdateProject:
    get:
      summary: Update Project
      description: Changes the settings of an existing build project.
      operationId: updateProject
      x-api-path-slug: actionupdateproject-get
      parameters:
      - in: query
        name: artifacts
        description: Information to be changed about the build projects build output
          artifacts
        type: string
      - in: query
        name: description
        description: A new or replacement description of the build project
        type: string
      - in: query
        name: encryptionKey
        description: The replacement AWS Key Management Service (AWS KMS) customer
          master key (CMK) to be used for encrypting the build projects build output
          artifacts
        type: string
      - in: query
        name: environment
        description: Information to be changed about the build projects build environment
        type: string
      - in: query
        name: name
        description: The name of the existing build project to change settings
        type: string
      - in: query
        name: serviceRole
        description: The replacement Amazon Resource Name (ARN) of the AWS Identity
          and Access Management (IAM) role that enables AWS CodeBuild to interact
          with dependent AWS services on behalf of the AWS account
        type: string
      - in: query
        name: source
        description: Information to be changed about the build projects build input
          source code
        type: string
      - in: query
        name: tags
        description: The replacement set of tags for this build project
        type: string
      - in: query
        name: timeoutInMinutes
        description: The replacement value in minutes, from 5 to 480 (8 hours), for
          AWS CodeBuild to wait to timeout any related build that did not get marked
          as completed
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=ListBuildsForProject:
    get:
      summary: List Builds For Project
      description: Gets a list of build IDs for the specified build project, with
        each build ID representing a single build.
      operationId: listBuildsForProject
      x-api-path-slug: actionlistbuildsforproject-get
      parameters:
      - in: query
        name: nextToken
        description: During a previous call, if there are more than 100 items in the
          list, only the first 100 items are returned, along with a unique string
          called a next token
        type: string
      - in: query
        name: projectName
        description: The name of the build project to get a list of build IDs for
        type: string
      - in: query
        name: sortOrder
        description: The order to list build IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Project Builds