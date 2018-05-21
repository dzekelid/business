---
swagger: "2.0"
x-collection-name: Barclays
x-complete: 1
info:
  title: Barclays
  description: this-is-an-openapi-definition-for-the-standard-set-of-open-banking-httpopenbankingapisio-apis-for-barclays
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: atlas.api.barclays
basePath: open-banking/v2.1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  business-current-accounts/:
    get:
      summary: Get Current Business Accounts
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple BCA products.
      operationId: getCurentBusinessAccounts
      x-api-path-slug: businesscurrentaccounts-get
      responses:
        200:
          description: OK
      tags:
      - Business
      - Current
      - Accounts
---