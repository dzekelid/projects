{
  "info": {
    "name": "Google Cloud SQL API Get Projects Project Operations",
    "_postman_id": "49c3e5a3-fb15-4787-97c2-f99804ee95f3",
    "description": "Lists all instance operations that have been performed on the given Cloud SQL instance in the reverse chronological order of the start time.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "projects",
      "item": [
        {
          "id": "13dff0df-a0e7-4e17-8a47-9f5087bf6848",
          "name": "sql.operations.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "sql",
                "v1beta4",
                "projects/:project/operations"
              ],
              "query": [
                {
                  "key": "instance",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "maxResults",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageToken",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "project",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all instance operations that have been performed on the given Cloud SQL instance in the reverse chronological order of the start time"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b79e40da-fcc0-420c-9948-5d9d54907fea"
            }
          ]
        }
      ]
    }
  ]
}