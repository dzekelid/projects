{
  "info": {
    "name": "Pivotal Tracker Get Projects Project Activities",
    "_postman_id": "cca53bee-2d37-4293-9147-b0bebb45a5d0",
    "description": "Retrieves the recent activity of a specific project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "e9be4f2d-c82d-4f53-a771-c81024287a89",
          "name": "getActivities",
          "request": {
            "url": "http://www.pivotaltracker.com/services/v3/activities?limit=%7B%7D&newer_than_version=%7B%7D&occurred_since_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the recent activity of all your projects."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f1a15a1-12ae-4c14-8728-963bf6ab0982"
            }
          ]
        }
      ]
    },
    {
      "name": "Projects",
      "item": [
        {
          "id": "0df95eaf-834d-4011-8b80-1751194e0781",
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
              "id": "9aae462f-4ab8-409f-bba8-cc3bfabb02b7"
            }
          ]
        }
      ]
    }
  ]
}