swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 1
info:
  title: Content API for Shopping
  description: manages-product-items-inventory-and-merchant-center-accounts-for-google-shopping-
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /content/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{merchantId}/inventory/{storeCode}/products/{productId}:
    post:
      summary: Update Price
      description: Updates price and availability of a product in your Merchant Center
        account. This operation does not update the expiration date of the product.
        This method can only be called for non-multi-client accounts.
      operationId: content.inventory.set
      x-api-path-slug: merchantidinventorystorecodeproductsproductid-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: path
        name: productId
        description: The ID of the product for which to update price and availability
      - in: path
        name: storeCode
        description: The code of the store for which to update price and availability
      responses:
        200:
          description: OK
      tags:
      - Price