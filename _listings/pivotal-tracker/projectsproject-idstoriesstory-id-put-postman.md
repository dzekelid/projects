{
  "info": {
    "name": "Pivotal Tracker Put Projects Project Stories Story",
    "_postman_id": "169003e9-8702-4f43-802b-cf33b1ed8806",
    "description": "Put projects project stories story.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "34bdcee1-315e-40f8-83cc-22726e2ee434",
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
              "id": "422fa7d1-07cf-46bd-83fd-ad2ec4a95336"
            }
          ]
        },
        {
          "id": "8262401e-2255-4b29-a7a2-1d7ba0ec273a",
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
              "id": "5ec790a9-cfa7-43fd-b58b-ad46e614ddc8"
            }
          ]
        },
        {
          "id": "db576611-0991-4841-8a88-38239359f8ad",
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
              "id": "22abf936-13e2-4f1a-85ad-c6ce0ccedd77"
            }
          ]
        },
        {
          "id": "89a3916a-0157-4636-9763-c2e3e05e9293",
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
              "id": "a4e633ab-45ae-4c58-8ee9-579fd6a320f0"
            }
          ]
        },
        {
          "id": "ccd94799-72a4-41e2-ad8a-4cd6719c282c",
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
              "id": "c5c4ad1d-c404-4555-81c5-7ba3212b0f0a"
            }
          ]
        },
        {
          "id": "1b204a0e-b6af-4988-891b-098dc67732e8",
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
              "id": "89bc275a-02d6-481a-ab0b-500eacd4f39a"
            }
          ]
        },
        {
          "id": "c08cdf56-8c8e-4ff8-b79a-50d5aba11072",
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
              "id": "285ae3d7-d653-4e08-b00f-9edabf84ecf9"
            }
          ]
        },
        {
          "id": "f655d7ea-bb8e-44ad-b77d-ac13b96d2806",
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
              "id": "fc8312ca-5694-4ec2-9028-0290d0630ffd"
            }
          ]
        },
        {
          "id": "d9fb4362-c41b-4947-a0bf-38b65672249e",
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
              "id": "1a0c4ed0-0054-41cd-9561-011256b2ce6a"
            }
          ]
        },
        {
          "id": "52e59259-be05-4d19-8d7a-9925d60a226f",
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
              "id": "fe20e8a3-8c96-4652-8179-168715882e9a"
            }
          ]
        },
        {
          "id": "d4f78b8c-953e-4122-8011-750297e50778",
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
              "id": "4289ab52-40f8-4ea0-8160-7c63e030c733"
            }
          ]
        },
        {
          "id": "9cb7a9a5-5635-42b4-86b3-71255b234b22",
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
              "id": "1e38b6d4-ba49-418a-a62d-7f27f749c4f5"
            }
          ]
        },
        {
          "id": "b242c3e2-7815-4048-a7af-55d49965ee73",
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
              "id": "5f8e1836-c0a4-44ca-9376-f73d9ae4acd3"
            }
          ]
        },
        {
          "id": "8e2d9bbc-2853-450a-b7cd-9747d636f20c",
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
              "id": "85deb289-54a9-46a3-a998-b22a3f7ca962"
            }
          ]
        },
        {
          "id": "a459cef0-475b-4ada-8556-955dcb0fa91e",
          "name": "putProjectsProjectStoriesStory",
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
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Put projects project stories story."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f13ff218-3741-439c-9c86-91a8f3698d7b"
            }
          ]
        }
      ]
    }
  ]
}