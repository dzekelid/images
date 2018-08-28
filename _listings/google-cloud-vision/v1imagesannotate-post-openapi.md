---
swagger: "2.0"
x-collection-name: Google Cloud Vision
x-complete: 0
info:
  title: Google Cloud Vision API Run Image Detection
  description: Run image detection and annotation for a batch of images.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: vision.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/images:annotate:
    post:
      summary: Run Image Detection
      description: Run image detection and annotation for a batch of images.
      operationId: vision.images.annotate
      x-api-path-slug: v1imagesannotate-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Image Detection
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