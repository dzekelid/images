swagger: "2.0"
x-collection-name: Spreaker
x-complete: 1
info:
  title: Spreaker API
  version: v1
host: api.spreaker.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /episode/<episode_id>/image:
    put:
      summary: Change Episode Image
      description: Change Episode Image
      operationId: putEpisode<episode>Image
      x-api-path-slug: episodeepisode-idimage-put
      parameters:
      - in: path
        name: episode_id
        description: The unique episode id
      - in: query
        name: image_id
        description: The id of the image to set to the episode
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Change
      - Episode
      - Image
  /user/{user_id}/image:
    put:
      summary: Change User Profile Image
      description: Change User Profile Image
      operationId: putUserUserImage
      x-api-path-slug: useruser-idimage-put
      parameters:
      - in: query
        name: image_id
        description: The id of the image to set to the user profile
      - in: path
        name: user_id
        description: The unique user id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Change
      - User
      - Profile
      - Image
  /user/{user_id}/images:
    post:
      summary: Upload An Image
      description: Upload An Image
      operationId: postUserUserImages
      x-api-path-slug: useruser-idimages-post
      parameters:
      - in: body
        name: Filedata
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Upload
      - Image
  show/{show_id}/image:
    put:
      summary: Change Show Image
      description: Change Show Image
      operationId: putShowShowImage
      x-api-path-slug: showshow-idimage-put
      parameters:
      - in: query
        name: image_id
        description: The id of the image to set to the show
      - in: path
        name: show_id
        description: Unique show id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - Change
      - Show
      - Image