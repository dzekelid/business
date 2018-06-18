{
  "info": {
    "name": "Kaltura VPaaS Get Service Businessprocessnotification Businessprocessserver Action Get",
    "_postman_id": "8230713b-78e9-4cce-aaa9-214603ec7b7b",
    "description": "Retrieve an Business-Process server object by id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "3f1409c9-2306-4123-b8f0-acfa0b9f5139",
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
              "id": "ed1e4825-d208-494a-8707-d7d50ec799a7"
            }
          ]
        },
        {
          "id": "910efefc-81b5-45e8-bc9f-0e9699f8a0a5",
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
              "id": "8da960b2-7ea3-4115-8897-79b7ea502083"
            }
          ]
        },
        {
          "id": "8369b130-7e95-466d-8cc6-bd41d4d4e72c",
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
              "id": "3c4b43e1-9c23-42b3-8d5f-977fb904d2f0"
            }
          ]
        },
        {
          "id": "dcb2d782-df2f-4c30-b6af-9c39e3c725e7",
          "name": "businessProcessServer.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocessserver/action/add?businessProcessServer[dc]=%7B%7D&businessProcessServer[description]=%7B%7D&businessProcessServer[host]=%7B%7D&businessProcessServer[name]=%7B%7D&businessProcessServer[objectType]=%7B%7D&businessProcessServer[password]=%7B%7D&businessProcessServer[port]=%7B%7D&businessProcessServer[protocol]=%7B%7D&businessProcessServer[systemName]=%7B%7D&businessProcessServer[username]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows you to add a new Business-Process server object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c786e469-e03d-4eab-b4af-46188c6fc261"
            }
          ]
        },
        {
          "id": "89e1b3fc-7ac0-412a-8031-d53ccaf2dcce",
          "name": "businessProcessServer.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocessserver/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete an Business-Process server object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f9778ef-cae1-41b5-bced-9e85aa1059be"
            }
          ]
        },
        {
          "id": "250814c6-3430-4e7f-bb1b-827d285fb551",
          "name": "businessProcessServer.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocessserver/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve an Business-Process server object by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09703754-5ad5-449a-8c3c-618d9ffa86b4"
            }
          ]
        }
      ]
    }
  ]
}