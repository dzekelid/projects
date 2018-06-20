---
name: Pivotal Tracker
x-slug: pivotal-tracker
description: Writing software isn&rsquo;t half as hard as all the talking, emails,
  and meetings needed to reconcile shifting requirements and slipping deadlines. We
  get it, we&rsquo;ve been there. In fact, we&rsquo;re still there. Were Pivotal Labs,
  a web and mobile development consultancy. In 2006 we built Tracker for our developers
  and clients to facilitate constructive communication, reflect the status of a project
  and help forecast its future. Today Tracker is a staple of the developers toolkit.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Projects
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/apis.md
specificationVersion: "0.14"
apis:
- name: Pivotal Tracker Get Projects Project Activities
  x-api-slug: pivotal-tracker
  description: Retrieves the recent activity of a specific project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/activities
  tags: Projects,PROJECT,ID,Activities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idactivities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idactivities-get-openapi.md
- name: Pivotal Tracker Get Projects Project
  x-api-slug: pivotal-tracker
  description: Retrieves information about a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}
  tags: Projects,PROJECT,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-id-get-openapi.md
- name: Pivotal Tracker Get Projects
  x-api-slug: pivotal-tracker
  description: Retrieves all of the user's projects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projects-get-openapi.md
- name: Pivotal Tracker Post Projects
  x-api-slug: pivotal-tracker
  description: Adds a new project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projects-post-openapi.md
- name: Pivotal Tracker Get Projects Project Memberships
  x-api-slug: pivotal-tracker
  description: Retrieves all memberships for a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/memberships
  tags: Projects,PROJECT,ID,Memberships
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idmemberships-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idmemberships-get-openapi.md
- name: Pivotal Tracker Post Projects Project Memberships
  x-api-slug: pivotal-tracker
  description: Adds a new membership to a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/memberships
  tags: Projects,PROJECT,ID,Memberships
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idmemberships-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idmemberships-post-openapi.md
- name: Pivotal Tracker Get Projects Project Memberships Membership
  x-api-slug: pivotal-tracker
  description: Retrieves information about a single membership.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/memberships/{MEMBERSHIP_ID}
  tags: Projects,PROJECT,ID,Memberships,MEMBERSHIP,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idmembershipsmembership-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idmembershipsmembership-id-get-openapi.md
- name: Pivotal Tracker Delete Projects Project Memberships Membership
  x-api-slug: pivotal-tracker
  description: Delete projects project memberships membership.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/memberships/{MEMBERSHIP_ID}
  tags: Projects,PROJECT,ID,Memberships,MEMBERSHIP,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idmembershipsmembership-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idmembershipsmembership-id-delete-openapi.md
- name: Pivotal Tracker Get Projects Project Iterations
  x-api-slug: pivotal-tracker
  description: Retrieves all iterations, with stories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/iterations
  tags: Projects,PROJECT,ID,Iterations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerations-get-openapi.md
- name: Pivotal Tracker Get Projects Project Iterations Done
  x-api-slug: pivotal-tracker
  description: Retrieves iterations from the "done" group, with stories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/iterations/done
  tags: Projects,PROJECT,ID,Iterations,Done
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerationsdone-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerationsdone-get-openapi.md
- name: Pivotal Tracker Get Projects Project Iterations Current
  x-api-slug: pivotal-tracker
  description: Retrieves iterations from the "current" group, with stories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/iterations/current
  tags: Projects,PROJECT,ID,Iterations,Current
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerationscurrent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerationscurrent-get-openapi.md
- name: Pivotal Tracker Get Projects Project Iterations Backlog
  x-api-slug: pivotal-tracker
  description: Retrieves iterations from the "backlog" group, with stories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/iterations/backlog
  tags: Projects,PROJECT,ID,Iterations,Backlog
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerationsbacklog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerationsbacklog-get-openapi.md
- name: Pivotal Tracker Get Projects Project Iterations Current Backlog
  x-api-slug: pivotal-tracker
  description: Retrieves iterations from the "current" and "backlog" groups, with
    stories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/iterations/current_backlog
  tags: Projects,PROJECT,ID,Iterations,Current,Backlog
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerationscurrent-backlog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-iditerationscurrent-backlog-get-openapi.md
- name: Pivotal Tracker Get Projects Project Stories Story
  x-api-slug: pivotal-tracker
  description: Retrieves information about a single story.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}
  tags: Projects,PROJECT,ID,Stories,STORY,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-id-get-openapi.md
- name: Pivotal Tracker Put Projects Project Stories Story
  x-api-slug: pivotal-tracker
  description: Put projects project stories story.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}
  tags: Projects,PROJECT,ID,Stories,STORY,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-id-put-openapi.md
- name: Pivotal Tracker Delete Projects Project Stories Story
  x-api-slug: pivotal-tracker
  description: Delete projects project stories story.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}
  tags: Projects,PROJECT,ID,Stories,STORY,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-id-delete-openapi.md
