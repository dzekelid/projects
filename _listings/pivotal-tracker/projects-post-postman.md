{
  "info": {
    "name": "Pivotal Tracker Post Projects",
    "_postman_id": "c2f52deb-ae9d-4768-866a-bcdb695eef72",
    "description": "Adds a new project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "59d43feb-5d41-488f-8ffb-ad48890a2e90",
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
              "id": "e82549dc-39ad-41e8-8b2a-d8c88a6c086e"
            }
          ]
        },
        {
          "id": "7e77e656-518f-4eb2-8367-d114fa7ff659",
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
              "id": "e75fb5fe-e41a-4d99-804a-9a1912298605"
            }
          ]
        },
        {
          "id": "63072803-965b-4b4f-9cfe-dc99fa20fee9",
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
              "id": "3111f134-4efe-4837-bd97-be2ba56d7f86"
            }
          ]
        },
        {
          "id": "7c3c1474-9c7d-4077-a72f-31faed027e2b",
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
              "id": "db3f34ce-437b-42ee-bc8f-cd5e4accd5fa"
            }
          ]
        }
      ]
    }
  ]
}