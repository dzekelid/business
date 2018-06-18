{
  "info": {
    "name": "Kaltura VPaaS Get Service Businessprocessnotification Businessprocessserver Action Updatestatus",
    "_postman_id": "c36c5bd3-bced-4c65-9511-480e8e45f293",
    "description": "Update Business-Process server status by id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "ffd2d14c-ef48-4747-b5b8-9541ab3773ff",
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
              "id": "b234c690-32b8-4803-885a-97f0cec8dd70"
            }
          ]
        },
        {
          "id": "40d7fe38-9216-4688-a267-c1baf8e94775",
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
              "id": "ad857aa5-ad2d-4df1-b409-bfeebe5dd053"
            }
          ]
        },
        {
          "id": "5b5a2ebc-b5ea-413c-bc00-fe9226b4f1fa",
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
              "id": "a405d826-d7e7-4c79-9b9d-070eda566e54"
            }
          ]
        },
        {
          "id": "0b05e562-91e8-48a2-8191-518e72660df0",
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
              "id": "2c62d024-f134-4f7b-9576-592c99a45231"
            }
          ]
        },
        {
          "id": "481e91be-bad9-4061-ab2c-b6a176e0ee76",
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
              "id": "e9d9d203-a747-488f-bf8b-2da4f98f47e9"
            }
          ]
        },
        {
          "id": "36eba9e5-083a-40bb-9283-328e75db75be",
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
              "id": "074f711c-322b-43a5-86e4-dd21fb915f2c"
            }
          ]
        },
        {
          "id": "0b5b7d2f-6464-46aa-88fe-88548c363064",
          "name": "businessProcessServer.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocessserver/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[currentDcOrExternal]=%7B%7D&filter[currentDc]=%7B%7D&filter[dcEqOrNull]=%7B%7D&filter[dcEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[idNotIn]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotEqual]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[typeEqual]=%7B%7D&filter[typeIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "list Business-Process server objects"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eeceb535-ee7a-40e5-b983-e8c536f486a3"
            }
          ]
        },
        {
          "id": "030f7a83-ddca-40a4-8d1e-25bea0555fac",
          "name": "businessProcessServer.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocessserver/action/update?businessProcessServer[dc]=%7B%7D&businessProcessServer[description]=%7B%7D&businessProcessServer[host]=%7B%7D&businessProcessServer[name]=%7B%7D&businessProcessServer[objectType]=%7B%7D&businessProcessServer[password]=%7B%7D&businessProcessServer[port]=%7B%7D&businessProcessServer[protocol]=%7B%7D&businessProcessServer[systemName]=%7B%7D&businessProcessServer[username]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update an existing Business-Process server object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88a66b04-5ff3-447b-a5d0-04fcf06754d0"
            }
          ]
        },
        {
          "id": "489a5587-4fe2-422c-9da6-3a296240063f",
          "name": "businessProcessServer.updateStatus",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/businessprocessnotification_businessprocessserver/action/updateStatus?id=%7B%7D&No Name=%7B%7D&status=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Business-Process server status by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a35f106-29fc-46ad-a46d-fc018745ed18"
            }
          ]
        }
      ]
    }
  ]
}