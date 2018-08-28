---
swagger: "2.0"
x-collection-name: IBM Cloud
x-complete: 0
info:
  title: IBM Containers List all Docker images that are available in your private
    Bluemix registry.
  description: 'This endpoint returns a list of all available Docker images in a private
    Bluemix registry (corresponding IBM Containers command: `cf ic images`.'
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