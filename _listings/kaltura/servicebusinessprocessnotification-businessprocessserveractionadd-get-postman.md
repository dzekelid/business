{
  "info": {
    "name": "Kaltura VPaaS Get Service Businessprocessnotification Businessprocessserver Action Add",
    "_postman_id": "79c7cba5-e56c-4962-99c1-696b2211cf0c",
    "description": "Allows you to add a new Business-Process server object",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "39c8aa10-368c-4c4c-8302-f8b3565d9bb5",
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
              "id": "1c86fc6a-fbf1-4952-b63b-1a574f93537b"
            }
          ]
        },
        {
          "id": "18aebffa-55d8-433b-95be-5a20b3818f7c",
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
              "id": "16a09e27-e08e-4aa6-8928-f3aa402ef0b3"
            }
          ]
        },
        {
          "id": "2271459c-1eb6-47fc-89bd-df81bd70ca9f",
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
              "id": "3d013c5e-b162-4492-929a-3e341b2ad696"
            }
          ]
        },
        {
          "id": "1de5a287-265d-412c-b5e5-8bb4b3ed72fc",
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
              "id": "4becd003-ee83-4481-a2a7-cbc5a525cecb"
            }
          ]
        }
      ]
    }
  ]
}