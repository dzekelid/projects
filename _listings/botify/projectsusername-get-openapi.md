---
swagger: "2.0"
x-collection-name: Botify
x-complete: 0
info:
  title: Botify Get Projects Username
  description: List all active projects for the user
  version: 1.0.0
host: api.botify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{username}:
    get:
      summary: Get Projects Username
      description: List all active projects for the user
      operationId: getProjectsUsername
      x-api-path-slug: projectsusername-get
      parameters:
      - in: query
        name: name
        description: Projects name
      - in: query
        name: page
        description: Page Number
      - in: query
        name: size
        description: Page Size
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
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