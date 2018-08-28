---
swagger: "2.0"
x-collection-name: Expedia
x-complete: 0
info:
  title: Expedia Mobile Image
  description: Mobile API Flight Mobile Image Operation
  version: 0.0.1
host: apim.expedia.com
basePath: x/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/flight/image:
    get:
      summary: Flight Image
      description: Mobile API Flight Image Operation
      operationId: flights-image
      x-api-path-slug: apiflightimage-get
      parameters:
      - in: query
        name: destinationCode
        description: The three letter airport code or metro code of the destination
      - in: query
        name: imageHeight
        description: Requested height of the image
      - in: query
        name: imageWidth
        description: Requested width of the image
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Images
      - Airlines
  /api/mobile/image:
    get:
      summary: Mobile Image
      description: Mobile API Flight Mobile Image Operation
      operationId: flights-mobile-image
      x-api-path-slug: apimobileimage-get
      parameters:
      - in: query
        name: imageCode
        description: image primary key, for example CAR:ECONOMY ACTIVITY:DISNEY DESTINATION:JFK
          DESTINATIONMOBILEWEB:JFK CARMOBILEWEB:MINI
      - in: query
        name: imageHeight
        description: Requested height of the image
      - in: query
        name: imageType
        description: type of image
      - in: query
        name: imageWidth
        description: Requested width of the image
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Images
      - Airlines
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