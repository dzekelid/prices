swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 1
info:
  title: LH Public
  version: "1.0"
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