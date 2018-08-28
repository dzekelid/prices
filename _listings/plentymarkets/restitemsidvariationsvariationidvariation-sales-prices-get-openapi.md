---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List sales prices of a variation
  description: Lists the sales prices of a variation. The ID of the variation must
    be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/items/sales_prices:
    get:
      summary: List sales prices
      description: Lists all sales prices.
      operationId: getRestItemsSalesPrices
      x-api-path-slug: restitemssales-prices-get
      parameters:
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      responses:
        200:
          description: OK
      tags:
      - List
      - Sales
      - Prices
  /rest/items/variations/variation_sales_prices:
    post:
      summary: Bulk create prices
      description: Creates up to 50 prices of variations. The ID of the variation,
        the ID of the sales price and a price must be specified.
      operationId: postRestItemsVariationsVariationSalesPrices
      x-api-path-slug: restitemsvariationsvariation-sales-prices-post
      parameters:
      - in: body
        name: /rest/items/variations/variation_sales_prices
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Create
      - Prices
    put:
      summary: Bulk update prices
      description: Updates up to 50 prices of variations. The ID of the variation,
        the ID of the sales price and a price must be specified.
      operationId: putRestItemsVariationsVariationSalesPrices
      x-api-path-slug: restitemsvariationsvariation-sales-prices-put
      parameters:
      - in: body
        name: /rest/items/variations/variation_sales_prices
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Update
      - Prices
  /rest/items/{id}/variations/{variationId}/variation_sales_prices:
    delete:
      summary: Delete all links between a variation and its sales prices
      description: Deletes all links between a variation and its sales prices and
        deletes the sales price data. The ID of the variation must be specified.
      operationId: deleteRestItemsVariationsVariationVariationSalesPrices
      x-api-path-slug: restitemsidvariationsvariationidvariation-sales-prices-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Links
      - Between
      - Variation
      - Its
      - Sales
      - Prices
    get:
      summary: List sales prices of a variation
      description: Lists the sales prices of a variation. The ID of the variation
        must be specified.
      operationId: getRestItemsVariationsVariationVariationSalesPrices
      x-api-path-slug: restitemsidvariationsvariationidvariation-sales-prices-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Sales
      - Prices
      - Of
      - Variation
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