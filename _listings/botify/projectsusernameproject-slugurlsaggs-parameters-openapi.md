---
swagger: "2.0"
x-collection-name: Botify
x-complete: 0
info:
  title: Botify Parameters Projects Username Project Slug Urls Aggs
  description: Parameters projects username project slug urls aggs.
  version: 1.0.0
host: api.botify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{username}:
    get:
      summary: Get Projects Username
      description: List all active projects for the user
      operationId: getProjectsUsername
      x-api-path-slug: projectsusername-get
      parameters:
      - in: query
        name: name
        description: Projects name
      - in: query
        name: page
        description: Page Number
      - in: query
        name: size
        description: Page Size
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
    parameters:
      summary: Parameters Projects Username
      description: Parameters projects username.
      operationId: parametersProjectsUsername
      x-api-path-slug: projectsusername-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
  /projects/{username}/{project_slug}/filters:
    get:
      summary: Get Projects Username Project Slug Filters
      description: List all the project's saved filters (each filter's name, ID and
        filter value)
      operationId: getProjectsUsernameProjectSlugFilters
      x-api-path-slug: projectsusernameproject-slugfilters-get
      parameters:
      - in: query
        name: page
        description: Page Number
      - in: query
        name: size
        description: Page Size
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
      - Project
      - Slug
      - Filters
    parameters:
      summary: Parameters Projects Username Project Slug Filters
      description: Parameters projects username project slug filters.
      operationId: parametersProjectsUsernameProjectSlugFilters
      x-api-path-slug: projectsusernameproject-slugfilters-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
      - Project
      - Slug
      - Filters
  /projects/{username}/{project_slug}/filters/{identifier}:
    get:
      summary: Get Projects Username Project Slug Filters Entifier
      description: Retrieves a specific saved filter's name, ID and filter value
      operationId: getProjectsUsernameProjectSlugFiltersEntifier
      x-api-path-slug: projectsusernameproject-slugfiltersidentifier-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
      - Project
      - Slug
      - Filters
      - Identifier
    parameters:
      summary: Parameters Projects Username Project Slug Filters Entifier
      description: Parameters projects username project slug filters entifier.
      operationId: parametersProjectsUsernameProjectSlugFiltersEntifier
      x-api-path-slug: projectsusernameproject-slugfiltersidentifier-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
      - Project
      - Slug
      - Filters
      - Identifier
  /projects/{username}/{project_slug}/urls/aggs:
    parameters:
      summary: Parameters Projects Username Project Slug Urls Aggs
      description: Parameters projects username project slug urls aggs.
      operationId: parametersProjectsUsernameProjectSlugUrlsAggs
      x-api-path-slug: projectsusernameproject-slugurlsaggs-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Username
      - Project
      - Slug
      - Urls
      - Aggs
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