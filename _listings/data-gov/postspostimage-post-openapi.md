---
swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 0
info:
  title: Data.gov API Add Post Image
  description: Upload a new image
  version: "3"
host: catalog.data.gov
basePath: /api/3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /posts/{post}/image:
    post:
      summary: Add Post Image
      description: Upload a new image
      operationId: postPostsPostImage
      x-api-path-slug: postspostimage-post
      parameters:
      - in: formData
        name: bbox
      - in: formData
        name: file
      - in: path
        name: post
      responses:
        200:
          description: OK
      tags:
      - Posts
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