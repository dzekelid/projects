---
swagger: "2.0"
x-collection-name: MotaWord
x-complete: 0
info:
  title: Mota Word Delete a project
  description: Delete(cancel) a project.
  version: alpha-0.1.0
host: api.motaword.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects:
    get:
      summary: Get a list of your projects
      description: Get a list of your projects.
      operationId: getProjects
      x-api-path-slug: projects-get
      parameters:
      - in: query
        name: page
      - in: query
        name: per_page
      responses:
        200:
          description: OK
      tags:
      - Projects
    post:
      summary: Get a new quote
      description: Create a new project
      operationId: createProject
      x-api-path-slug: projects-post
      parameters:
      - in: formData
        name: callback_url
        description: Optional
      - in: formData
        name: custom
        description: Optional
      - in: formData
        name: documents[]
        description: Optional
      - in: formData
        name: glossaries[]
        description: Optional
      - in: formData
        name: source_language
      - in: formData
        name: styleguides[]
        description: Optional
      - in: formData
        name: target_languages[]
      responses:
        200:
          description: OK
      tags:
      - Projects
  /projects/{id}:
    delete:
      summary: Delete a project
      description: Delete(cancel) a project.
      operationId: deleteProject
      x-api-path-slug: projectsid-delete
      parameters:
      - in: path
        name: id
        description: Project ID
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