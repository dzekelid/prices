---
swagger: "2.0"
x-collection-name: SAP
x-complete: 0
info:
  title: SAP Manufacturing Network Customer APIs Creates a production option without
    pricing
  description: "Creates a new production option without an initial pricing.  \nThis
    endpoint is used by users from the additive manufactuirng supplier that're not
    collaboration leads."
  version: 1.0.0
host: hostname
basePath: /dim/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /collaborationRooms/{collaborationRoomId}/productionData/basic:
    post:
      summary: Creates a production option without pricing
      description: "Creates a new production option without an initial pricing.  \nThis
        endpoint is used by users from the additive manufactuirng supplier that're
        not collaboration leads."
      operationId: creates-a-new-production-option-without-an-initial-pricing--this-endpoint-is-used-by-users-from-the-
      x-api-path-slug: collaborationroomscollaborationroomidproductiondatabasic-post
      parameters:
      - in: body
        name: AdditionalProductionDataBasicCreateRequest
        description: A request about creating a production option without pricing
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: collaborationRoomId
        description: The ID of a collaboration room
      responses:
        200:
          description: Successful response
      tags:
      - Creates
      - Production
      - Option
      - Without
      - Pricing
  /collaborationRooms/{collaborationRoomId}/productionData/original/pricing:
    put:
      summary: Updates the pricing
      description: "Updates the initial pricing for the customer's production option.
        \ \nThe login user must be a collaboration lead from an additive manufacturing
        supplier.  \nNote: The planned quantity is defined by the customer and not
        available for update by the supplier."
      operationId: updates-the-initial-pricing-for-the-customers-production-option--the-login-user-must-be-a-collaborat
      x-api-path-slug: collaborationroomscollaborationroomidproductiondataoriginalpricing-put
      parameters:
      - in: path
        name: collaborationRoomId
        description: The ID of a collaboration room
      - in: body
        name: ProductionDataPricingRequest
        description: A request about updating the pricing of a production option
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - S
      - Pricing
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