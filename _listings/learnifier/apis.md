---
name: Learnifier
x-slug: learnifier
description: Create your online courses in minutes. Learnifier is the fast and easy
  tool for creating and sharing great courses that work on your mobile, tablet and
  desktop. Book a DEMO or test it out with our FREE TRIAL.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
x-kinRank: "7"
x-alexaRank: "5836977"
tags: Projects
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/apis.md
specificationVersion: "0.14"
apis:
- name: Learnifier Gets Organization Unit by external id
  x-api-slug: learnifier
  description: Gets an Organization Unit by external id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////extproject
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/extproject-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/extproject-get-openapi.md
- name: Learnifier Organization Unit Projects
  x-api-slug: learnifier
  description: Returns the available projects for the organization unit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects
  tags: Organizations,Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojects-get-openapi.md
- name: Learnifier Create project
  x-api-slug: learnifier
  description: Creates a new project
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects
  tags: Organizations,Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojects-post-openapi.md
- name: Learnifier Deletes the project
  x-api-slug: learnifier
  description: Deletes the project. The project can only be deleted if the project
    do not contain any participants.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}
  tags: Organizations,Projects,Projectid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectid-delete-openapi.md
- name: Learnifier Project information
  x-api-slug: learnifier
  description: Returns project information
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}
  tags: Organizations,Projects,Projectid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectid-get-openapi.md
- name: Learnifier Update project information
  x-api-slug: learnifier
  description: Updates information about a project. Values are only updated if the
    fields are specified in the input
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}
  tags: Organizations,Projects,Projectid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectid-patch-openapi.md
- name: Learnifier Project participants
  x-api-slug: learnifier
  description: Returns project participants
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants
  tags: Organizations,Projects,Projectid,Participants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipants-get-openapi.md
- name: Learnifier Add participant
  x-api-slug: learnifier
  description: Add a user to the project. Participant information is created for the
    user. In the body object, only one of either email or userid must be specified.
    The participant needs to be activated before it the user can access it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants
  tags: Organizations,Projects,Projectid,Participants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipants-post-openapi.md
- name: Learnifier Deletes a participant
  x-api-slug: learnifier
  description: "Deletes a participant. The user itself will still remain but any state
    related to the project will be deleted. \nIt might not be possible due to constraints
    from the products in the project to delete the participant. However\nthis can
    only be determined at the time of the delete. If a delete fails the participant
    will have their inError\nflag set."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants/${participantId}
  tags: Organizations,Projects,Projectid,Participants,$participantId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipantsparticipantid-delete-openapi.md
- name: Learnifier Activate participant
  x-api-slug: learnifier
  description: Activates a participant so that it can be used
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants/${participantId}/activate
  tags: Organizations,Projects,Projectid,Participants,$participantId,Activate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipantsparticipantidactivate-post-openapi.md
- name: Learnifier Participant login link
  x-api-slug: learnifier
  description: |-
    Returns a single sign on link for the participant. The link is only usable once and should be used directly. The link expires after a few minutes.

    This operation requires the *login link* permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants/${participantId}/loginlink
  tags: Organizations,Projects,Projectid,Participants,$participantId,Loginlink
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipantsparticipantidloginlink-post-openapi.md
- name: Learnifier Project team members
  x-api-slug: learnifier
  description: Returns the project team members. A team member is a ....
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/teammembers
  tags: Organizations,Projects,Projectid,Team,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectidteammembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/orgunitsorgidprojectsprojectidteammembers-get-openapi.md
- name: Learnifier
  x-api-slug: learnifier
  description: Create your online courses in minutes. Learnifier is the fast and easy
    tool for creating and sharing great courses that work on your mobile, tablet and
    desktop. Book a DEMO or test it out with our FREE TRIAL.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com//
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/learnifier/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/learnifier
- type: x-developer
  url: https://learnifier.com/api/
- type: x-email
  url: sales@learnifier.com
- type: x-email
  url: Abdalla.Mohamed@learnifier.com
- type: x-email
  url: support@learnifier.com
- type: x-email
  url: jerker.klang@learnifier.com
- type: x-email
  url: mattias.borg@learnifier.com
- type: x-email
  url: lars.peterstrand@learnifier.com
- type: x-email
  url: hello@learnifier.com
- type: x-email
  url: unsubscribe@learnifier.com
- type: x-email
  url: privacy@learnifier.com
- type: x-twitter
  url: https://twitter.com/Learnifier
- type: x-website
  url: http://learnifier.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---