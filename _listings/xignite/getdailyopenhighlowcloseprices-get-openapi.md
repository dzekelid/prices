---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Bonds Get Daily Open High Low Close Prices
  description: Returns daily Open, High, Low, Close (OHLC) prices for the list of
    bonds specified in the input. Daily OHLC data is provided for the most recent
    date for which data is provided by the price source. Each DailyOpenHighLowClosePrice
    object  returned counts as one hit.
  version: 1.0.0
host: bonds.xignite.com
basePath: xBonds.json/XigniteBonds
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetDailyOpenHighLowClosePrices:
    get:
      summary: Get Daily Open High Low Close Prices
      description: Returns daily Open, High, Low, Close (OHLC) prices for the list
        of bonds specified in the input. Daily OHLC data is provided for the most
        recent date for which data is provided by the price source. Each DailyOpenHighLowClosePrice
        object  returned counts as one hit.
      operationId: GetDailyOpenHighLowClosePrices
      x-api-path-slug: getdailyopenhighlowcloseprices-get
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
      - Daily
      - Open
      - High
      - Low
      - Close
      - Prices
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