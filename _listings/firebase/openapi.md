swagger: "2.0"
x-collection-name: Firebase
x-complete: 1
info:
  title: Firebase
  description: you-can-use-any-firebase-database-url-as-a-rest-endpoint--all-you-need-to-do-is-append--json-to-the-end-of-the-url-and-send-a-request-from-your-favorite-https-client-
  version: 1.0.0
host: '{project_id].firebaseio.co}'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{projectId}/settings:
    get:
      summary: Get Project Settings
      description: |-
        Gets the Tool Results settings for a project.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to read from project
      operationId: toolresults.projects.getSettings
      x-api-path-slug: projectidsettings-get
      parameters:
      - in: path
        name: projectId
        description: A Project id
      responses:
        200:
          description: OK
      tags:
      - Project
  /{projectId}:initializeSettings:
    post:
      summary: Initialize Settings
      description: |-
        Creates resources for settings which have not yet been set.

        Currently, this creates a single resource: a Google Cloud Storage bucket, to be used as the default bucket for this project. The bucket is created in the name of the user calling. Except in rare cases, calling this method in parallel from multiple clients will only create a single bucket. In order to avoid unnecessary storage charges, the bucket is configured to automatically delete objects older than 90 days.

        The bucket is created with the project-private ACL: All project team members are given permissions to the bucket and objects created within it according to their roles. Project owners have owners rights, and so on. The default ACL on objects created in the bucket is project-private as well. See Google Cloud Storage documentation for more details.

        If there is already a default bucket set and the project can access the bucket, this call does nothing. However, if the project doesn't have the permission to access the bucket or the bucket is deteleted, a new bucket will be created.

        May return any canonical error codes, including the following:

        - PERMISSION_DENIED - if the user is not authorized to write to project - Any error code raised by Google Cloud Storage
      operationId: toolresults.projects.initializeSettings
      x-api-path-slug: projectidinitializesettings-post
      parameters:
      - in: path
        name: projectId
        description: A Project id
      responses:
        200:
          description: OK
      tags:
      - Project