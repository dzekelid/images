---
swagger: "2.0"
info:
  title: Etsy Get Listings Listing Images Listing Image
  description: Retrieves a ListingImage by id.
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /listings/{listing_id}/images/{listing_image_id}:
    get:
      summary: Get Listings Listing Images Listing Image
      description: Retrieves a ListingImage by id
      operationId: getListingsListingImagesListingImage
      responses:
        200:
          description: OK
      tags:
      - listings
      - images
      - listing
      - image
definitions: []
x-collection-name: Etsy
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