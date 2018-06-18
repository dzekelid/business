---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Businessprocessnotification Businessprocessserver
    Action Updatestatus
  description: Update Business-Process server status by id
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
  /service/businessprocessnotification_businessprocessserver/action/list:
    get:
      summary: Get Service Businessprocessnotification Businessprocessserver Action
        List
      description: list Business-Process server objects
      operationId: businessProcessServer.list
      x-api-path-slug: servicebusinessprocessnotification-businessprocessserveractionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[currentDcOrExternal]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[currentDc]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[dcEqOrNull]
      - in: query
        name: filter[dcEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[idNotIn]
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[partnerIdEqual]
      - in: query
        name: filter[partnerIdIn]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaBusinessProcessServerStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[statusNotEqual]
        description: 'Enum Type: `KalturaBusinessProcessServerStatus`'
      - in: query
        name: filter[statusNotIn]
      - in: query
        name: filter[typeEqual]
        description: 'Enum Type: `KalturaBusinessProcessProvider`'
      - in: query
        name: filter[typeIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocessserver
      - Action
      - List
  /service/businessprocessnotification_businessprocessserver/action/update:
    get:
      summary: Get Service Businessprocessnotification Businessprocessserver Action
        Update
      description: Update an existing Business-Process server object
      operationId: businessProcessServer.update
      x-api-path-slug: servicebusinessprocessnotification-businessprocessserveractionupdate-get
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
      - Update
  /service/businessprocessnotification_businessprocessserver/action/updateStatus:
    get:
      summary: Get Service Businessprocessnotification Businessprocessserver Action
        Updatestatus
      description: Update Business-Process server status by id
      operationId: businessProcessServer.updateStatus
      x-api-path-slug: servicebusinessprocessnotification-businessprocessserveractionupdatestatus-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      - in: query
        name: status
        description: 'Enum Type: `KalturaBusinessProcessServerStatus`'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Businessprocessnotification
      - Businessprocessserver
      - Action
      - UpdateStatus
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