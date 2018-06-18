{
  "info": {
    "name": "Kaltura VPaaS Get Service Businessprocessnotification Businessprocesscase Action Servediagram",
    "_postman_id": "5f9c8296-fb74-4fa5-8d7d-0a31289b9238",
    "description": "Server business-process case diagram",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "8b2f38e2-4666-4980-b551-51f648af2d72",
          "name": "businessProcessCase.abort",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocesscase/action/abort?businessProcessStartNotificationTemplateId=%7B%7D&No Name=%7B%7D&objectId=%7B%7D&objectType=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Abort business-process case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d3f8a87-1f14-4ffe-8b46-52f39f8f382c"
            }
          ]
        },
        {
          "id": "207fd44e-905d-4e45-ad03-dd5db53fdb4e",
          "name": "businessProcessCase.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocesscase/action/list?No Name=%7B%7D&objectId=%7B%7D&objectType=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "list business-process cases"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3092e9cc-9304-4d69-b609-b60056088f6c"
            }
          ]
        },
        {
          "id": "ef94a024-573d-475b-8329-3e9e78c8858c",
          "name": "businessProcessCase.serveDiagram",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocesscase/action/serveDiagram?businessProcessStartNotificationTemplateId=%7B%7D&No Name=%7B%7D&objectId=%7B%7D&objectType=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Server business-process case diagram"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1cc0177f-e334-4721-adde-2ca1408a978f"
            }
          ]
        }
      ]
    }
  ]
}