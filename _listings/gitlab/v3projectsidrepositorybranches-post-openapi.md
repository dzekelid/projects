---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Post Projects Repository Branches
  version: 1.0.0
  description: Post projects repository branches.
host: localhost:3000
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/groups/{id}/projects:
    get:
      summary: Get Groups Projects
      description: Get a list of projects in this group.
      operationId: getV3GroupsIdProjects
      x-api-path-slug: v3groupsidprojects-get
      parameters:
      - in: query
        name: archived
        description: Limit by archived status
      - in: path
        name: id
        description: The ID of a group
      - in: query
        name: order_by
        description: Return projects ordered by field
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      - in: query
        name: search
        description: Return list of authorized projects matching the search criteria
      - in: query
        name: simple
        description: Return only the ID, URL, name, and path of each project
      - in: query
        name: sort
        description: Return projects sorted in ascending and descending order
      - in: query
        name: visibility
        description: Limit by visibility
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Projects
  /v3/groups/{id}/projects/{project_id}:
    post:
      summary: Post Groups Projects Project
      description: Transfer a project to the group namespace. Available only for admin.
      operationId: postV3GroupsIdProjectsProjectId
      x-api-path-slug: v3groupsidprojectsproject-id-post
      parameters:
      - in: path
        name: id
        description: The ID of a group
      - in: path
        name: project_id
        description: The ID or path of the project
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Projects
      - Project
  /v3/projects/{id}/access_requests:
    get:
      summary: Get Projects Access Requests
      description: This feature was introduced in GitLab 8.11.
      operationId: getV3ProjectsIdAccessRequests
      x-api-path-slug: v3projectsidaccess-requests-get
      parameters:
      - in: path
        name: id
        description: The project ID
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Access
      - Requests
    post:
      summary: Post Projects Access Requests
      description: This feature was introduced in GitLab 8.11.
      operationId: postV3ProjectsIdAccessRequests
      x-api-path-slug: v3projectsidaccess-requests-post
      parameters:
      - in: path
        name: id
        description: The project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Access
      - Requests
  /v3/projects/{id}/access_requests/{user_id}/approve:
    put:
      summary: Put Projects Access Requests User Approve
      description: This feature was introduced in GitLab 8.11.
      operationId: putV3ProjectsIdAccessRequestsUserIdApprove
      x-api-path-slug: v3projectsidaccess-requestsuser-idapprove-put
      parameters:
      - in: formData
        name: access_level
        description: 'A valid access level (defaults: `30`, developer access level)'
      - in: path
        name: id
        description: The project ID
      - in: path
        name: user_id
        description: The user ID of the access requester
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Access
      - Requests
      - User
      - Approve
  /v3/projects/{id}/access_requests/{user_id}:
    delete:
      summary: Delete Projects Access Requests User
      description: This feature was introduced in GitLab 8.11.
      operationId: deleteV3ProjectsIdAccessRequestsUserId
      x-api-path-slug: v3projectsidaccess-requestsuser-id-delete
      parameters:
      - in: path
        name: id
        description: The project ID
      - in: path
        name: user_id
        description: The user ID of the access requester
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Access
      - Requests
      - User
  /v3/projects/{id}/issues/{issue_id}/award_emoji:
    get:
      summary: Get Projects Issues Issue Award Emoji
      description: Get projects issues issue award emoji.
      operationId: getV3ProjectsIdIssuesIssueIdAwardEmoji
      x-api-path-slug: v3projectsidissuesissue-idaward-emoji-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: path
        name: issue_id
        description: The ID of an Issue, Merge Request or Snippet
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Award
      - Emoji
    post:
      summary: Post Projects Issues Issue Award Emoji
      description: Post projects issues issue award emoji.
      operationId: postV3ProjectsIdIssuesIssueIdAwardEmoji
      x-api-path-slug: v3projectsidissuesissue-idaward-emoji-post
      parameters:
      - in: path
        name: id
      - in: path
        name: issue_id
      - in: formData
        name: name
        description: The name of a award_emoji (without colons)
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Award
      - Emoji
  /v3/projects/{id}/issues/{issue_id}/award_emoji/{award_id}:
    get:
      summary: Get Projects Issues Issue Award Emoji Award
      description: Get projects issues issue award emoji award.
      operationId: getV3ProjectsIdIssuesIssueIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidissuesissue-idaward-emojiaward-id-get
      parameters:
      - in: path
        name: award_id
        description: The ID of the award
      - in: path
        name: id
      - in: path
        name: issue_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Award
      - Emoji
      - Award
    delete:
      summary: Delete Projects Issues Issue Award Emoji Award
      description: Delete projects issues issue award emoji award.
      operationId: deleteV3ProjectsIdIssuesIssueIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidissuesissue-idaward-emojiaward-id-delete
      parameters:
      - in: path
        name: award_id
        description: The ID of an award emoji
      - in: path
        name: id
      - in: path
        name: issue_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Award
      - Emoji
      - Award
  /v3/projects/{id}/issues/{issue_id}/notes/{note_id}/award_emoji:
    get:
      summary: Get Projects Issues Issue Notes Note Award Emoji
      description: Get projects issues issue notes note award emoji.
      operationId: getV3ProjectsIdIssuesIssueIdNotesNoteIdAwardEmoji
      x-api-path-slug: v3projectsidissuesissue-idnotesnote-idaward-emoji-get
      parameters:
      - in: path
        name: id
      - in: path
        name: issue_id
      - in: path
        name: note_id
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Notes
      - Note
      - Award
      - Emoji
    post:
      summary: Post Projects Issues Issue Notes Note Award Emoji
      description: Post projects issues issue notes note award emoji.
      operationId: postV3ProjectsIdIssuesIssueIdNotesNoteIdAwardEmoji
      x-api-path-slug: v3projectsidissuesissue-idnotesnote-idaward-emoji-post
      parameters:
      - in: path
        name: id
      - in: path
        name: issue_id
      - in: formData
        name: name
        description: The name of a award_emoji (without colons)
      - in: path
        name: note_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Notes
      - Note
      - Award
      - Emoji
  /v3/projects/{id}/issues/{issue_id}/notes/{note_id}/award_emoji/{award_id}:
    get:
      summary: Get Projects Issues Issue Notes Note Award Emoji Award
      description: Get projects issues issue notes note award emoji award.
      operationId: getV3ProjectsIdIssuesIssueIdNotesNoteIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidissuesissue-idnotesnote-idaward-emojiaward-id-get
      parameters:
      - in: path
        name: award_id
        description: The ID of the award
      - in: path
        name: id
      - in: path
        name: issue_id
      - in: path
        name: note_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Notes
      - Note
      - Award
      - Emoji
      - Award
    delete:
      summary: Delete Projects Issues Issue Notes Note Award Emoji Award
      description: Delete projects issues issue notes note award emoji award.
      operationId: deleteV3ProjectsIdIssuesIssueIdNotesNoteIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidissuesissue-idnotesnote-idaward-emojiaward-id-delete
      parameters:
      - in: path
        name: award_id
        description: The ID of an award emoji
      - in: path
        name: id
      - in: path
        name: issue_id
      - in: path
        name: note_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Issues
      - Issue
      - Notes
      - Note
      - Award
      - Emoji
      - Award
  /v3/projects/{id}/merge_requests/{merge_request_id}/award_emoji:
    get:
      summary: Get Projects Merge Requests Merge Request Award Emoji
      description: Get projects merge requests merge request award emoji.
      operationId: getV3ProjectsIdMergeRequestsMergeRequestIdAwardEmoji
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idaward-emoji-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: path
        name: merge_request_id
        description: The ID of an Issue, Merge Request or Snippet
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Award
      - Emoji
    post:
      summary: Post Projects Merge Requests Merge Request Award Emoji
      description: Post projects merge requests merge request award emoji.
      operationId: postV3ProjectsIdMergeRequestsMergeRequestIdAwardEmoji
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idaward-emoji-post
      parameters:
      - in: path
        name: id
      - in: path
        name: merge_request_id
      - in: formData
        name: name
        description: The name of a award_emoji (without colons)
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Award
      - Emoji
  /v3/projects/{id}/merge_requests/{merge_request_id}/award_emoji/{award_id}:
    get:
      summary: Get Projects Merge Requests Merge Request Award Emoji Award
      description: Get projects merge requests merge request award emoji award.
      operationId: getV3ProjectsIdMergeRequestsMergeRequestIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idaward-emojiaward-id-get
      parameters:
      - in: path
        name: award_id
        description: The ID of the award
      - in: path
        name: id
      - in: path
        name: merge_request_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Award
      - Emoji
      - Award
    delete:
      summary: Delete Projects Merge Requests Merge Request Award Emoji Award
      description: Delete projects merge requests merge request award emoji award.
      operationId: deleteV3ProjectsIdMergeRequestsMergeRequestIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idaward-emojiaward-id-delete
      parameters:
      - in: path
        name: award_id
        description: The ID of an award emoji
      - in: path
        name: id
      - in: path
        name: merge_request_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Award
      - Emoji
      - Award
  /v3/projects/{id}/merge_requests/{merge_request_id}/notes/{note_id}/award_emoji:
    get:
      summary: Get Projects Merge Requests Merge Request Notes Note Award Emoji
      description: Get projects merge requests merge request notes note award emoji.
      operationId: getV3ProjectsIdMergeRequestsMergeRequestIdNotesNoteIdAwardEmoji
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idnotesnote-idaward-emoji-get
      parameters:
      - in: path
        name: id
      - in: path
        name: merge_request_id
      - in: path
        name: note_id
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Notes
      - Note
      - Award
      - Emoji
    post:
      summary: Post Projects Merge Requests Merge Request Notes Note Award Emoji
      description: Post projects merge requests merge request notes note award emoji.
      operationId: postV3ProjectsIdMergeRequestsMergeRequestIdNotesNoteIdAwardEmoji
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idnotesnote-idaward-emoji-post
      parameters:
      - in: path
        name: id
      - in: path
        name: merge_request_id
      - in: formData
        name: name
        description: The name of a award_emoji (without colons)
      - in: path
        name: note_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Notes
      - Note
      - Award
      - Emoji
  /v3/projects/{id}/merge_requests/{merge_request_id}/notes/{note_id}/award_emoji/{award_id}:
    get:
      summary: Get Projects Merge Requests Merge Request Notes Note Award Emoji Award
      description: Get projects merge requests merge request notes note award emoji
        award.
      operationId: getV3ProjectsIdMergeRequestsMergeRequestIdNotesNoteIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idnotesnote-idaward-emojiaward-id-get
      parameters:
      - in: path
        name: award_id
        description: The ID of the award
      - in: path
        name: id
      - in: path
        name: merge_request_id
      - in: path
        name: note_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Notes
      - Note
      - Award
      - Emoji
      - Award
    delete:
      summary: Delete Projects Merge Requests Merge Request Notes Note Award Emoji
        Award
      description: Delete projects merge requests merge request notes note award emoji
        award.
      operationId: deleteV3ProjectsIdMergeRequestsMergeRequestIdNotesNoteIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidmerge-requestsmerge-request-idnotesnote-idaward-emojiaward-id-delete
      parameters:
      - in: path
        name: award_id
        description: The ID of an award emoji
      - in: path
        name: id
      - in: path
        name: merge_request_id
      - in: path
        name: note_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Merge
      - Requests
      - Merge
      - Request
      - Notes
      - Note
      - Award
      - Emoji
      - Award
  /v3/projects/{id}/snippets/{snippet_id}/award_emoji:
    get:
      summary: Get Projects Snippets Snippet Award Emoji
      description: Get projects snippets snippet award emoji.
      operationId: getV3ProjectsIdSnippetsSnippetIdAwardEmoji
      x-api-path-slug: v3projectsidsnippetssnippet-idaward-emoji-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      - in: path
        name: snippet_id
        description: The ID of an Issue, Merge Request or Snippet
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Snippets
      - Snippet
      - Award
      - Emoji
    post:
      summary: Post Projects Snippets Snippet Award Emoji
      description: Post projects snippets snippet award emoji.
      operationId: postV3ProjectsIdSnippetsSnippetIdAwardEmoji
      x-api-path-slug: v3projectsidsnippetssnippet-idaward-emoji-post
      parameters:
      - in: path
        name: id
      - in: formData
        name: name
        description: The name of a award_emoji (without colons)
      - in: path
        name: snippet_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Snippets
      - Snippet
      - Award
      - Emoji
  /v3/projects/{id}/snippets/{snippet_id}/award_emoji/{award_id}:
    get:
      summary: Get Projects Snippets Snippet Award Emoji Award
      description: Get projects snippets snippet award emoji award.
      operationId: getV3ProjectsIdSnippetsSnippetIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidsnippetssnippet-idaward-emojiaward-id-get
      parameters:
      - in: path
        name: award_id
        description: The ID of the award
      - in: path
        name: id
      - in: path
        name: snippet_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Snippets
      - Snippet
      - Award
      - Emoji
      - Award
    delete:
      summary: Delete Projects Snippets Snippet Award Emoji Award
      description: Delete projects snippets snippet award emoji award.
      operationId: deleteV3ProjectsIdSnippetsSnippetIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidsnippetssnippet-idaward-emojiaward-id-delete
      parameters:
      - in: path
        name: award_id
        description: The ID of an award emoji
      - in: path
        name: id
      - in: path
        name: snippet_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Snippets
      - Snippet
      - Award
      - Emoji
      - Award
  /v3/projects/{id}/snippets/{snippet_id}/notes/{note_id}/award_emoji:
    get:
      summary: Get Projects Snippets Snippet Notes Note Award Emoji
      description: Get projects snippets snippet notes note award emoji.
      operationId: getV3ProjectsIdSnippetsSnippetIdNotesNoteIdAwardEmoji
      x-api-path-slug: v3projectsidsnippetssnippet-idnotesnote-idaward-emoji-get
      parameters:
      - in: path
        name: id
      - in: path
        name: note_id
      - in: query
        name: page
        description: Current page number
      - in: query
        name: per_page
        description: Number of items per page
      - in: path
        name: snippet_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Snippets
      - Snippet
      - Notes
      - Note
      - Award
      - Emoji
    post:
      summary: Post Projects Snippets Snippet Notes Note Award Emoji
      description: Post projects snippets snippet notes note award emoji.
      operationId: postV3ProjectsIdSnippetsSnippetIdNotesNoteIdAwardEmoji
      x-api-path-slug: v3projectsidsnippetssnippet-idnotesnote-idaward-emoji-post
      parameters:
      - in: path
        name: id
      - in: formData
        name: name
        description: The name of a award_emoji (without colons)
      - in: path
        name: note_id
      - in: path
        name: snippet_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Snippets
      - Snippet
      - Notes
      - Note
      - Award
      - Emoji
  /v3/projects/{id}/snippets/{snippet_id}/notes/{note_id}/award_emoji/{award_id}:
    get:
      summary: Get Projects Snippets Snippet Notes Note Award Emoji Award
      description: Get projects snippets snippet notes note award emoji award.
      operationId: getV3ProjectsIdSnippetsSnippetIdNotesNoteIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidsnippetssnippet-idnotesnote-idaward-emojiaward-id-get
      parameters:
      - in: path
        name: award_id
        description: The ID of the award
      - in: path
        name: id
      - in: path
        name: note_id
      - in: path
        name: snippet_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Snippets
      - Snippet
      - Notes
      - Note
      - Award
      - Emoji
      - Award
    delete:
      summary: Delete Projects Snippets Snippet Notes Note Award Emoji Award
      description: Delete projects snippets snippet notes note award emoji award.
      operationId: deleteV3ProjectsIdSnippetsSnippetIdNotesNoteIdAwardEmojiAwardId
      x-api-path-slug: v3projectsidsnippetssnippet-idnotesnote-idaward-emojiaward-id-delete
      parameters:
      - in: path
        name: award_id
        description: The ID of an award emoji
      - in: path
        name: id
      - in: path
        name: note_id
      - in: path
        name: snippet_id
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Snippets
      - Snippet
      - Notes
      - Note
      - Award
      - Emoji
      - Award
  /v3/projects/{id}/boards:
    get:
      summary: Get Projects Boards
      description: This feature was introduced in 8.13
      operationId: getV3ProjectsIdBoards
      x-api-path-slug: v3projectsidboards-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Boards
  /v3/projects/{id}/repository/branches:
    get:
      summary: Get Projects Repository Branches
      description: Get a project repository branches
      operationId: getV3ProjectsIdRepositoryBranches
      x-api-path-slug: v3projectsidrepositorybranches-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Branches
    post:
      summary: Post Projects Repository Branches
      description: Post projects repository branches.
      operationId: postV3ProjectsIdRepositoryBranches
      x-api-path-slug: v3projectsidrepositorybranches-post
      parameters:
      - in: formData
        name: branch_name
        description: The name of the branch
      - in: path
        name: id
        description: The ID of a project
      - in: formData
        name: ref
        description: Create branch from commit sha or existing branch
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Branches
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