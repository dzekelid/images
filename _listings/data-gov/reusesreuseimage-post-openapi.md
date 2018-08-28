---
swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 0
info:
  title: Data.gov API Add Reuses Reuse Image
  description: Upload a new reuse image
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
    put:
      summary: Update Post Image
      description: Set the image BBox
      operationId: putPostsPostImage
      x-api-path-slug: postspostimage-put
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
  /reuses/{reuse}/image:
    post:
      summary: Add Reuses Reuse Image
      description: Upload a new reuse image
      operationId: postReusesReuseImage
      x-api-path-slug: reusesreuseimage-post
      parameters:
      - in: formData
        name: bbox
      - in: formData
        name: file
      - in: path
        name: reuse
        description: The reuse ID or slug
      responses:
        200:
          description: OK
      tags:
      - Reuses
      - Reuse
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