swagger: "2.0"
x-collection-name: Codefresh
x-complete: 1
info:
  title: Codefresh API
  description: codefresh-api-swagger2-0-specification
  termsOfService: http://www.codefresh.io
  contact:
    name: Codefresh api team
    url: http://www.codefresh.io
  version: 1.0.0
host: g.codefresh.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /images:
    get:
      summary: Get Images
      description: Get images.
      operationId: getImages
      x-api-path-slug: images-get
      responses:
        200:
          description: OK
      tags:
      - Images
  /images/external:
    post:
      summary: Post Images External
      description: Post images external.
      operationId: postImagesExternal
      x-api-path-slug: imagesexternal-post
      responses:
        200:
          description: OK
      tags:
      - Images
      - External
    parameters:
      summary: Parameters Images External
      description: Parameters images external.
      operationId: parametersImagesExternal
      x-api-path-slug: imagesexternal-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Images
      - External
  /images/{imageId}:
    get:
      summary: Get Images Imageid
      description: Get images imageid.
      operationId: getImagesImage
      x-api-path-slug: imagesimageid-get
      parameters:
      - in: path
        name: imageId
        description: id of the Image
      responses:
        200:
          description: OK
      tags:
      - Images
      - Imageid
  /images/{imageName}/tags:
    get:
      summary: Get Images Imagename Tags
      description: Get images imagename tags.
      operationId: getImagesImagenameTags
      x-api-path-slug: imagesimagenametags-get
      parameters:
      - in: path
        name: imageName
        description: name of the image
      responses:
        200:
          description: OK
      tags:
      - Images
      - Imagename
      - Tags
  /images/{internalImageId}/metadata:
    get:
      summary: Get Images Internalimageid Metadata
      description: Get images internalimageid metadata.
      operationId: getImagesInternalimageMetadata
      x-api-path-slug: imagesinternalimageidmetadata-get
      parameters:
      - in: path
        name: internalImageId
        description: id of the Image (from docker inspect)
      responses:
        200:
          description: OK
      tags:
      - Images
      - Internalimageid
      - Metadata
    post:
      summary: Post Images Internalimageid Metadata
      description: Post images internalimageid metadata.
      operationId: postImagesInternalimageMetadata
      x-api-path-slug: imagesinternalimageidmetadata-post
      parameters:
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: internalImageId
        description: id of the Image (from docker inspect)
      responses:
        200:
          description: OK
      tags:
      - Images
      - Internalimageid
      - Metadata
  /images/{internalImageId}/metadata/{keyName}:
    delete:
      summary: Delete Images Internalimageid Metadata Keyname
      description: Delete images internalimageid metadata keyname.
      operationId: deleteImagesInternalimageMetadataKeyname
      x-api-path-slug: imagesinternalimageidmetadatakeyname-delete
      parameters:
      - in: path
        name: internalImageId
        description: id of the Image from docker inspect
      - in: path
        name: keyName
        description: name of the metadata key
      responses:
        200:
          description: OK
      tags:
      - Images
      - Internalimageid
      - Metadata
      - Keyname