swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/products/7990943555/images.json:
    get:
      summary: Get all product images
      description: Get all product images.
      operationId: getAdminProducts7990943555Images.json
      x-api-path-slug: adminproducts7990943555images-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Images
    post:
      summary: Create a new product image
      description: Create a new product image.
      operationId: postAdminProducts7990943555Images.json
      x-api-path-slug: adminproducts7990943555images-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Product
      - Image
  /admin/products/7990943555/images/count.json:
    get:
      summary: Get a count of all product images
      description: Get a count of all product images.
      operationId: getAdminProducts7990943555ImagesCount.json
      x-api-path-slug: adminproducts7990943555imagescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Product
      - Images
  /admin/products/7990943555/images/19489404942.json:
    get:
      summary: Get a single product image by id
      description: Get a single product image by id.
      operationId: getAdminProducts7990943555Images19489404942.json
      x-api-path-slug: adminproducts7990943555images19489404942-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Product
      - Image
      - By
      - Id
    put:
      summary: Modify an existing product image
      description: Modify an existing product image.
      operationId: putAdminProducts7990943555Images19489404942.json
      x-api-path-slug: adminproducts7990943555images19489404942-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Modify
      - Existing
      - Product
      - Image
    delete:
      summary: Delete a product image
      description: Delete a product image.
      operationId: deleteAdminProducts7990943555Images19489404942.json
      x-api-path-slug: adminproducts7990943555images19489404942-json-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Image