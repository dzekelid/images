---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Create Image Family
  description: Returns the latest image that is part of an image family and is not
    deprecated.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/global/images:
    get:
      summary: Get Images
      description: Retrieves the list of private images available to the specified
        project. Private images are images you create that belong to your project.
        This method does not get any images that belong to other projects, including
        publicly-available images, like Debian 8. If you want to get a list of publicly-available
        images, use this method to make a request to the respective image project,
        such as debian-cloud or windows-cloud.
      operationId: compute.images.list
      x-api-path-slug: projectglobalimages-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Image
    post:
      summary: Create Image
      description: Creates an image in the specified project using the data included
        in the request.
      operationId: compute.images.insert
      x-api-path-slug: projectglobalimages-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Image
  /{project}/global/images/family/{family}:
    get:
      summary: Create Image Family
      description: Returns the latest image that is part of an image family and is
        not deprecated.
      operationId: compute.images.getFromFamily
      x-api-path-slug: projectglobalimagesfamilyfamily-get
      parameters:
      - in: path
        name: family
        description: Name of the image family to search for
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Image
  /{project}/global/images/{image}:
    delete:
      summary: Delete Image
      description: Deletes the specified image.
      operationId: compute.images.delete
      x-api-path-slug: projectglobalimagesimage-delete
      parameters:
      - in: path
        name: image
        description: Name of the image resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Image
    get:
      summary: Get Image
      description: Returns the specified image. Get a list of available images by
        making a list() request.
      operationId: compute.images.get
      x-api-path-slug: projectglobalimagesimage-get
      parameters:
      - in: path
        name: image
        description: Name of the image resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Image
  /{project}/global/images/{image}/deprecate:
    post:
      summary: Deprecate Image
      description: |-
        Sets the deprecation status of an image.

        If an empty request body is given, clears the deprecation status instead.
      operationId: compute.images.deprecate
      x-api-path-slug: projectglobalimagesimagedeprecate-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: image
        description: Image name
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
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