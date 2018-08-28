---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Request Price
  version: 1.0.0
  description: Post request price.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/payment/promocode/price:
    post:
      summary: Post Payment Promocode Price
      description: Post payment promocode price.
      operationId: postApiV1PaymentPromocodePrice
      x-api-path-slug: apiv1paymentpromocodeprice-post
      parameters:
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Promocode
      - Price
  /api/v1/request/price:
    post:
      summary: Post Request Price
      description: Post request price.
      operationId: postApiV1RequestPrice
      x-api-path-slug: apiv1requestprice-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Request
      - Price
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