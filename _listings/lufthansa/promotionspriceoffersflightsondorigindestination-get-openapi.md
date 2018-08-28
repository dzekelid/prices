---
swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 0
info:
  title: LH Partner Price Offers
  version: "1.0"
  description: Retrieve a best price offer given an origin and destination.
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /promotions/priceoffers/flights/ond/{origin}/{destination}:
    get:
      summary: Price Offers
      description: Retrieve a best price offer given an origin and destination.
      operationId: promotions.priceoffers.flights.ond.origin.destination.get
      x-api-path-slug: promotionspriceoffersflightsondorigindestination-get
      parameters:
      - in: query
        name: departureDate
        description: Departure date in local time (YYYY-MM-DD)
      - in: path
        name: destination
        description: Destination city
      - in: path
        name: origin
        description: Departure city
      - in: query
        name: returnDate
        description: Return date in local time (YYYY-MM-DD)
      - in: query
        name: service
        description: Optional parameter
      responses:
        200:
          description: OK
      tags:
      - Price
      - Offers
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