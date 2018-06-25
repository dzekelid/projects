---
name: Bitbucket
x-slug: bitbucket
description: Collaborate on code with inline comments and pull requests. Manage and
  share your Git repositories to build and ship software, as a team.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
x-kinRank: "8"
x-alexaRank: "901"
tags: Projects
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/apis.md
specificationVersion: "0.14"
apis:
- name: Bitbucket Get Teams Owner Projects
  x-api-slug: bitbucket
  description: Get teams owner projects
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//teams/{owner}/projects/
  tags: Teams, Owner, Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojects-get-openapi.md
- name: Bitbucket Parameters Teams Owner Projects
  x-api-slug: bitbucket
  description: Parameters teams owner projects
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//teams/{owner}/projects/
  tags: Teams, Owner, Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojects-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojects-parameters-openapi.md
- name: Bitbucket Add Teams Owner Projects
  x-api-slug: bitbucket
  description: |-
    Creates a new project.

    Note that the avatar has to be embedded as either a data-url
    or a URL to an external image as shown in the examples below:

    ```
    $ body=$(cat << EOF
    {
        "name": "Mars Project",
        "key": "MARS",
        "description": "Software for colonizing mars.",
        "links": {
            "avatar": {
                "href": "data:image/gif;base64,R0lGODlhEAAQAMQAAORHHOVSKudfOulrSOp3WOyDZu6QdvCchPGolfO0o/..."
            }
        },
        "is_private": false
    }
    EOF
    )
    $ curl -H "Content-Type: application/json" \
           -X POST \
           -d "$body" \
           https://api.bitbucket.org/2.0/teams/teams-in-space/projects/ | jq .
    {
      // Serialized project document
    }
    ```

    or even:

    ```
    $ body=$(cat << EOF
    {
        "name": "Mars Project",
        "key": "MARS",
        "description": "Software for colonizing mars.",
        "links": {
            "avatar": {
                "href": "http://i.imgur.com/72tRx4w.gif"
            }
        },
        "is_private": false
    }
    EOF
    )
    $ curl -H "Content-Type: application/json" \
           -X POST \
           -d "$body" \
           https://api.bitbucket.org/2.0/teams/teams-in-space/projects/ | jq .
    {
      // Serialized project document
    }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//teams/{owner}/projects/
  tags: Teams, Owner, Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojects-post-openapi.md
- name: Bitbucket Delete Teams Owner Projects Project Key
  x-api-slug: bitbucket
  description: Delete teams owner projects project key
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//teams/{owner}/projects/{project_key}
  tags: Teams, Owner, Projects, Project, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojectsproject-key-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojectsproject-key-delete-openapi.md
- name: Bitbucket Get Teams Owner Projects Project Key
  x-api-slug: bitbucket
  description: Get teams owner projects project key
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//teams/{owner}/projects/{project_key}
  tags: Teams, Owner, Projects, Project, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojectsproject-key-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojectsproject-key-get-openapi.md
- name: Bitbucket Parameters Teams Owner Projects Project Key
  x-api-slug: bitbucket
  description: Parameters teams owner projects project key
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//teams/{owner}/projects/{project_key}
  tags: Teams, Owner, Projects, Project, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojectsproject-key-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojectsproject-key-parameters-openapi.md
- name: Bitbucket Update Teams Owner Projects Project Key
  x-api-slug: bitbucket
  description: |-
    Since this endpoint can be used to both update and to create a
    project, the request body depends on the intent.

    ### Creation

    See the POST documentation for the project collection for an
    example of the request body.

    Note: The `key` should not be specified in the body of request
    (since it is already present in the URL). The `name` is required,
    everything else is optional.

    ### Update

    See the POST documentation for the project collection for an
    example of the request body.

    Note: The key is not required in the body (since it is already in
    the URL). The key may be specified in the body, if the intent is
    to change the key itself. In such a scenario, the location of the
    project is changed and is returned in the `Location` header of the
    response.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//teams/{owner}/projects/{project_key}
  tags: Teams, Owner, Projects, Project, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/teamsownerprojectsproject-key-put-openapi.md
- name: Bitbucket
  x-api-slug: bitbucket
  description: Collaborate on code with inline comments and pull requests. Manage
    and share your Git repositories to build and ship software, as a team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/bitbucket/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/bitbucket
- type: x-developer
  url: https://developer.atlassian.com/cloud/bitbucket/
- type: x-documentation
  url: https://confluence.atlassian.com/bitbucket/bitbucket-cloud-documentation-221448814.html?_ga=2.77295890.629375793.1519179030-1077111323.1516485126
- type: x-status
  url: https://status.bitbucket.org/?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-support
  url: https://support.atlassian.com/bitbucket-cloud/
- type: x-terms-of-service
  url: https://www.atlassian.com/legal/customer-agreement?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-twitter
  url: https://twitter.com/bitbucket
- type: x-website
  url: http://bitbucket.org
- type: x-website
  url: https://bitbucket.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---