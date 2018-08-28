---
swagger: "2.0"
info:
  title: AWS Device Farm API Get Project
  version: 1.0.0
  description: Gets information about a project.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetProject:
    get:
      summary: ' Get Project '
      description: Gets information about a project
      operationId: getProject
      parameters:
      - in: query
        name: arn
        description: The project's ARN
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