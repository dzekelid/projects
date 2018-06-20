{
  "info": {
    "name": "Learnifier Gets Organization Unit by external id",
    "_postman_id": "06026cd6-3a0a-4327-a512-e7c7c6351d43",
    "description": "Gets an Organization Unit by external id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "f0410ec1-625e-42ca-a985-bdde498e4b2a",
          "name": "extproject.get",
          "request": {
            "url": "http://learnifier.com/extproject?extid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets an Organization Unit by external id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "464e1f55-e548-48b0-b935-e5e4151db4c1"
            }
          ]
        }
      ]
    }
  ]
}