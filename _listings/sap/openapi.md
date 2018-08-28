swagger: "2.0"
x-collection-name: SAP
x-complete: 1
info:
  title: SAP Translation Hub
  description: to-provide-users-of-software-in-a-global-market-with-texts-in-their-own-language-translations-are-required--sap-translation-hub-enables-you-to-draw-on-saps-translation-experience-across-multiple-products-and-languages-to-propose-translations-for-short-texts-
  contact:
    name: SAP Translation Hub team
    email: translationhub@sap.com
  version: 1.0.0
host: sandbox.api.sap.com
basePath: /translationhub/api/v1
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