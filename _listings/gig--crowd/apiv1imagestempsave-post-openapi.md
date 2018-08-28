---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Images Temp Save
  version: 1.0.0
  description: Post images temp save.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/images/temp/save:
    post:
      summary: Post Images Temp Save
      description: Post images temp save.
      operationId: postApiV1ImagesTempSave
      x-api-path-slug: apiv1imagestempsave-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: url
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Images
      - Temp
      - Save
  /api/v1/images/temp/remove:
    post:
      summary: Post Images Temp Remove
      description: Post images temp remove.
      operationId: postApiV1ImagesTempRemove
      x-api-path-slug: apiv1imagestempremove-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: url
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Images
      - Temp
      - Remove
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