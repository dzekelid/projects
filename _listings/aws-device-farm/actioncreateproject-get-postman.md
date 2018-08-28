{
  "info": {
    "name": "AWS Device Farm API Create Project",
    "_postman_id": "70900dde-9eaa-4875-a6d0-b4aad6db134f",
    "description": "Creates a new project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Device Pool",
      "item": [
        {
          "id": "e31d6929-8675-457d-82eb-8e9059730a59",
          "name": "createDevicePool",
          "request": {
            "url": "http://example.com/api/?Action=CreateDevicePool?description=description&name=name&projectArn=projectArn&rules=rules",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a device pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "adf33129-2a5f-48e0-95e1-e9f67d27ea74"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "c0eab246-86a0-4926-81f3-56e5114a07fb",
          "name": "createProject",
          "request": {
            "url": "http://example.com/api/?Action=CreateProject?name=name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53114b92-781d-417c-bb69-82b73567abbc"
            }
          ]
        }
      ]
    }
  ]
}