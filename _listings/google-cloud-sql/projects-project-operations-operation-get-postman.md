{
  "info": {
    "name": "Google Cloud SQL API Get Projects Project Operations Operation",
    "_postman_id": "9abedaba-fa3b-49f7-9608-c0a1378e49f5",
    "description": "Retrieves an instance operation that has been performed on an instance.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "projects",
      "item": [
        {
          "id": "871674a3-c9fb-496d-816c-5c775b5224cb",
          "name": "sql.operations.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "sql",
                "v1beta4",
                "projects/:project/operations/:operation"
              ],
              "variable": [
                {
                  "id": "operation",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Retrieves an instance operation that has been performed on an instance"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c04458de-a945-43cd-b70a-aa45bf8fd995"
            }
          ]
        }
      ]
    }
  ]
}