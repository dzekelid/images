---
swagger: "2.0"
x-collection-name: NewsCred
x-complete: 0
info:
  title: News Cred Category Images
  description: Gets images related to the specified category.
  version: v1
host: api.newscred.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  category/{dashed-name}/images/:
    get:
      summary: Category Images
      description: Gets images related to the specified category.
      operationId: getCategoryDashedNameImages
      x-api-path-slug: categorydashednameimages-get
      parameters:
      - in: query
        name: access_key
        description: Unique API access key
      - in: query
        name: safe_search
        description: Returns only images marked as safe when set to true
      responses:
        200:
          description: OK
      tags:
      - News
      - Category
      - Dashed-name
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