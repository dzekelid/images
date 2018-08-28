---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Updates a collection of images from a specific Product
  version: 1.0.0
  description: Updates a collection of images from a specific product.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Products/{catalogid}/Images:
    get:
      summary: Get the images from a specific Product
      description: Get the images from a specific product.
      operationId: Products_GetAllProductImages
      x-api-path-slug: 3dcartwebapiv1productscatalogidimages-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Images
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of images from a specific Product
      description: Updates a collection of images from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidimages-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: images
        description: A Json or XML object containing the new images
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Images
      - From
      - Specific
      - Product
    post:
      summary: Adds a new image to the system
      description: Adds a new image to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogidimages-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: body
        name: image
        description: A Json or XML object containing the new image
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Image
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/Images/{imagegalleryid}:
    put:
      summary: Updates a specific image from a specific Product
      description: Updates a specific image from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidimagesimagegalleryid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: image
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: imagegalleryid
        description: ImageGalleryID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Image
      - From
      - Specific
      - Product
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