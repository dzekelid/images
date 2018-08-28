---
swagger: "2.0"
x-collection-name: DigitalOcean
x-complete: 0
info:
  title: Digital Ocean Retrieve an existing Image by id
  description: "To retrieve information about an image (public or private), send a
    GET request to /v2/images/$IMAGE_ID.\r\n\r\nThe response will be a JSON object
    with a key called image. The value of this will be an image object containing
    the standard image attributes:"
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
  /images/63261821:
    get:
      summary: Retrieve an existing Image by id
      description: "To retrieve information about an image (public or private), send
        a GET request to /v2/images/$IMAGE_ID.\r\n\r\nThe response will be a JSON
        object with a key called image. The value of this will be an image object
        containing the standard image attributes:"
      operationId: Images63261821Get
      x-api-path-slug: images63261821-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Existing
      - Image
      - By
      - Id
    delete:
      summary: Delete an Image
      description: "To delete an image, send a DELETE request to /v2/images/$IMAGE_ID.\r\n\r\nA
        status of 204 will be given. This indicates that the request was processed
        successfully, but that no response body is needed"
      operationId: Images63261821Delete
      x-api-path-slug: images63261821-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Image
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