---
swagger: "2.0"
x-collection-name: IBM Cloud
x-complete: 0
info:
  title: IBM Containers Remove a Docker image.
  description: 'Remove a Docker image from the private Bluemix registry that is identified
    by the image ID (corresponding IBM Containers command: `cf ic rmi <image>`).'
  version: 3.0.0
host: containers-api.ng.bluemix.net
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /images/json:
    get:
      summary: List all Docker images that are available in your private Bluemix registry.
      description: 'This endpoint returns a list of all available Docker images in
        a private Bluemix registry (corresponding IBM Containers command: `cf ic images`.'
      operationId: this-endpoint-returns-a-list-of-all-available-docker-images-in-a-private-bluemix-registry-correspond
      x-api-path-slug: imagesjson-get
      parameters:
      - in: header
        name: X-Auth-Project-Id
        description: The unique ID of your organization space where you want to create
          or work with your containers
      - in: header
        name: X-Auth-Token
        description: The Bluemix JSON web token that you receive when logging into
          Bluemix
      responses:
        200:
          description: OK
      tags:
      - Images
      - Json
  /images/{id}:
    delete:
      summary: Remove a Docker image.
      description: 'Remove a Docker image from the private Bluemix registry that is
        identified by the image ID (corresponding IBM Containers command: `cf ic rmi
        <image>`).'
      operationId: remove-a-docker-image-from-the-private-bluemix-registry-that-is-identified-by-the-image-id-correspon
      x-api-path-slug: imagesid-delete
      parameters:
      - in: path
        name: id
        description: The unique identifier representing a Docker image
      - in: header
        name: X-Auth-Project-Id
        description: The unique ID of your organization space where you want to create
          or work with your containers
      - in: header
        name: X-Auth-Token
        description: The Bluemix JSON web token that you receive when logging into
          Bluemix
      responses:
        200:
          description: OK
      tags:
      - Images
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