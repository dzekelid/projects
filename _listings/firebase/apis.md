---
name: Firebase
x-slug: firebase
description: Firebase is a mobile platform that gives developers the tools and infrastructure
  to build better apps and grow successful businesses.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
x-kinRank: "9"
x-alexaRank: "1"
tags: Projects
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/firebase/apis.md
specificationVersion: "0.14"
apis:
- name: Firebase - Get Project Settings
  x-api-slug: projectidsettings-get
  description: |-
    Gets the Tool Results settings for a project.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to read from project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}//
  tags: Data, Real Time, API Provider, API Service Provider, SDIO Competition, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/firebase/projectidsettings-get-openapi.md
- name: Firebase - Initialize Settings
  x-api-slug: projectidinitializesettings-post
  description: |-
    Creates resources for settings which have not yet been set.

    Currently, this creates a single resource: a Google Cloud Storage bucket, to be used as the default bucket for this project. The bucket is created in the name of the user calling. Except in rare cases, calling this method in parallel from multiple clients will only create a single bucket. In order to avoid unnecessary storage charges, the bucket is configured to automatically delete objects older than 90 days.

    The bucket is created with the project-private ACL: All project team members are given permissions to the bucket and objects created within it according to their roles. Project owners have owners rights, and so on. The default ACL on objects created in the bucket is project-private as well. See Google Cloud Storage documentation for more details.

    If there is already a default bucket set and the project can access the bucket, this call does nothing. However, if the project doesn't have the permission to access the bucket or the bucket is deteleted, a new bucket will be created.

    May return any canonical error codes, including the following:

    - PERMISSION_DENIED - if the user is not authorized to write to project - Any error code raised by Google Cloud Storage
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}//
  tags: Data, Real Time, API Provider, API Service Provider, SDIO Competition, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/firebase/projectidinitializesettings-post-openapi.md
- name: Firebase - Get Project Settings
  x-api-slug: projectidsettings-get
  description: |-
    Gets the Tool Results settings for a project.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to read from project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}//
  tags: Data, Real Time, API Provider, API Service Provider, SDIO Competition, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/firebase/projectidsettings-get-openapi.md
- name: Firebase - Initialize Settings
  x-api-slug: projectidinitializesettings-post
  description: |-
    Creates resources for settings which have not yet been set.

    Currently, this creates a single resource: a Google Cloud Storage bucket, to be used as the default bucket for this project. The bucket is created in the name of the user calling. Except in rare cases, calling this method in parallel from multiple clients will only create a single bucket. In order to avoid unnecessary storage charges, the bucket is configured to automatically delete objects older than 90 days.

    The bucket is created with the project-private ACL: All project team members are given permissions to the bucket and objects created within it according to their roles. Project owners have owners rights, and so on. The default ACL on objects created in the bucket is project-private as well. See Google Cloud Storage documentation for more details.

    If there is already a default bucket set and the project can access the bucket, this call does nothing. However, if the project doesn't have the permission to access the bucket or the bucket is deteleted, a new bucket will be created.

    May return any canonical error codes, including the following:

    - PERMISSION_DENIED - if the user is not authorized to write to project - Any error code raised by Google Cloud Storage
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}//
  tags: Data, Real Time, API Provider, API Service Provider, SDIO Competition, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/firebase/projectidinitializesettings-post-openapi.md
- name: Firebase - Initialize Settings
  x-api-slug: projectidinitializesettings-post
  description: |-
    Creates resources for settings which have not yet been set.

    Currently, this creates a single resource: a Google Cloud Storage bucket, to be used as the default bucket for this project. The bucket is created in the name of the user calling. Except in rare cases, calling this method in parallel from multiple clients will only create a single bucket. In order to avoid unnecessary storage charges, the bucket is configured to automatically delete objects older than 90 days.

    The bucket is created with the project-private ACL: All project team members are given permissions to the bucket and objects created within it according to their roles. Project owners have owners rights, and so on. The default ACL on objects created in the bucket is project-private as well. See Google Cloud Storage documentation for more details.

    If there is already a default bucket set and the project can access the bucket, this call does nothing. However, if the project doesn't have the permission to access the bucket or the bucket is deteleted, a new bucket will be created.

    May return any canonical error codes, including the following:

    - PERMISSION_DENIED - if the user is not authorized to write to project - Any error code raised by Google Cloud Storage
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}//
  tags: Data, Real Time, API Provider, API Service Provider, SDIO Competition, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/firebase/projectidinitializesettings-post-openapi.md
- name: Firebase - Get Project Settings
  x-api-slug: projectidsettings-get
  description: |-
    Gets the Tool Results settings for a project.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to read from project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}//
  tags: Data, Real Time, API Provider, API Service Provider, SDIO Competition, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/firebase/projectidsettings-get-openapi.md
x-common:
- type: x-google-firebase
  url: Hacker News Search
- type: x-stack-exchange-search
  url: Google Firebase
- type: x-website
  url: https://Firebase.google.com
- type: x-api-gallery
  url: http://fire.browse.api.gallery.streamdata.io
- type: x-api-stack
  url: http://firebase.stack.network
- type: x-blog
  url: https://firebase.googleblog.com/
- type: x-blog-rss
  url: http://firebase.googleblog.com/feeds/posts/default?alt=rss
- type: x-case-studies
  url: https://firebase.google.com/customers/
- type: x-change-log
  url: https://firebase.google.com/support/releases
- type: x-code
  url: https://firebase.google.com/docs/libraries/
- type: x-crunchbase
  url: https://crunchbase.com/organization/google
- type: x-documentation
  url: https://firebase.google.com/docs/
- type: x-faq
  url: https://firebase.google.com/support/faq/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/firebase-talk
- type: x-github
  url: https://github.com/firebase
- type: x-pricing
  url: https://firebase.google.com/pricing/
- type: x-pricing
  url: https://adwords.google.com/home/pricing/
- type: x-slack
  url: https://firebase.community/
- type: x-submit-bug
  url: https://firebase.google.com/support/contact/bugs-features
- type: x-support
  url: https://firebase.google.com/support/
- type: x-twitter
  url: https://twitter.com/Google
- type: x-twitter
  url: https://twitter.com/firebase
- type: x-website
  url: https://firebase.google.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---