- name: Pivotal Tracker Get Projects Project Stories
  x-api-slug: pivotal-tracker
  description: Retrieves all stories for a project, or those matching filter(s)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories
  tags: Projects,PROJECT,ID,Stories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstories-get-openapi.md
- name: Pivotal Tracker Post Projects Project Stories
  x-api-slug: pivotal-tracker
  description: Post projects project stories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories
  tags: Projects,PROJECT,ID,Stories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstories-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstories-post-openapi.md
- name: Pivotal Tracker Put Projects Project Stories Story Notes
  x-api-slug: pivotal-tracker
  description: Put projects project stories story notes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}/notes
  tags: Projects,PROJECT,ID,Stories,STORY,ID,Notes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idnotes-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idnotes-put-openapi.md
- name: Pivotal Tracker Post Projects Project Stories Deliver All Finished
  x-api-slug: pivotal-tracker
  description: Takes all finished stories and marks them as delivered. This could
    be used to automate a demo deploy process. The updated stories are returned as
    the result.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/deliver_all_finished
  tags: Projects,PROJECT,ID,Stories,Deliver,,Finished
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesdeliver-all-finished-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesdeliver-all-finished-post-openapi.md
- name: Pivotal Tracker Post Projects Project Stories Story Moves
  x-api-slug: pivotal-tracker
  description: Moves a story before or after another story. The moved story is returned
    in the response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}/moves
  tags: Projects,PROJECT,ID,Stories,STORY,ID,Moves
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idmoves-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idmoves-post-openapi.md
- name: Pivotal Tracker Get Projects Project Stories Story Tasks Task
  x-api-slug: pivotal-tracker
  description: Get projects project stories story tasks task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}/tasks/{TASK_ID}
  tags: Projects,PROJECT,ID,Stories,STORY,ID,Tasks,TASK,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtaskstask-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtaskstask-id-get-openapi.md
- name: Pivotal Tracker Put Projects Project Stories Story Tasks Task
  x-api-slug: pivotal-tracker
  description: Put projects project stories story tasks task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}/tasks/{TASK_ID}
  tags: Projects,PROJECT,ID,Stories,STORY,ID,Tasks,TASK,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtaskstask-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtaskstask-id-put-openapi.md
- name: Pivotal Tracker Delete Projects Project Stories Story Tasks Task
  x-api-slug: pivotal-tracker
  description: Delete projects project stories story tasks task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}/tasks/{TASK_ID}
  tags: Projects,PROJECT,ID,Stories,STORY,ID,Tasks,TASK,ID
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtaskstask-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtaskstask-id-delete-openapi.md
- name: Pivotal Tracker Get Projects Project Stories Story Tasks
  x-api-slug: pivotal-tracker
  description: Get projects project stories story tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}/tasks
  tags: Projects,PROJECT,ID,Stories,STORY,ID,Tasks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtasks-get-openapi.md
- name: Pivotal Tracker Post Projects Project Stories Story Tasks
  x-api-slug: pivotal-tracker
  description: Post projects project stories story tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}/tasks
  tags: Projects,PROJECT,ID,Stories,STORY,ID,Tasks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtasks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idtasks-post-openapi.md
- name: Pivotal Tracker Post Projects Project Stories Story Attachments
  x-api-slug: pivotal-tracker
  description: Post projects project stories story attachments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3///projects/{PROJECT_ID}/stories/{STORY_ID}/attachments
  tags: Projects,PROJECT,ID,Stories,STORY,ID,Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/projectsproject-idstoriesstory-idattachments-post-openapi.md
- name: Pivotal Tracker
  x-api-slug: pivotal-tracker
  description: Whether welding together two apps or forging a unique one, tap into
    100% of the Tracker feature set with the very same API the Tracker team uses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/pivotal-tracker.png
  humanURL: http://pivotaltracker.com
  baseURL: https://www.pivotaltracker.com//services/v3/
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/pivotal-tracker/openapi.md
x-common:
- type: x-blog
  url: http://www.pivotaltracker.com/community/tracker-blog
- type: x-blog
  url: http://www.pivotaltracker.com/feed
- type: x-email
  url: TRACKER@PIVOTAL.IO
- type: x-faq
  url: https://www.pivotaltracker.com/faq
- type: x-github
  url: https://github.com/pivotal
- type: x-pricing
  url: http://www.pivotaltracker.com/why-tracker/pricing
- type: x-selfservice-registration
  url: https://www.pivotaltracker.com/signup/new
- type: x-status
  url: http://status.pivotaltracker.com/
- type: x-terms-of-service
  url: https://www.pivotaltracker.com/policy/eula
- type: x-twitter
  url: https://twitter.com/pivotaltracker
- type: x-website
  url: http://pivotaltracker.com
- type: x-website
  url: http://www.pivotaltracker.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---