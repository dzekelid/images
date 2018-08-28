---
swagger: "2.0"
x-collection-name: BigCommerce
x-complete: 0
info:
  title: BigCommerce Delete the image associated with a modifier
  description: Delete the image applied to show when the modifier value is selected
  version: 1.0.0
host: api.bigcommerce.com
basePath: /stores
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{store-hash}/v3/catalog/products/{id}/images/{id}:
    get:
      summary: Retrieve a single product image's data
      description: GET request for a specific product image by ID
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsidimagesid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Single
      - Product
      - Images
      - Data
    put:
      summary: Update product image information
      description: This is used to update the information for an existing product
        image
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdPut
      x-api-path-slug: storehashv3catalogproductsidimagesid-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Image
      - Information
    delete:
      summary: Delete a single product image
      description: Delete a product image and it's description
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdDelete
      x-api-path-slug: storehashv3catalogproductsidimagesid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Product
      - Image
  /{store-hash}/v3/catalog/products/{id}/images:
    post:
      summary: Upload a new product image to a single product
      description: Adds a new product image from a publicly accessible URL. May fail
        if the hosting website is forcing HTTPS connections with TLS 1.0 (as this
        has been deprecated).
      operationId: V3CatalogProductsImagesByStoreHashAndIdPost
      x-api-path-slug: storehashv3catalogproductsidimages-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Upload
      - New
      - Product
      - Image
      - To
      - Single
      - Product
    get:
      summary: Retrieve images for a single product
      description: GET request for retrieving images associated with a product
      operationId: V3CatalogProductsImagesByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsidimages-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Imagesa
      - Single
      - Product
  /{store_hash}/v3/catalog/brands/{id}/image:
    delete:
      summary: Delete a brand image
      description: Delete a `Brand` image the BigCommerce Catalog
      operationId: V3CatalogBrandsImageByStoreHashAndIdDelete
      x-api-path-slug: store-hashv3catalogbrandsidimage-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Brand
      - Image
    post:
      summary: Upload an image for a brand
      description: ""
      operationId: V3CatalogBrandsImageByStoreHashAndIdPost
      x-api-path-slug: store-hashv3catalogbrandsidimage-post
      parameters:
      - in: path
        name: id
      - in: formData
        name: image_file
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Upload
      - Imagea
      - Brand
  /{store_hash}/v3/catalog/categories/{id}/image:
    delete:
      summary: Delete a category image
      description: ""
      operationId: V3CatalogCategoriesImageByStoreHashAndIdDelete
      x-api-path-slug: store-hashv3catalogcategoriesidimage-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Category
      - Image
    post:
      summary: Create an image for a category
      description: ""
      operationId: V3CatalogCategoriesImageByStoreHashAndIdPost
      x-api-path-slug: store-hashv3catalogcategoriesidimage-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Imagea
      - Category
  /{store_hash}/v3/catalog/products/{id}/modifiers/{id}/values/{id}/image:
    post:
      summary: Add an image to a modifier value
      description: "Add an image to a modifier value that will show on the storefront
        when it\u2019s selected"
      operationId: V3CatalogProductsModifiersIdValuesIdImageByStoreHashAndIdPost
      x-api-path-slug: store-hashv3catalogproductsidmodifiersidvaluesidimage-post
      parameters:
      - in: path
        name: id
      - in: formData
        name: image_file
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Image
      - To
      - Modifier
      - Value
    delete:
      summary: Delete the image associated with a modifier
      description: Delete the image applied to show when the modifier value is selected
      operationId: V3CatalogProductsModifiersIdValuesIdImageByStoreHashAndIdDelete
      x-api-path-slug: store-hashv3catalogproductsidmodifiersidvaluesidimage-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Image
      - Associated
      - Modifier
  /{store_hash}/v3/catalog/products/{id}/variants/{id}/image:
    post:
      summary: Upload a variant image
      description: ""
      operationId: V3CatalogProductsVariantsIdImageByStoreHashAndIdPost
      x-api-path-slug: store-hashv3catalogproductsidvariantsidimage-post
      parameters:
      - in: path
        name: id
      - in: formData
        name: image_file
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Upload
      - Variant
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