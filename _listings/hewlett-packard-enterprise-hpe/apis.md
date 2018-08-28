---
name: Hewlett Packard Enterprise (HPE)
x-slug: hewlett-packard-enterprise-hpe
description: We help customers use technology to slash the time it takes to turn ideas
  into value. In turn, they transform industries, markets and lives. Some of our customers
  run traditional IT environments. Most are transitioning to a secure, cloud-enabled,
  mobile-friendly infrastructure. Many rely on a combination of both. Wherever they
  are in that journey, we provide the technology and solutions to help them succeed.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Projects
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/hewlett-packard-enterprise-hpe/apis.md
specificationVersion: "0.14"
apis:
- name: HPE OneSphere API - Get Projects
  x-api-slug: projects-get
  description: Returns projects. It requires any project role or non-'consumer' global
    role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/hewlett-packard-enterprise-hpe/projects-get-openapi.md
- name: HPE OneSphere API - Post Projects
  x-api-slug: projects-post
  description: Creates a new project. It requires the **project-owner** project role,
    or **administrator** or **project creator** global role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/hewlett-packard-enterprise-hpe/projects-post-openapi.md
- name: HPE OneSphere API - Delete Projects
  x-api-slug: projectsid-delete
  description: Deletes a project. If resources (currently Deployments) exist within
    the project they must first be deleted. In this case, the response will be a 409
    Conflict with the body listing the first ten offending items. It requires **administratpor**
    global role or **owner** project role. **not implemented**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/hewlett-packard-enterprise-hpe/projectsid-delete-openapi.md
- name: HPE OneSphere API - Get Projects
  x-api-slug: projectsid-get
  description: Returns a project based on its id. It requires any project role or
    non-consumer global role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/hewlett-packard-enterprise-hpe/projectsid-get-openapi.md
- name: HPE OneSphere API - Patch Projects
  x-api-slug: projectsid-patch
  description: Updates a project. It requires the **administrator** global role or
    the **project owner** role on a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/HPE-logo.png
  humanURL: http://HPE.com
  baseURL: https://deic02-hpe.hpeonesphere.com//rest
  tags: Enterprise, Cloud, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/hewlett-packard-enterprise-hpe/projectsid-patch-openapi.md
x-common:
- type: x-developer
  url: https://developer.hpe.com/
- type: x-github
  url: https://github.com/hewlettpackard
- type: x-openapi
  url: https://raw.githubusercontent.com/HewlettPackard/hpe-onesphere-http/master/swagger.yml
- type: x-twitter
  url: https://twitter.com/HPE
- type: x-website
  url: http://HPE.com
- type: x-api-gallery
  url: http://heroku.api.gallery.streamdata.io
- type: x-api-stack
  url: http://hewlett.packard.enterprise.hpe.stack.network
- type: x-blog
  url: https://developer.hpe.com/blog
- type: x-curated-source
  url: http://community.hpe.com/t5/LoadRunner-and-Performance/LoadRunner-and-VuGen-12-53-load-testing-software-What-s-new-in/ba-p/6885101
- type: x-website
  url: https://www.hpe.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---