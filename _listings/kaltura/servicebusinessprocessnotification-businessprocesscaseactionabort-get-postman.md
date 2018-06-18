{
  "info": {
    "name": "Kaltura VPaaS Get Service Businessprocessnotification Businessprocesscase Action Abort",
    "_postman_id": "8b523917-660c-49b4-990a-f2adba9a8043",
    "description": "Abort business-process case",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "bbde58d9-edce-43e8-8bc4-23f8f4c4f324",
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
              "id": "1266de45-2631-4e50-b0eb-851505ff3715"
            }
          ]
        }
      ]
    }
  ]
}