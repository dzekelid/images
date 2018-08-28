---
swagger: "2.0"
x-collection-name: BBC
x-complete: 0
info:
  title: BBC Nitro Get raw image
  description: Get raw image
  termsOfService: http://www.bbc.co.uk/terms/
  contact:
    name: Open Nitro Project
    url: http://developer.bbc.co.uk/
    email: nitro@bbc.co.uk
  version: 1.0.0
host: programmes.api.bbc.com
basePath: /nitro/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /images:
    get:
      summary: Find metadata for images
      description: Find metadata for images, particularly those in galleries
      operationId: listImages
      x-api-path-slug: images-get
      parameters:
      - in: query
        name: embargoed
        description: Control return of embargoed items (undocumented)
      - in: query
        name: group
        description: filter for images belonging to the given group (i
      - in: query
        name: image_type
        description: filter for images by type
      - in: query
        name: is_alternate_image_for
        description: filter for alternate images by entity PID
      - in: query
        name: is_image_for
        description: filter for images by entity PID
      - in: query
        name: page
        description: which page of results to return
      - in: query
        name: page_size
        description: number of results in each page
      - in: query
        name: partner_id
        description: filter for images by partner ID
      - in: query
        name: partner_pid
        description: filter for images by partner PID
      - in: query
        name: pid
        description: filter for subset of images having given PID
      - in: query
        name: q
        description: filter for subset of images matching supplied keyword/phrase
          (boolean operators permitted)
      - in: query
        name: sort
        description: 'Sorts:* group_position: sort numerically by position, ascending
          only* pid: sort alphabetically by PID'
      - in: query
        name: sort_direction
        description: Sort direction
      responses:
        200:
          description: OK
      tags:
      - Images
  /v1/images/{pid}:
    get:
      summary: Get raw image
      description: Get raw image
      operationId: Get_Raw_image
      x-api-path-slug: v1imagespid-get
      parameters:
      - in: path
        name: pid
      responses:
        200:
          description: OK
      tags:
      - V1
      - Images
      - Pid
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