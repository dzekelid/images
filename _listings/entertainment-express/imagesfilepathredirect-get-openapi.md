---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: Entertainment Express Redirect to an image based on filepath.
  description: "Images should be downloaded and stored on the client server. Use /Common/ImageTypes
    to see a list of available image types.  \n\n\n`Note: The swagger U/I does not
    support redirects.`"
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Images/Batch:
    post:
      summary: Returns a list of batch image responses links based on filepath.
      description: Requires a list filepath.
      operationId: GetImageBatch
      x-api-path-slug: imagesbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: FilePath
        description: List of Filepaths
      responses:
        200:
          description: OK
      tags:
      - Images
      - Batch
  /Images/ScreenCaptures/Batch:
    post:
      summary: Returns a list of screen capture responses.
      description: Requires a list of filepaths.
      operationId: GetScreenCaptureBatch
      x-api-path-slug: imagesscreencapturesbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: FilePath
        description: List of Filepaths
      responses:
        200:
          description: OK
      tags:
      - Images
      - ScreenCaptures
      - Batch
  /Images/ScreenCaptures/Redirect:
    get:
      summary: Redirect to a screen capture based on filepath.
      description: "Requires a valid filepath of a video asset screen capture.  \n\n`Note:
        The swagger U/I does not support redirects.`"
      operationId: GetScreenCapture
      x-api-path-slug: imagesscreencapturesredirect-get
      parameters:
      - in: query
        name: FilePath
        description: Filepath of Image
      - in: query
        name: Redirect
        description: Redirect to the image
      responses:
        200:
          description: OK
      tags:
      - Images
      - ScreenCaptures
      - Redirect
  /Images/{FilePath}/Redirect:
    get:
      summary: Redirect to an image based on filepath.
      description: "Images should be downloaded and stored on the client server. Use
        /Common/ImageTypes to see a list of available image types.  \n\n\n`Note: The
        swagger U/I does not support redirects.`"
      operationId: GetImage
      x-api-path-slug: imagesfilepathredirect-get
      parameters:
      - in: path
        name: FilePath
        description: Filepath of Image
      - in: query
        name: Redirect
        description: Redirect to the image
      responses:
        200:
          description: OK
      tags:
      - Images
      - FilePath
      - Redirect
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