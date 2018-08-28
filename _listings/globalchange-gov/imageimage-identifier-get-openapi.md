---
swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 0
info:
  title: Global Change Information System API Get a representation of an image.
  description: Get JSON which represents the structure of an image.
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /image:
    get:
      summary: List images.
      description: List the images, 20 per page.
      operationId: list-the-images-20-per-page
      x-api-path-slug: image-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the images
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Images
  /report/{report_identifier}/image:
    get:
      summary: List images associated with a report.
      description: List the images associated with a report, 20 per page.
      operationId: list-the-images-associated-with-a-report-20-per-page
      x-api-path-slug: reportreport-identifierimage-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the images
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - Images
      - Associated
      - Report
  /image/{image_identifier}:
    get:
      summary: Get a representation of an image.
      description: Get JSON which represents the structure of an image.
      operationId: get-json-which-represents-the-structure-of-an-image
      x-api-path-slug: imageimage-identifier-get
      parameters:
      - in: path
        name: image_identifier
        description: image_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the image
      - in: query
        name: with_regions
        description: Include regions associated with the image
      responses:
        200:
          description: OK
      tags:
      - Representation
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