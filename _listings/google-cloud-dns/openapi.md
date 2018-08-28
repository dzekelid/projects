swagger: "2.0"
x-collection-name: Google Cloud DNS
x-complete: 1
info:
  title: Google Cloud DNS
  description: configures-and-serves-authoritative-dns-records-
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