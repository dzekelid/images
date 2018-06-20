---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /listings/{listing_id}/images:
    get:
      summary: Get Listings Listing Images
      description: View the images associated with a particular listing
      operationId: getListingsListingImages
      x-api-path-slug: listingslisting-idimages-get
      parameters:
      - in: path
        name: listing_id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Listing
      - Id
      - Images
  /listings/{listing_id}/images/{image_id}:
    delete:
      summary: Delete Listings Listing Images Image
      description: Delete listings listing images image.
      operationId: deleteListingsListingImagesImage
      x-api-path-slug: listingslisting-idimagesimage-id-delete
      parameters:
      - in: path
        name: image_id
      - in: path
        name: listing_id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Listing
      - Id
      - Images
      - Image
      - Id
---