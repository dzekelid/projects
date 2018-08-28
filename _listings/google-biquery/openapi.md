swagger: "2.0"
x-collection-name: Google Biquery
x-complete: 1
info:
  title: BigQuery
  description: a-data-platform-for-customers-to-create-manage-share-and-query-data-
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /bigquery/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects:
    get:
      summary: Get Projects
      description: Lists all projects to which you have been granted any project role.
      operationId: bigquery.projects.list
      x-api-path-slug: projects-get
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Page token, returned by a previous call, to request the next
          page of results
      responses:
        200:
          description: OK
      tags:
      - Project