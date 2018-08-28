---
swagger: "2.0"
x-collection-name: GitLab
x-complete: 0
info:
  title: GitLab Post Projects Repository Commits Sha Comments
  version: 1.0.0
  description: Post projects repository commits sha comments.
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
  /v3/projects/{id}/repository/branches/{branch}:
    get:
      summary: Get Projects Repository Branches Branch
      description: Get projects repository branches branch.
      operationId: getV3ProjectsIdRepositoryBranchesBranch
      x-api-path-slug: v3projectsidrepositorybranchesbranch-get
      parameters:
      - in: path
        name: branch
        description: The name of the branch
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
      - Branch
    delete:
      summary: Delete Projects Repository Branches Branch
      description: Delete projects repository branches branch.
      operationId: deleteV3ProjectsIdRepositoryBranchesBranch
      x-api-path-slug: v3projectsidrepositorybranchesbranch-delete
      parameters:
      - in: path
        name: branch
        description: The name of the branch
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
      - Branch
  /v3/projects/{id}/repository/branches/{branch}/protect:
    put:
      summary: Put Projects Repository Branches Branch Protect
      description: Put projects repository branches branch protect.
      operationId: putV3ProjectsIdRepositoryBranchesBranchProtect
      x-api-path-slug: v3projectsidrepositorybranchesbranchprotect-put
      parameters:
      - in: path
        name: branch
        description: The name of the branch
      - in: formData
        name: developers_can_merge
        description: Flag if developers can merge to that branch
      - in: formData
        name: developers_can_push
        description: Flag if developers can push to that branch
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
      - Branch
      - Protect
  /v3/projects/{id}/repository/branches/{branch}/unprotect:
    put:
      summary: Put Projects Repository Branches Branch Unprotect
      description: Put projects repository branches branch unprotect.
      operationId: putV3ProjectsIdRepositoryBranchesBranchUnprotect
      x-api-path-slug: v3projectsidrepositorybranchesbranchunprotect-put
      parameters:
      - in: path
        name: branch
        description: The name of the branch
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
      - Branch
      - Unprotect
  /v3/projects/{id}/repository/merged_branches:
    delete:
      summary: Delete Projects Repository Merged Branches
      description: Delete projects repository merged branches.
      operationId: deleteV3ProjectsIdRepositoryMergedBranches
      x-api-path-slug: v3projectsidrepositorymerged-branches-delete
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
      - Merged
      - Branches
  /v3/projects/{id}/builds:
    get:
      summary: Get Projects Builds
      description: Get a project builds
      operationId: getV3ProjectsIdBuilds
      x-api-path-slug: v3projectsidbuilds-get
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
      - in: query
        name: scope
        description: The scope of builds to show
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
  /v3/projects/{id}/repository/commits/{sha}/builds:
    get:
      summary: Get Projects Repository Commits Sha Builds
      description: Get builds for a specific commit of a project
      operationId: getV3ProjectsIdRepositoryCommitsShaBuilds
      x-api-path-slug: v3projectsidrepositorycommitsshabuilds-get
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
      - in: query
        name: scope
        description: The scope of builds to show
      - in: path
        name: sha
        description: The SHA id of a commit
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Commits
      - Sha
      - Builds
  /v3/projects/{id}/builds/{build_id}:
    get:
      summary: Get Projects Builds Build
      description: Get a specific build of a project
      operationId: getV3ProjectsIdBuildsBuildId
      x-api-path-slug: v3projectsidbuildsbuild-id-get
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
  /v3/projects/{id}/builds/{build_id}/artifacts:
    get:
      summary: Get Projects Builds Build Artifacts
      description: This feature was introduced in GitLab 8.5
      operationId: getV3ProjectsIdBuildsBuildIdArtifacts
      x-api-path-slug: v3projectsidbuildsbuild-idartifacts-get
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Artifacts
  /v3/projects/{id}/builds/artifacts/{ref_name}/download:
    get:
      summary: Get Projects Builds Artifacts Ref Name Download
      description: Get projects builds artifacts ref name download.
      operationId: getV3ProjectsIdBuildsArtifactsRefNameDownload
      x-api-path-slug: v3projectsidbuildsartifactsref-namedownload-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: query
        name: job
        description: The name for the build
      - in: path
        name: ref_name
        description: The ref from repository
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Artifacts
      - Ref
      - Name
      - Download
  /v3/projects/{id}/builds/{build_id}/trace:
    get:
      summary: Get Projects Builds Build Trace
      description: Get a trace of a specific build of a project
      operationId: getV3ProjectsIdBuildsBuildIdTrace
      x-api-path-slug: v3projectsidbuildsbuild-idtrace-get
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Trace
  /v3/projects/{id}/builds/{build_id}/cancel:
    post:
      summary: Post Projects Builds Build Cancel
      description: Cancel a specific build of a project
      operationId: postV3ProjectsIdBuildsBuildIdCancel
      x-api-path-slug: v3projectsidbuildsbuild-idcancel-post
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Cancel
  /v3/projects/{id}/builds/{build_id}/retry:
    post:
      summary: Post Projects Builds Build Retry
      description: Retry a specific build of a project
      operationId: postV3ProjectsIdBuildsBuildIdRetry
      x-api-path-slug: v3projectsidbuildsbuild-idretry-post
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Retry
  /v3/projects/{id}/builds/{build_id}/erase:
    post:
      summary: Post Projects Builds Build Erase
      description: Erase build (remove artifacts and build trace)
      operationId: postV3ProjectsIdBuildsBuildIdErase
      x-api-path-slug: v3projectsidbuildsbuild-iderase-post
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Erase
  /v3/projects/{id}/builds/{build_id}/artifacts/keep:
    post:
      summary: Post Projects Builds Build Artifacts Keep
      description: Keep the artifacts to prevent them from being deleted
      operationId: postV3ProjectsIdBuildsBuildIdArtifactsKeep
      x-api-path-slug: v3projectsidbuildsbuild-idartifactskeep-post
      parameters:
      - in: path
        name: build_id
        description: The ID of a build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Artifacts
      - Keep
  /v3/projects/{id}/builds/{build_id}/play:
    post:
      summary: Post Projects Builds Build Play
      description: This feature was added in GitLab 8.11
      operationId: postV3ProjectsIdBuildsBuildIdPlay
      x-api-path-slug: v3projectsidbuildsbuild-idplay-post
      parameters:
      - in: path
        name: build_id
        description: The ID of a Build
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Builds
      - Build
      - Play
  /v3/projects/{id}/repository/commits:
    get:
      summary: Get Projects Repository Commits
      description: Get a project repository commits
      operationId: getV3ProjectsIdRepositoryCommits
      x-api-path-slug: v3projectsidrepositorycommits-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: query
        name: page
        description: The page for pagination
      - in: query
        name: path
        description: The file path
      - in: query
        name: per_page
        description: The number of results per page
      - in: query
        name: ref_name
        description: The name of a repository branch or tag, if not given the default
          branch is used
      - in: query
        name: since
        description: Only commits after or in this date will be returned
      - in: query
        name: until
        description: Only commits before or in this date will be returned
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Commits
    post:
      summary: Post Projects Repository Commits
      description: This feature was introduced in GitLab 8.13
      operationId: postV3ProjectsIdRepositoryCommits
      x-api-path-slug: v3projectsidrepositorycommits-post
      parameters:
      - in: formData
        name: actions
        description: Actions to perform in commit
      - in: formData
        name: author_email
        description: Author email for commit
      - in: formData
        name: author_name
        description: Author name for commit
      - in: formData
        name: branch_name
        description: The name of branch
      - in: formData
        name: commit_message
        description: Commit message
      - in: path
        name: id
        description: The ID of a project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Commits
  /v3/projects/{id}/repository/commits/{sha}:
    get:
      summary: Get Projects Repository Commits Sha
      description: Get projects repository commits sha.
      operationId: getV3ProjectsIdRepositoryCommitsSha
      x-api-path-slug: v3projectsidrepositorycommitssha-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: path
        name: sha
        description: A commit sha, or the name of a branch or tag
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Commits
      - Sha
  /v3/projects/{id}/repository/commits/{sha}/diff:
    get:
      summary: Get Projects Repository Commits Sha Diff
      description: Get the diff for a specific commit of a project
      operationId: getV3ProjectsIdRepositoryCommitsShaDiff
      x-api-path-slug: v3projectsidrepositorycommitsshadiff-get
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: path
        name: sha
        description: A commit sha, or the name of a branch or tag
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Commits
      - Sha
      - Diff
  /v3/projects/{id}/repository/commits/{sha}/comments:
    get:
      summary: Get Projects Repository Commits Sha Comments
      description: Get projects repository commits sha comments.
      operationId: getV3ProjectsIdRepositoryCommitsShaComments
      x-api-path-slug: v3projectsidrepositorycommitsshacomments-get
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
        name: sha
        description: A commit sha, or the name of a branch or tag
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Commits
      - Sha
      - Comments
    post:
      summary: Post Projects Repository Commits Sha Comments
      description: Post projects repository commits sha comments.
      operationId: postV3ProjectsIdRepositoryCommitsShaComments
      x-api-path-slug: v3projectsidrepositorycommitsshacomments-post
      parameters:
      - in: path
        name: id
        description: The ID of a project
      - in: formData
        name: line
        description: The line number
      - in: formData
        name: line_type
        description: The type of the line
      - in: formData
        name: note
        description: The text of the comment
      - in: formData
        name: path
        description: The file path
      - in: path
        name: sha
        description: The commits SHA
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Repository
      - Commits
      - Sha
      - Comments
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