swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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