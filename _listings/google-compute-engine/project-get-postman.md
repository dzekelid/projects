{
  "info": {
    "name": "Google Compute Engine API Get Project",
    "_postman_id": "5f54c0fa-0f23-4eae-8734-7b4ca0cc6b83",
    "description": "Returns the specified Project resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Project",
      "item": [
        {
          "id": "c5ece2e3-2484-4280-af4b-0d9d115f825b",
          "name": "compute.projects.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "compute",
                "v1",
                "projects",
                ":project"
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
            "description": "Returns the specified Project resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df9b77cf-0a9d-4685-ae6f-9deefae071f7"
            }
          ]
        }
      ]
    }
  ]
}