---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 0
info:
  title: Big Oven Get all the images for a recipe. DEPRECATED. Please use /recipe/{recipeId}/photos.
  description: Get all the images for a recipe. deprecated. please use /recipe/{recipeid}/photos..
  termsOfService: Please see our [terms of service](http://api2.bigoven.com/web/documentation/termsofuse
  version: partner
host: api2.bigoven.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /recipe/{recipeId}/images:
    get:
      summary: Get all the images for a recipe. DEPRECATED. Please use /recipe/{recipeId}/photos.
      description: Get all the images for a recipe. deprecated. please use /recipe/{recipeid}/photos..
      operationId: Images_Get
      x-api-path-slug: reciperecipeidimages-get
      parameters:
      - in: path
        name: recipeId
        description: Recipe ID (required)
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
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