---
swagger: "2.0"
x-collection-name: AWS CodeBuild
x-complete: 0
info:
  title: AWS CodeBuild API Create Project
  version: 1.0.0
  description: Creates a build project.
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