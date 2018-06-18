---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Businessprocessnotification Businessprocesscase
    Action Servediagram
  description: Server business-process case diagram
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