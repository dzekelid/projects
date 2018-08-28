---
name: Google Cloud Resource Manager
x-slug: google-cloud-resource-manager
description: Google Cloud Platform provides resource containers such as Organizations
  and Projects, that allow you to group and hierarchically organize other Cloud Platform
  resources. This hierarchical organization lets you easily manage common aspects
  of your resources such as access control and configuration settings. The Google
  Cloud Resource Manager service enables you to programmatically manage these resource
  containers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Projects
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Resource Manager - List Projects
  x-api-slug: v1projects-get
  description: |-
    Lists Projects that are visible to the user and satisfy the
    specified filter. This method returns Projects in an unspecified order.
    New Projects do not necessarily appear at the end of the list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projects-get-openapi.md
- name: Google Cloud Resource Manager - Create Project
  x-api-slug: v1projects-post
  description: |-
    Request that a new Project be created. The result is an Operation which
    can be used to track the creation process. It is automatically deleted
    after a few hours, so there is no need to call DeleteOperation.

    Our SLO permits Project creation to take up to 30 seconds at the 90th
    percentile. As of 2016-08-29, we are observing 6 seconds 50th percentile
    latency. 95th percentile latency is around 11 seconds. We recommend
    polling at the 5th second with an exponential backoff.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projects-post-openapi.md
- name: Google Cloud Resource Manager - Delete Project
  x-api-slug: v1projectsprojectid-delete
  description: |-
    Marks the Project identified by the specified
    `project_id` (for example, `my-project-123`) for deletion.
    This method will only affect the Project if the following criteria are met:

    + The Project does not have a billing account associated with it.
    + The Project has a lifecycle state of
    ACTIVE.

    This method changes the Project's lifecycle state from
    ACTIVE
    to DELETE_REQUESTED.
    The deletion starts at an unspecified time,
    at which point the Project is no longer accessible.

    Until the deletion completes, you can check the lifecycle state
    checked by retrieving the Project with GetProject,
    and the Project remains visible to ListProjects.
    However, you cannot update the project.

    After the deletion completes, the Project is not retrievable by
    the  GetProject and
    ListProjects methods.

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-delete-openapi.md
- name: Google Cloud Resource Manager - Get Project
  x-api-slug: v1projectsprojectid-get
  description: |-
    Retrieves the Project identified by the specified
    `project_id` (for example, `my-project-123`).

    The caller must have read permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-get-openapi.md
- name: Google Cloud Resource Manager - Update Project
  x-api-slug: v1projectsprojectid-put
  description: |-
    Updates the attributes of the Project identified by the specified
    `project_id` (for example, `my-project-123`).

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-put-openapi.md
- name: Google Cloud Resource Manager - Get Project Ancestry
  x-api-slug: v1projectsprojectidgetancestry-post
  description: |-
    Gets a list of ancestors in the resource hierarchy for the Project
    identified by the specified `project_id` (for example, `my-project-123`).

    The caller must have read permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectidgetancestry-post-openapi.md
- name: Google Cloud Resource Manager - Restore Project
  x-api-slug: v1projectsprojectidundelete-post
  description: |-
    Restores the Project identified by the specified
    `project_id` (for example, `my-project-123`).
    You can only use this method for a Project that has a lifecycle state of
    DELETE_REQUESTED.
    After deletion starts, the Project cannot be restored.

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectidundelete-post-openapi.md
- name: Google Cloud Resource Manager - List Projects
  x-api-slug: v1projects-get
  description: |-
    Lists Projects that are visible to the user and satisfy the
    specified filter. This method returns Projects in an unspecified order.
    New Projects do not necessarily appear at the end of the list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projects-get-openapi.md
- name: Google Cloud Resource Manager - Create Project
  x-api-slug: v1projects-post
  description: |-
    Request that a new Project be created. The result is an Operation which
    can be used to track the creation process. It is automatically deleted
    after a few hours, so there is no need to call DeleteOperation.

    Our SLO permits Project creation to take up to 30 seconds at the 90th
    percentile. As of 2016-08-29, we are observing 6 seconds 50th percentile
    latency. 95th percentile latency is around 11 seconds. We recommend
    polling at the 5th second with an exponential backoff.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projects-post-openapi.md
- name: Google Cloud Resource Manager - Delete Project
  x-api-slug: v1projectsprojectid-delete
  description: |-
    Marks the Project identified by the specified
    `project_id` (for example, `my-project-123`) for deletion.
    This method will only affect the Project if the following criteria are met:

    + The Project does not have a billing account associated with it.
    + The Project has a lifecycle state of
    ACTIVE.

    This method changes the Project's lifecycle state from
    ACTIVE
    to DELETE_REQUESTED.
    The deletion starts at an unspecified time,
    at which point the Project is no longer accessible.

    Until the deletion completes, you can check the lifecycle state
    checked by retrieving the Project with GetProject,
    and the Project remains visible to ListProjects.
    However, you cannot update the project.

    After the deletion completes, the Project is not retrievable by
    the  GetProject and
    ListProjects methods.

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-delete-openapi.md
- name: Google Cloud Resource Manager - Get Project
  x-api-slug: v1projectsprojectid-get
  description: |-
    Retrieves the Project identified by the specified
    `project_id` (for example, `my-project-123`).

    The caller must have read permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-get-openapi.md
