---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Historical Get Last Closing Prices Ordered Adjusted
  description: Returns last closing price for a collection of securities.This include
    the splits and dividends adjusted price
  version: 1.0.0
host: www.xignite.com
basePath: xHistorical.json/XigniteHistorical
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetLastClosingPrices:
    get:
      summary: Get Last Closing Prices
      description: Returns last closing price for a collection of securities.
      operationId: postGetlastclosingprices
      x-api-path-slug: getlastclosingprices-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Last
      - Closing
      - Prices
  /GetLastClosingPricesAdjusted:
    get:
      summary: Get Last Closing Prices Adjusted
      description: Returns last closing price for a collection of securities.This
        include the splits and dividends adjusted price
      operationId: postGetlastclosingpricesadjusted
      x-api-path-slug: getlastclosingpricesadjusted-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Last
      - Closing
      - Prices
      - Adjusted
  /GetLastClosingPricesOrdered:
    get:
      summary: Get Last Closing Prices Ordered
      description: Returns last closing price for a collection of securities.
      operationId: postGetlastclosingpricesordered
      x-api-path-slug: getlastclosingpricesordered-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Last
      - Closing
      - Prices
      - Ordered
  /GetLastClosingPricesOrderedAdjusted:
    get:
      summary: Get Last Closing Prices Ordered Adjusted
      description: Returns last closing price for a collection of securities.This
        include the splits and dividends adjusted price
      operationId: postGetlastclosingpricesorderedadjusted
      x-api-path-slug: getlastclosingpricesorderedadjusted-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Last
      - Closing
      - Prices
      - Ordered
      - Adjusted
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