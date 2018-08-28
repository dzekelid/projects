swagger: "2.0"
x-collection-name: Google Cloud Billing
x-complete: 1
info:
  title: Google Cloud Billing
  description: allows-developers-to-manage-billing-for-their-google-cloud-platform-projects----programmatically-
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