- name: Google Cloud Resource Manager - Update Project
  x-api-slug: v1projectsprojectid-put
  description: |-
    Updates the attributes of the Project identified by the specified
    `project_id` (for example, `my-project-123`).

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-put-openapi.md
- name: Google Cloud Resource Manager - Get Project Ancestry
  x-api-slug: v1projectsprojectidgetancestry-post
  description: |-
    Gets a list of ancestors in the resource hierarchy for the Project
    identified by the specified `project_id` (for example, `my-project-123`).

    The caller must have read permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectidgetancestry-post-openapi.md
- name: Google Cloud Resource Manager - Restore Project
  x-api-slug: v1projectsprojectidundelete-post
  description: |-
    Restores the Project identified by the specified
    `project_id` (for example, `my-project-123`).
    You can only use this method for a Project that has a lifecycle state of
    DELETE_REQUESTED.
    After deletion starts, the Project cannot be restored.

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectidundelete-post-openapi.md
- name: Google Cloud Resource Manager - List Projects
  x-api-slug: v1projects-get
  description: |-
    Lists Projects that are visible to the user and satisfy the
    specified filter. This method returns Projects in an unspecified order.
    New Projects do not necessarily appear at the end of the list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projects-get-openapi.md
- name: Google Cloud Resource Manager - Create Project
  x-api-slug: v1projects-post
  description: |-
    Request that a new Project be created. The result is an Operation which
    can be used to track the creation process. It is automatically deleted
    after a few hours, so there is no need to call DeleteOperation.

    Our SLO permits Project creation to take up to 30 seconds at the 90th
    percentile. As of 2016-08-29, we are observing 6 seconds 50th percentile
    latency. 95th percentile latency is around 11 seconds. We recommend
    polling at the 5th second with an exponential backoff.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projects-post-openapi.md
- name: Google Cloud Resource Manager - Delete Project
  x-api-slug: v1projectsprojectid-delete
  description: |-
    Marks the Project identified by the specified
    `project_id` (for example, `my-project-123`) for deletion.
    This method will only affect the Project if the following criteria are met:

    + The Project does not have a billing account associated with it.
    + The Project has a lifecycle state of
    ACTIVE.

    This method changes the Project's lifecycle state from
    ACTIVE
    to DELETE_REQUESTED.
    The deletion starts at an unspecified time,
    at which point the Project is no longer accessible.

    Until the deletion completes, you can check the lifecycle state
    checked by retrieving the Project with GetProject,
    and the Project remains visible to ListProjects.
    However, you cannot update the project.

    After the deletion completes, the Project is not retrievable by
    the  GetProject and
    ListProjects methods.

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-delete-openapi.md
- name: Google Cloud Resource Manager - Get Project
  x-api-slug: v1projectsprojectid-get
  description: |-
    Retrieves the Project identified by the specified
    `project_id` (for example, `my-project-123`).

    The caller must have read permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-get-openapi.md
- name: Google Cloud Resource Manager - Update Project
  x-api-slug: v1projectsprojectid-put
  description: |-
    Updates the attributes of the Project identified by the specified
    `project_id` (for example, `my-project-123`).

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectid-put-openapi.md
- name: Google Cloud Resource Manager - Get Project Ancestry
  x-api-slug: v1projectsprojectidgetancestry-post
  description: |-
    Gets a list of ancestors in the resource hierarchy for the Project
    identified by the specified `project_id` (for example, `my-project-123`).

    The caller must have read permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectidgetancestry-post-openapi.md
- name: Google Cloud Resource Manager - Restore Project
  x-api-slug: v1projectsprojectidundelete-post
  description: |-
    Restores the Project identified by the specified
    `project_id` (for example, `my-project-123`).
    You can only use this method for a Project that has a lifecycle state of
    DELETE_REQUESTED.
    After deletion starts, the Project cannot be restored.

    The caller must have modify permissions for this Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/resource-manager/
  baseURL: ://cloudresourcemanager.googleapis.com//
  tags: Orchestration, Google APIs, Management, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/google-cloud-resource-manager/v1projectsprojectidundelete-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.pub.sub.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.resource.manager.stack.network
- type: x-authentication
  url: https://cloud.google.com/resource-manager/docs/authorizing
- type: x-code
  url: https://cloud.google.com/resource-manager/docs/libraries
- type: x-documentation
  url: https://cloud.google.com/resource-manager/docs/
- type: x-errors
  url: https://cloud.google.com/resource-manager/docs/core_errors
- type: x-how-to-guides
  url: https://cloud.google.com/resource-manager/docs/how-to
- type: x-performance
  url: https://cloud.google.com/resource-manager/docs/performance
- type: x-pricing
  url: https://cloud.google.com/resource-manager/pricing
- type: x-rate-limits
  url: https://cloud.google.com/resource-manager/docs/limits
- type: x-website
  url: https://cloud.google.com/resource-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---