swagger: "2.0"
x-collection-name: EVRYTHNG
x-complete: 1
info:
  title: EVRYTHNG
  description: the-evrythng-platform-is-a-cloud-platformasaservice-paas-for-storing-sharing-and-analyzing-data-generated-by-physical-objects--the-platform-gives-a-unique-and-permanent-digital-identity-also-known-as-adis-to-each-individual-object-and-allows-authorized-applications-and-users-to-access-it-via-rest-and-pubsub-mqtt-apis--visualisations-in-the-evrythng-dashboard-analytics-conditional-redirections-and-the-reactor-rules-engine-provide-means-to-add-intelligent-behavior-and-features-on-top-of-your-data-to-add-value-
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
    post:
      summary: /projects/ (O)
      description: OPERATOR creates a new project.
      operationId: ProjectsPost
      x-api-path-slug: projects-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Projects
  /projects/{PROJECT_ID}/applications/{APP_ID}:
    get:
      summary: /applications/{id} (O)
      description: OPERATOR reads a specific application.
      operationId: ProjectsApplicationsByPROJECTIDAndAPPIDGet
      x-api-path-slug: projectsproject-idapplicationsapp-id-get
      parameters:
      - in: header
        name: Accept
      - in: path
        name: APP_ID
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
      - APP
      - ID