---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 0
info:
  title: Jumpseller Delete Products Images Image
  description: ""
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/{id}/images.json:
    get:
      summary: Get Products Images
      description: ""
      operationId: getProductsImages.json
      x-api-path-slug: productsidimages-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Images
      - Json
    post:
      summary: Post Products Images
      description: ""
      operationId: postProductsImages.json
      x-api-path-slug: productsidimages-json-post
      parameters:
      - in: body
        name: body
        description: Product Image parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Images
      - Json
  /products/{id}/images/count.json:
    get:
      summary: Get Products Images Count
      description: ""
      operationId: getProductsImagesCount.json
      x-api-path-slug: productsidimagescount-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Images
      - Count
      - Json
  /products/{id}/images/{image_id}.json:
    delete:
      summary: Delete Products Images Image
      description: ""
      operationId: deleteProductsImagesImage.json
      x-api-path-slug: productsidimagesimage-id-json-delete
      parameters:
      - in: path
        name: image_id
        description: Id of the Product Image
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Images
      - Image
      - Id
      - Json
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