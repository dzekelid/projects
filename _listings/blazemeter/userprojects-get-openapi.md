---
swagger: "2.0"
x-collection-name: BlazeMeter
x-complete: 0
info:
  title: Blazemeter Get User Projects
  description: Get user projects.
  version: 1.0.0
host: a.blazemeter.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/projects:
    get:
      summary: Get User Projects
      description: Get user projects.
      operationId: retrieveProjects
      x-api-path-slug: userprojects-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - User
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