---
swagger: "2.0"
x-collection-name: Google Cloud Billing
x-complete: 0
info:
  title: Google Cloud Billing API Get Projects
  description: |-
    Lists the projects associated with a billing account. The current
    authenticated user must be an [owner of the billing
    account](https://support.google.com/cloud/answer/4430947).
  contact:
    name: Google
    url: https://google.com
  version: v1
host: cloudbilling.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}/projects:
    get:
      summary: Get Projects
      description: |-
        Lists the projects associated with a billing account. The current
        authenticated user must be an [owner of the billing
        account](https://support.google.com/cloud/answer/4430947).
      operationId: cloudbilling.billingAccounts.projects.list
      x-api-path-slug: v1nameprojects-get
      parameters:
      - in: path
        name: name
        description: The resource name of the billing account associated with the
          projects thatyou want to list
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results to be returned
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