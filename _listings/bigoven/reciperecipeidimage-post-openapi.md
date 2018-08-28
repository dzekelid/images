---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 0
info:
  title: "Big Oven POST: /recipe/{recipeId}/image?lat=42&amp;lng=21&amp;caption=this%20is%20my%20caption\r\n
    \            \r\n             Note that caption, lng and lat are all optional,
    but must go on the request URI as params because this endpoint\r\n             needs
    a m"
  description: "Post: /recipe/{recipeid}/image?lat=42&amp;lng=21&amp;caption=this%20is%20my%20caption\r\n
    \            \r\n             note that caption, lng and lat are all optional,
    but must go on the request uri as params because this endpoint\r\n             needs
    a m."
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
  /recipe/{recipeId}/image:
    post:
      summary: "POST: /recipe/{recipeId}/image?lat=42&amp;lng=21&amp;caption=this%20is%20my%20caption\r\n
        \            \r\n             Note that caption, lng and lat are all optional,
        but must go on the request URI as params because this endpoint\r\n             needs
        a m"
      description: "Post: /recipe/{recipeid}/image?lat=42&amp;lng=21&amp;caption=this%20is%20my%20caption\r\n
        \            \r\n             note that caption, lng and lat are all optional,
        but must go on the request uri as params because this endpoint\r\n             needs
        a m."
      operationId: Images_UploadRecipeImage
      x-api-path-slug: reciperecipeidimage-post
      parameters:
      - in: query
        name: caption
      - in: query
        name: lat
      - in: query
        name: lng
      - in: path
        name: recipeId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
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