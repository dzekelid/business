{
  "info": {
    "name": "Kaltura VPaaS Get Service Businessprocessnotification Businessprocessserver Action Delete",
    "_postman_id": "61933a2e-454b-4f20-8ea2-c255a2cf2b07",
    "description": "Delete an Business-Process server object",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "820903e2-677e-41c0-bef6-ae8de45822db",
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
              "id": "759b3325-30d6-4b80-9857-8354a9e0818e"
            }
          ]
        },
        {
          "id": "138166ff-36a0-453c-a53d-e41b6d93ec61",
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
              "id": "2690c7fc-b422-45ab-8fd2-85a32032f73a"
            }
          ]
        },
        {
          "id": "65103a76-916d-43fe-9ee2-e4d2721aaec3",
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
              "id": "6ac85cf5-5a96-4a5d-b26c-a842dfe72842"
            }
          ]
        },
        {
          "id": "14046d2e-c690-4275-8d30-b26720ea367f",
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
              "id": "dd6cafa3-5c81-41a4-bdb3-9e25b25e77da"
            }
          ]
        },
        {
          "id": "886757f9-1dae-43be-98e6-eacb40cf82c4",
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
              "id": "18e8b827-e681-4210-8569-9f2618c8fdf7"
            }
          ]
        }
      ]
    }
  ]
}