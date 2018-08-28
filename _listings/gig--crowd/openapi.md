swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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