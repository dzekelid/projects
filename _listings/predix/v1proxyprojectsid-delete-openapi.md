---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix SAS ESP Predix Service Delete project.
  description: API to delete project from ESP server.
  contact:
    name: zahid.iqbal2@ge.com
  version: 1.0.0
host: sas-proxy.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/proxy/projects/{id}:
    put:
      summary: Load/Create Project
      description: API to Load/Create project in ESP server.
      operationId: loadOrCreateProjectUsingPUT
      x-api-path-slug: v1proxyprojectsid-put
      parameters:
      - in: body
        name: reqBody
        description: reqBody
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Load
      - Project
    delete:
      summary: Delete project.
      description: API to delete project from ESP server.
      operationId: deleteProjectUsingDELETE
      x-api-path-slug: v1proxyprojectsid-delete
      parameters:
      - in: body
        name: reqBody
        description: reqBody
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Project
  /v1/proxy/projects/{id}/state:
    put:
      summary: Update project status
      description: API to update project status etc. started, running, stopped
      operationId: projectStatusUsingPUT
      x-api-path-slug: v1proxyprojectsidstate-put
      parameters:
      - in: body
        name: reqBody
        description: reqBody
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Project
      - Status
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