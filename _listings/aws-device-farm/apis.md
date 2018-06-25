---
name: AWS Device Farm
x-slug: aws-device-farm
description: AWS Device Farm is an app testing service that lets you test and interact
  with your Android, iOS, and web apps on many devices at once, or reproduce issues
  on a device in real time. View video, screenshots, logs, and performance data to
  pinpoint and fix issues before shipping your app.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Projects
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-device-farm/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Device Farm API Delete Project
  x-api-slug: aws-device-farm-api
  description: Deletes an AWS Device Farm project, given the project ARN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=DeleteProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-device-farm/actiondeleteproject-get-openapi.md
- name: AWS Device Farm API Get Project
  x-api-slug: aws-device-farm-api
  description: Gets information about a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=GetProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-device-farm/actiongetproject-get-openapi.md
- name: AWS Device Farm API List Projects
  x-api-slug: aws-device-farm-api
  description: Gets information about projects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=ListProjects
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-device-farm/actionlistprojects-get-openapi.md
- name: AWS Device Farm API Update Project
  x-api-slug: aws-device-farm-api
  description: Modifies the specified project name, given the project ARN and a new
    name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: ://///?Action=UpdateProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-device-farm/actionupdateproject-get-openapi.md
- name: AWS Device Farm API
  x-api-slug: aws-device-farm-api
  description: AWS Device Farm is an app testing service that lets you test and interact
    with your Android, iOS, and web apps on many devices at once, or reproduce issues
    on a device in real time. View video, screenshots, logs, and performance data
    to pinpoint and fix issues before shipping your app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AWSDeviceFarm.png
  humanURL: https://aws.amazon.com/device-farm/
  baseURL: :///
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-device-farm/openapi.md
x-common:
- type: x-blog
  url: https://aws.amazon.com/blogs/mobile/tag/aws-device-farm/
- type: x-concepts
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/concepts.html
- type: x-documentation
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/api-ref.html
- type: x-documentation
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/cli-ref.html
- type: x-limits
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/limits.html
- type: x-logging
  url: https://docs.aws.amazon.com/devicefarm/latest/developerguide/cloudtrail.html
- type: x-plugins
  url: https://github.com/awslabs?q=aws-device-farm
- type: x-faq
  url: https://aws.amazon.com/device-farm/faq
- type: x-pricing
  url: https://aws.amazon.com/device-farm/pricing
- type: x-website
  url: https://aws.amazon.com/device-farm/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---