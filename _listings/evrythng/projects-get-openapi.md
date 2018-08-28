---
swagger: "2.0"
x-collection-name: EVRYTHNG
x-complete: 0
info:
  title: EVRYTHNG /projects/ (O)
  description: OPERATOR reads the list of all Projects.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{PROJECT_ID}/applications/:
    post:
      summary: /applications/ (O)
      description: OPERATOR creates a new application.
      operationId: ProjectsApplicationsByPROJECTIDPost
      x-api-path-slug: projectsproject-idapplications-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: PROJECT_ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - PROJECT
      - ID
      - Applications
  /projects/{PROJECT_ID}:
    get:
      summary: /projects/{id} (O)
      description: OPERATOR Reads a Specific Project.
      operationId: ProjectsByPROJECTIDGet
      x-api-path-slug: projectsproject-id-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: PROJECT_ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - PROJECT
      - ID
  /projects/:
    get:
      summary: /projects/ (O)
      description: OPERATOR reads the list of all Projects.
      operationId: ProjectsGet
      x-api-path-slug: projects-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
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