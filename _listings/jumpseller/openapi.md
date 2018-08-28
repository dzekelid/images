swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 1
info:
  title: Jumpseller
  description: explore-all-our-endpoints-with-your-own-set-of-of-access-tokens--all-changes-affect-your-production-jumpseller-store-
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
    get:
      summary: Get Products Images Image
      description: ""
      operationId: getProductsImagesImage.json
      x-api-path-slug: productsidimagesimage-id-json-get
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