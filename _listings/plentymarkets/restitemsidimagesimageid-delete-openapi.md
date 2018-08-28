---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Delete an image
  description: Delete an image. The ID of the image must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/items/{id}/images:
    get:
      summary: List images of an item
      description: Lists all images of an item. The item ID must be specified.
      operationId: getRestItemsImages
      x-api-path-slug: restitemsidimages-get
      parameters:
      - in: path
        name: id
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      responses:
        200:
          description: OK
      tags:
      - List
      - Images
      - Of
      - Item
  /rest/items/{id}/variations/{variationId}/images:
    get:
      summary: List images of a variation
      description: Lists all images of a variation. The variation ID must be specified.
      operationId: getRestItemsVariationsVariationImages
      x-api-path-slug: restitemsidvariationsvariationidimages-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Images
      - Of
      - Variation
  /rest/items/{id}/images/attribute_value_markets:
    get:
      summary: List attribute value image link
      description: Lists the images linked to an attribute value.
      operationId: getRestItemsImagesAttributeValueMarkets
      x-api-path-slug: restitemsidimagesattribute-value-markets-get
      parameters:
      - in: query
        name: attributeId
        description: The unique ID of the attribute
      - in: path
        name: id
      - in: query
        name: imageId
        description: The unique ID of the image
      - in: query
        name: itemId
        description: The unique ID of the item
      - in: query
        name: valueId
        description: The unique ID of the attribute value
      responses:
        200:
          description: OK
      tags:
      - List
      - Attribute
      - Value
      - Image
      - Link
  /rest/items/{id}/images/upload:
    post:
      summary: Upload a new image
      description: Uploads an image. The item ID must be specified.
      operationId: postRestItemsImagesUpload
      x-api-path-slug: restitemsidimagesupload-post
      parameters:
      - in: body
        name: /rest/items/{id}/images/upload
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Upload
      - New
      - Image
  /rest/items/{id}/images/{imageId}:
    delete:
      summary: Delete an image
      description: Delete an image. The ID of the image must be specified.
      operationId: deleteRestItemsImagesImage
      x-api-path-slug: restitemsidimagesimageid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Image
    get:
      summary: Get an image
      description: Gets an image. The ID of the image must be specified.
      operationId: getRestItemsImagesImage
      x-api-path-slug: restitemsidimagesimageid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Image
    put:
      summary: Update an image
      description: Updates an image. The ID of the image must be specified.
      operationId: putRestItemsImagesImage
      x-api-path-slug: restitemsidimagesimageid-put
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Image
  /rest/items/{id}/images/{imageId}/attribute_value_markets:
    post:
      summary: Create an attribute value image link
      description: Creates a link between an image and an attribute value.
      operationId: postRestItemsImagesImageAttributeValueMarkets
      x-api-path-slug: restitemsidimagesimageidattribute-value-markets-post
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/attribute_value_markets
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Image
      - Link
  /rest/items/{id}/images/{imageId}/attribute_value_markets/{valueId}:
    delete:
      summary: Delete an attribute value image link
      description: Deletes the link between an image and an attribute value. The attribute
        ID must be specified.
      operationId: deleteRestItemsImagesImageAttributeValueMarketsValue
      x-api-path-slug: restitemsidimagesimageidattribute-value-marketsvalueid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: query
        name: itemId
        description: The unique ID of the item
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Image
      - Link
    get:
      summary: Get an attribute value image link
      description: 'Gets an attribute value image link. The following IDs must be
        specified: image ID, item ID and value ID.'
      operationId: getRestItemsImagesImageAttributeValueMarketsValue
      x-api-path-slug: restitemsidimagesimageidattribute-value-marketsvalueid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: query
        name: itemId
        description: The unique ID of the item
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Image
      - Link
    put:
      summary: Update an attribute value image link
      description: 'Updates the link between an image and an attribute value. The
        following IDs must be specified: image ID, item ID and value ID.'
      operationId: putRestItemsImagesImageAttributeValueMarketsValue
      x-api-path-slug: restitemsidimagesimageidattribute-value-marketsvalueid-put
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/attribute_value_markets/{valueId}
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: attributeId
        description: The unique ID of the attribute
      - in: path
        name: id
      - in: path
        name: imageId
      - in: query
        name: itemId
        description: The unique ID of the item
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Image
      - Link
  /rest/items/{id}/images/{imageId}/names:
    get:
      summary: List names of an image
      description: Lists all names of an image. The image ID must be specified.
      operationId: getRestItemsImagesImageNames
      x-api-path-slug: restitemsidimagesimageidnames-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - List
      - Names
      - Of
      - Image
    post:
      summary: Create an image name
      description: Create an image name. The ID, language and name of the image must
        be specified.
      operationId: postRestItemsImagesImageNames
      x-api-path-slug: restitemsidimagesimageidnames-post
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Image
      - Name
  /rest/items/{id}/images/{imageId}/names/{lang}:
    delete:
      summary: Delete an image name
      description: Delete an image name. The ID and language of the image must be
        specified.
      operationId: deleteRestItemsImagesImageNamesLang
      x-api-path-slug: restitemsidimagesimageidnameslang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Image
      - Name
    get:
      summary: Get an image name
      description: Gets an image name. The image ID and language must be specified.
      operationId: getRestItemsImagesImageNamesLang
      x-api-path-slug: restitemsidimagesimageidnameslang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Image
      - Name
    put:
      summary: Update an image name
      description: Update an image name. The ID, language and name of the image must
        be specified.
      operationId: putRestItemsImagesImageNamesLang
      x-api-path-slug: restitemsidimagesimageidnameslang-put
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/names/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Image
      - Name
  /rest/items/{id}/images/{imageId}/variation_images:
    get:
      summary: List image links of an image
      description: Lists all variations linked to an image. The image ID must be specified.
      operationId: getRestItemsImagesImageVariationImages
      x-api-path-slug: restitemsidimagesimageidvariation-images-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - List
      - Image
      - Links
      - Of
      - Image
  /rest/items/{id}/variation_images:
    get:
      summary: List image links of an item
      description: Lists all images linked to an item. The item ID must be specified.
      operationId: getRestItemsVariationImages
      x-api-path-slug: restitemsidvariation-images-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Image
      - Links
      - Of
      - Item
  /rest/items/{id}/variations/{variationId}/variation_images:
    get:
      summary: List image links of a variation
      description: Lists all images linked to a variation. The variation ID must be
        specified.
      operationId: getRestItemsVariationsVariationVariationImages
      x-api-path-slug: restitemsidvariationsvariationidvariation-images-get
      parameters:
      - in: path
        name: id
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to variation images updated
          after the specified date
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Image
      - Links
      - Of
      - Variation
    post:
      summary: Create an image link
      description: Creates a link between an image and a variation.
      operationId: postRestItemsVariationsVariationVariationImages
      x-api-path-slug: restitemsidvariationsvariationidvariation-images-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_images
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Image
      - Link
  /rest/items/{id}/variations/{variationId}/variation_images/{imageId}:
    delete:
      summary: Delete an image link
      description: Deletes a link between an image and a variation.
      operationId: deleteRestItemsVariationsVariationVariationImagesImage
      x-api-path-slug: restitemsidvariationsvariationidvariation-imagesimageid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Image
      - Link
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