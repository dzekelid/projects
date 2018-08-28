---
swagger: "2.0"
x-collection-name: Google Cloud DNS
x-complete: 0
info:
  title: Google Cloud DNS API Get Project
  description: Fetch the representation of an existing Project.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /dns/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}:
    get:
      summary: Get Project
      description: Fetch the representation of an existing Project.
      operationId: dns.projects.get
      x-api-path-slug: project-get
      parameters:
      - in: path
        name: project
        description: Identifies the project addressed by this request
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