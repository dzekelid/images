---
swagger: "2.0"
info:
  title: Akamai API List Images Matching a URL
  description: List Images Matching a URL
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /imaging/v0/images:
    get:
      summary: List Images Matching a URL
      description: List Images Matching a URL
      operationId: imagingv0imagesurl
      parameters:
      - in: query
        name: url
        description: URL to search for
        type: string
      responses:
        200:
          description: OK
      tags:
      - imaging
      - v0
      - images
      - url
definitions: []
x-collection-name: Akamai
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