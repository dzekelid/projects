{
  "info": {
    "name": "Google Cloud DNS API Get Project",
    "_postman_id": "730983e6-85c0-4e3d-86ec-b2d285ec100b",
    "description": "Fetch the representation of an existing Project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Project",
      "item": [
        {
          "id": "3083d338-35b1-4e57-b3ae-ef7f74ddd48c",
          "name": "dns.projects.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "dns",
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
            "description": "Fetch the representation of an existing Project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "330b48b4-8779-46c4-970e-8e4ebc2515f5"
            }
          ]
        }
      ]
    }
  ]
}