---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get permitted projects
  description: Returns all projects where currently logged in user was granted ALL
    requested project permissions.
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