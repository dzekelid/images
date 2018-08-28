swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/image:
    get:
      summary: Get user's profile image
      description: |-
        Get a user's profile image based on user_id string parameter.
        ##### Permissions
        Must be logged in.
      operationId: get-a-users-profile-image-based-on-user-id-string-parameter-permissionsmust-be-logged-in
      x-api-path-slug: usersuser-idimage-get
      parameters:
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Users
      - Profile
      - Image
    post:
      summary: Set user's profile image
      description: |-
        Set a user's profile image based on user_id string parameter.
        ##### Permissions
        Must be logged in as the user being updated or have the `edit_other_users` permission.
      operationId: set-a-users-profile-image-based-on-user-id-string-parameter-permissionsmust-be-logged-in-as-the-user
      x-api-path-slug: usersuser-idimage-post
      parameters:
      - in: formData
        name: image
        description: The image to be uploaded
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Set
      - Users
      - Profile
      - Image
  /emoji/{emoji_id}/image:
    get:
      summary: Get custom emoji image
      description: |-
        Get the image for a custom emoji.
        ##### Permissions
        Must be authenticated.
      operationId: get-the-image-for-a-custom-emoji-permissionsmust-be-authenticated
      x-api-path-slug: emojiemoji-idimage-get
      parameters:
      - in: path
        name: emoji_id
        description: Emoji GUID
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Emoji
      - Image
  /brand/image:
    get:
      summary: Get brand image
      description: |-
        Get the previously uploaded brand image. Returns 404 if no brand image has been uploaded.
        ##### Permissions
        No permission required.
      operationId: get-the-previously-uploaded-brand-image-returns-404-if-no-brand-image-has-been-uploaded-permissionsn
      x-api-path-slug: brandimage-get
      responses:
        200:
          description: OK
      tags:
      - Brand
      - Image
    post:
      summary: Upload brand image
      description: |-
        Uploads a brand image.
        ##### Permissions
        Must have `manage_system` permission.
      operationId: uploads-a-brand-image-permissionsmust-have-manage-system-permission
      x-api-path-slug: brandimage-post
      parameters:
      - in: formData
        name: image
        description: The image to be uploaded
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Brand
      - Image