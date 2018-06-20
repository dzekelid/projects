---
swagger: "2.0"
x-collection-name: Learnifier
x-complete: 0
info:
  title: Learnifier Gets Organization Unit by external id
  version: 1.1.0
  description: Gets an Organization Unit by external id
host: learnifier.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /extproject:
    get:
      summary: Gets Organization Unit by external id
      description: Gets an Organization Unit by external id
      operationId: extproject.get
      x-api-path-slug: extproject-get
      parameters:
      - in: query
        name: extid
        description: The external id of the organization unit
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