---
swagger: "2.0"
x-collection-name: Site24x7
x-complete: 1
info:
  title: Business Hours API
  description: the-business-hours-api-
  version: 1.0.0
host: www.site24x7.com.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /business_hours:
    post:
      summary: Create Business Hour
      description: Create a new Business Hour.
      operationId: create-business-hour
      x-api-path-slug: business-hours-post
      parameters:
      - in: path
        name: "display_name\n        \n        \n            required\n            Display
          name for the Business Hour.\n        \n    \n    \n        \n        description\n
          \       \n        \n            optional\n            Description for the
          Business Hour"
      responses:
        Maximum record size:
          description: 100 KiB
        Maximum number of records per datastore:
          description: "100,000"
        Maximum datastore size:
          description: 10 MiB
        Maximum size of a delta:
          description: 2 MiB
      tags:
      - Business Hours
    get:
      summary: List Business Hours
      description: List of all Business Hours.
      operationId: list-business-hours
      x-api-path-slug: business-hours-get
      parameters:
      - in: path
        name: "background_color\n        \n        \n            string\n            Back
          ground color for your reports.\n        \n                \n    \n        \n
          \       foreground_color\n        \n        \n            string\n            Foreground
          ground color for your r"
      responses:
        Maximum record size:
          description: 100 KiB
        Maximum number of records per datastore:
          description: "100,000"
        Maximum datastore size:
          description: 10 MiB
        Maximum size of a delta:
          description: 2 MiB
      tags:
      - Business Hours
  /business_hours/{business_hours_id}:
    put:
      summary: Update Business Hour
      description: Update an existing Business Hour.
      operationId: update-business-hour
      x-api-path-slug: business-hoursbusiness-hours-id-put
      parameters:
      - in: path
        name: "display_name\n        \n        \n            required\n            Display
          name for the Business Hour.\n        \n    \n    \n        \n        description\n
          \       \n        \n            optional\n            Description for the
          Business Hour"
      responses:
        Maximum record size:
          description: 100 KiB
        Maximum number of records per datastore:
          description: "100,000"
        Maximum datastore size:
          description: 10 MiB
        Maximum size of a delta:
          description: 2 MiB
      tags:
      - Business Hours
---