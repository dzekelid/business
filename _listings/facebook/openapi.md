---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 1
info:
  title: Facebook Graph (Achievement Type) API
  description: api-for-managing-facebook-achievement-types
  termsOfService: https://www.facebook.com/policies/
  version: 1.0.0
host: graph.facebook.com
basePath: /v3.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /&#123;user-id&#125;/business_activities:
    get:
      summary: Get User Business Activities
      description: User Business Activities
      operationId: getUserBusinessActivities
      x-api-path-slug: 123userid125business-activities-get
      parameters:
      - in: query
        name: "100"
        description: Invalid parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Business
      - Activities
  /&#123;user-id&#125;/businesses:
    get:
      summary: Get User Businesses
      description: User Businesses
      operationId: getUserBusinesses
      x-api-path-slug: 123userid125businesses-get
      parameters:
      - in: query
        name: permitted_rolesliststring
        description: Roles the user has on the business
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Businesses
  /&#123;user-id&#125;/ids_for_business:
    get:
      summary: Get User S For Business
      description: User IDs for Business
      operationId: getUserSForBusiness
      x-api-path-slug: 123userid125ids-for-business-get
      parameters:
      - in: query
        name: "100"
        description: Invalid parameter
        type: string
      - in: query
        name: "200"
        description: Permissions error
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - S
      - Business
---