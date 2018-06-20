---
name: AWS CodeBuild
x-slug: aws-codebuild
description: AWS CodeBuild is a fully managed build service that compiles source code,
  runs tests, and produces software packages that are ready to deploy. With CodeBuild,
  you don&rsquo;t need to provision, manage, and scale your own build servers. CodeBuild
  scales continuously and processes multiple builds concurrently, so your builds are
  not left waiting in a queue. You can get started quickly by using prepackaged build
  environments, or you can create custom build environments that use your own build
  tools. With CodeBuild, you are charged by the minute for the compute resources you
  use.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Projects
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-codebuild/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CodeBuild API Batch Get Projects
  x-api-slug: aws-codebuild-api
  description: Gets information about one or more build projects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=BatchGetProjects
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-codebuild/actionbatchgetprojects-get-openapi.md
- name: AWS CodeBuild API Create Project
  x-api-slug: aws-codebuild-api
  description: Creates a build project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=CreateProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-codebuild/actioncreateproject-get-openapi.md
- name: AWS CodeBuild API Delete Project
  x-api-slug: aws-codebuild-api
  description: Deletes a build project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=DeleteProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-codebuild/actiondeleteproject-get-openapi.md
- name: AWS CodeBuild API List Projects
  x-api-slug: aws-codebuild-api
  description: Gets a list of build project names, with each build project name representing
    a single build project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=ListProjects
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-codebuild/actionlistprojects-get-openapi.md
- name: AWS CodeBuild API Update Project
  x-api-slug: aws-codebuild-api
  description: Changes the settings of an existing build project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=UpdateProject
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-codebuild/actionupdateproject-get-openapi.md
- name: AWS CodeBuild API
  x-api-slug: aws-codebuild-api
  description: AWS CodeBuild is a fully managed build service that compiles source
    code, runs tests, and produces software packages that are ready to deploy. With
    CodeBuild, you don&rsquo;t need to provision, manage, and scale your own build
    servers. CodeBuild scales continuously and processes multiple builds concurrently,
    so your builds are not left waiting in a queue. You can get started quickly by
    using prepackaged build environments, or you can create custom build environments
    that use your own build tools. With CodeBuild, you are charged by the minute for
    the compute resources you use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/projects/master/_listings/aws-codebuild/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/codebuild/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/codebuild/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/codebuild/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/codebuild/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/codebuild/pricing/
- type: x-website
  url: https://aws.amazon.com/codebuild/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---