{
  "info": {
    "name": "Pivotal Tracker Get Projects Project Stories Story",
    "_postman_id": "f262a79b-08a4-4876-879a-2daf7a079b2e",
    "description": "Retrieves information about a single story.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "2b2ad31b-1bb0-4d91-b096-7c7acb7db349",
          "name": "getProjectsProjectActivities",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/activities"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "occurred_since_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the recent activity of a specific project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "56a7d7d3-6dc2-48d1-a285-9d90d4a34bdb"
            }
          ]
        },
        {
          "id": "43434c34-9f1c-4254-98ab-1a7cbe752869",
          "name": "getProjectsProject",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID"
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f08fb48-9cb1-43db-8619-3fd35d6d8214"
            }
          ]
        },
        {
          "id": "4a41efc4-20e3-4bec-8bfd-842af922c672",
          "name": "getProjects",
          "request": {
            "url": "http://www.pivotaltracker.com/services/v3/projects",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all of the user's projects."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ee85383-6ba5-4b62-8aff-de74f2f12b3a"
            }
          ]
        },
        {
          "id": "f90eb79e-6bef-464b-9307-2e488dd3dbd0",
          "name": "postProjects",
          "request": {
            "url": "http://www.pivotaltracker.com/services/v3/projects",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "077ec945-bc9f-483b-9341-eadfb28e541e"
            }
          ]
        },
        {
          "id": "d5f67b43-ae6a-4908-b60f-25a957aa9445",
          "name": "getProjectsProjectMemberships",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/memberships"
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all memberships for a project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d503659-209b-4940-bdc7-32a9bb7bc62e"
            }
          ]
        },
        {
          "id": "135c25f8-6691-40d7-96ad-13f92b8fd7e8",
          "name": "postProjectsProjectMemberships",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/memberships"
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new membership to a project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d58efe4b-163c-49ee-9758-6c018661e959"
            }
          ]
        },
        {
          "id": "19547d44-57f6-4ce0-93ee-466bb70692cc",
          "name": "getProjectsProjectMembershipsMembership",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/memberships/:MEMBERSHIP_ID"
              ],
              "variable": [
                {
                  "id": "MEMBERSHIP_ID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a single membership."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5d487d7-0936-4cee-b099-886fcdcb98bb"
            }
          ]
        },
        {
          "id": "37d28e80-d426-4d9a-85bd-b94ff493e90b",
          "name": "deleteProjectsProjectMembershipsMembership",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/memberships/:MEMBERSHIP_ID"
              ],
              "variable": [
                {
                  "id": "MEMBERSHIP_ID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete projects project memberships membership."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "babbddbd-fcd2-40e2-a456-c980c1cce27a"
            }
          ]
        },
        {
          "id": "0d9ef01b-e660-4770-9a3d-3e1dd9c82715",
          "name": "getProjectsProjectIterations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/iterations"
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves all iterations, with stories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acbf94d8-050e-4632-a277-2ffa587bec0a"
            }
          ]
        },
        {
          "id": "be78db1b-78d2-4154-a8c1-dab2216d2b5a",
          "name": "getProjectsProjectIterationsDone",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/iterations/done"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves iterations from the \"done\" group, with stories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60e1212f-ec2d-467c-b77d-29cc8ef689df"
            }
          ]
        },
        {
          "id": "f99777c6-0df0-4b1e-b207-c0a7bd9f48ff",
          "name": "getProjectsProjectIterationsCurrent",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/iterations/current"
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves iterations from the \"current\" group, with stories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9f570f3-73d7-4384-a682-5a534a4b6321"
            }
          ]
        },
        {
          "id": "317e6cea-2624-49d7-ad8a-7d6d8efd7f36",
          "name": "getProjectsProjectIterationsBacklog",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/iterations/backlog"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves iterations from the \"backlog\" group, with stories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "255b823d-47d5-4ce1-a79d-2ac9f9f0d94d"
            }
          ]
        },
        {
          "id": "4c7fe7d4-0ff9-4d4f-816e-c568365aa52e",
          "name": "getProjectsProjectIterationsCurrentBacklog",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/iterations/current_backlog"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves iterations from the \"current\" and \"backlog\" groups, with stories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15a18728-abe8-4d85-8fc0-7e1932224f82"
            }
          ]
        },
        {
          "id": "64e6b895-3592-4a23-806d-8cbf0f51b16c",
          "name": "getProjectsProjectStoriesStory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.pivotaltracker.com",
              "path": [
                "services",
                "v3",
                "projects/:PROJECT_ID/stories/:STORY_ID"
              ],
              "variable": [
                {
                  "id": "PROJECT_ID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "STORY_ID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a single story."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a4427d0-1388-4518-898b-8c0802f75f7d"
            }
          ]
        }
      ]
    }
  ]
}