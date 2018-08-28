swagger: "2.0"
x-collection-name: Twitter
x-complete: 1
info:
  title: Twitter
  description: the-twitter-api-gives-you-programmatic-control-over-any-twitter-account-and-most-aspect-of-the-platform--allowing-developers-to-build-social-applications-that-use-the-platform-and-automate-interactions-between-users-
  version: "1.1"
host: api.twitter.com
basePath: /1.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/update_profile_background_image:
    post:
      summary: Update Profile Background Image
      description: updates user's profile background image
      operationId: updates-users-profile-background-image
      x-api-path-slug: accountupdate-profile-background-image-post
      parameters:
      - in: formData
        name: file
        description: image to replace background image of profile
      - in: query
        name: include_entities
        description: whether or not to include entities
      - in: query
        name: skip_status
        description: whether or not to include status in returned user objects
      - in: query
        name: tile
        description: whether or not to tile background image
      - in: query
        name: use
        description: display background image or not
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
  /account/update_profile_image:
    post:
      summary: Update Profile Image
      description: updates user's profile image
      operationId: updates-users-profile-image
      x-api-path-slug: accountupdate-profile-image-post
      parameters:
      - in: formData
        name: image
        description: image to be set as profile image
      - in: query
        name: skip_status
        description: whether or not to include statuses
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account