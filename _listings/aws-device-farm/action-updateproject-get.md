---
swagger: "2.0"
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
  /?Action=UpdateProject:
    get:
      summary: ' Update Project '
      description: Modifies the specified project name, given the project ARN and
        a new name
      operationId: updateProject
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
      - projects
definitions: []
x-collection-name: AWS Device Farm
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