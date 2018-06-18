---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Businessprocessnotification Businessprocessserver
    Action Get
  description: Retrieve an Business-Process server object by id
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/businessprocessnotification_businessprocesscase/action/abort:
    get:
      summary: Get Service Businessprocessnotification Businessprocesscase Action
        Abort
      description: Abort business-process case
      operationId: businessProcessCase.abort
      x-api-path-slug: servicebusinessprocessnotification-businessprocesscaseactionabort-get
      parameters:
      - in: query
        name: businessProcessStartNotificationTemplateId
      - in: query
        name: No Name
      - in: query
        name: objectId
      - in: query
        name: objectType
        description: 'Enum Type: `KalturaEventNotificationEventObjectType`'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocesscase
      - Action
      - Abort
  /service/businessprocessnotification_businessprocesscase/action/list:
    get:
      summary: Get Service Businessprocessnotification Businessprocesscase Action
        List
      description: list business-process cases
      operationId: businessProcessCase.list
      x-api-path-slug: servicebusinessprocessnotification-businessprocesscaseactionlist-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: objectId
      - in: query
        name: objectType
        description: 'Enum Type: `KalturaEventNotificationEventObjectType`'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocesscase
      - Action
      - List
  /service/businessprocessnotification_businessprocesscase/action/serveDiagram:
    get:
      summary: Get Service Businessprocessnotification Businessprocesscase Action
        Servediagram
      description: Server business-process case diagram
      operationId: businessProcessCase.serveDiagram
      x-api-path-slug: servicebusinessprocessnotification-businessprocesscaseactionservediagram-get
      parameters:
      - in: query
        name: businessProcessStartNotificationTemplateId
      - in: query
        name: No Name
      - in: query
        name: objectId
      - in: query
        name: objectType
        description: 'Enum Type: `KalturaEventNotificationEventObjectType`'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocesscase
      - Action
      - ServeDiagram
  /service/businessprocessnotification_businessprocessserver/action/add:
    get:
      summary: Get Service Businessprocessnotification Businessprocessserver Action
        Add
      description: Allows you to add a new Business-Process server object
      operationId: businessProcessServer.add
      x-api-path-slug: servicebusinessprocessnotification-businessprocessserveractionadd-get
      parameters:
      - in: query
        name: businessProcessServer[dc]
        description: The dc of the server
      - in: query
        name: businessProcessServer[description]
      - in: query
        name: businessProcessServer[host]
      - in: query
        name: businessProcessServer[name]
      - in: query
        name: businessProcessServer[objectType]
      - in: query
        name: businessProcessServer[password]
      - in: query
        name: businessProcessServer[port]
      - in: query
        name: businessProcessServer[protocol]
        description: 'Enum Type: `KalturaActivitiBusinessProcessServerProtocol`'
      - in: query
        name: businessProcessServer[systemName]
      - in: query
        name: businessProcessServer[username]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocessserver
      - Action
      - Add
  /service/businessprocessnotification_businessprocessserver/action/delete:
    get:
      summary: Get Service Businessprocessnotification Businessprocessserver Action
        Delete
      description: Delete an Business-Process server object
      operationId: businessProcessServer.delete
      x-api-path-slug: servicebusinessprocessnotification-businessprocessserveractiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocessserver
      - Action
      - Delete
  /service/businessprocessnotification_businessprocessserver/action/get:
    get:
      summary: Get Service Businessprocessnotification Businessprocessserver Action
        Get
      description: Retrieve an Business-Process server object by id
      operationId: businessProcessServer.get
      x-api-path-slug: servicebusinessprocessnotification-businessprocessserveractionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocessserver
      - Action
      - Get
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---