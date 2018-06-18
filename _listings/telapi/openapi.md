---
swagger: "2.0"
x-collection-name: TelAPI
x-complete: 1
info:
  title: hetras Hotel API Version 0
  version: v0
host: api.hetras-certification.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates/{businessDay}:
    get:
      summary: Get the setup of a daily rate for a specific business day and rateplan.
      description: Read the setup of the daily rate for the defined rateplan for that
        specific business day.
      operationId: RatePlans_GetRate
      x-api-path-slug: apihotelv0hotelshotelidrateplansrateplancoderatesbusinessday-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: businessDay
        description: The business day you want to get the rate setup for
      - in: path
        name: hotelId
        description: The hotel id the rateplan belongs to
      - in: path
        name: rateplanCode
        description: The code of the rateplan you want to see details for
      responses:
        200:
          description: OK
      tags:
      - Setup
      - Of
      - Daily
      - Ratea
      - Specific
      - Business
      - Day
      - Rateplan
    patch:
      summary: Partially update a rate of the specified rateplan for a defined business
        day.
      description: "The hetras API is using this Patch Specification\r\n            to
        partially update an existing resource. Currently this call only allows to
        set the base price for non-derived rateplans if the rateplan\r\n            is
        active and already loaded for the specified business day.\r\n            \r\n
        \           A request example:\r\n            [\r\n              {\r\n                \"op\":
        \"replace\", \"path\": \"/base_price\", \"value\": 120.00\r\n              }\r\n
        \           ]\r\n            \r\n            For more details on how the API
        responds to errors please check our documentation on \r\n            Error
        Handling."
      operationId: RatePlans_PatchRate
      x-api-path-slug: apihotelv0hotelshotelidrateplansrateplancoderatesbusinessday-patch
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: businessDay
        description: The business day of the daily rate you want to update
      - in: path
        name: hotelId
        description: The hotel id the rateplan belongs to
      - in: body
        name: patchRequest
        description: A set of JSON Patch operations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: rateplanCode
        description: The code of the rateplan you want to update the daily rate details
          for
      responses:
        200:
          description: OK
      tags:
      - Partially
      - Update
      - Rate
      - Of
      - Specified
      - Rateplana
      - Defined
      - Business
      - Day
---