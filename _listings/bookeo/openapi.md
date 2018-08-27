swagger: "2.0"
x-collection-name: Bookeo
x-complete: 1
info:
  title: Bookeo
  version: 1.0.0
host: api.bookeo.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /settings/business:
    get:
      summary: Get information, location and contact details about the business
      description: Get information, location and contact details about the business.
      operationId: getSettingsBusiness
      x-api-path-slug: settingsbusiness-get
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Business