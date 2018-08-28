---
swagger: "2.0"
x-collection-name: Google Play
x-complete: 0
info:
  title: Google Play Upoads Image
  version: 1.0.0
  description: Uploads a new image and adds it to the list of images for the specified
    language and image type.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{packageName}/edits/{editId}/listings/{language}/{imageType}:
    delete:
      summary: Delete All Images
      description: Deletes all images for the specified language and image type.
      operationId: androidpublisher.edits.images.deleteall
      x-api-path-slug: packagenameeditseditidlistingslanguageimagetype-delete
      parameters:
      - in: path
        name: editId
        description: Unique identifier for this edit
      - in: path
        name: imageType
      - in: path
        name: language
        description: The language code (a BCP-47 language tag) of the localized listing
          whose images are to read or modified
      - in: path
        name: packageName
        description: Unique identifier for the Android app that is being updated;
          for example, com
      responses:
        200:
          description: OK
      tags:
      - Image
    get:
      summary: Get All Images
      description: Lists all images for the specified language and image type.
      operationId: androidpublisher.edits.images.list
      x-api-path-slug: packagenameeditseditidlistingslanguageimagetype-get
      parameters:
      - in: path
        name: editId
        description: Unique identifier for this edit
      - in: path
        name: imageType
      - in: path
        name: language
        description: The language code (a BCP-47 language tag) of the localized listing
          whose images are to read or modified
      - in: path
        name: packageName
        description: Unique identifier for the Android app that is being updated;
          for example, com
      responses:
        200:
          description: OK
      tags:
      - Image
    post:
      summary: Upoads Image
      description: Uploads a new image and adds it to the list of images for the specified
        language and image type.
      operationId: androidpublisher.edits.images.upload
      x-api-path-slug: packagenameeditseditidlistingslanguageimagetype-post
      parameters:
      - in: path
        name: editId
        description: Unique identifier for this edit
      - in: path
        name: imageType
      - in: path
        name: language
        description: The language code (a BCP-47 language tag) of the localized listing
          whose images are to read or modified
      - in: path
        name: packageName
        description: Unique identifier for the Android app that is being updated;
          for example, com
      responses:
        200:
          description: OK
      tags:
      - Image
  /{packageName}/edits/{editId}/listings/{language}/{imageType}/{imageId}:
    delete:
      summary: Delete Image
      description: Deletes the image (specified by id) from the edit.
      operationId: androidpublisher.edits.images.delete
      x-api-path-slug: packagenameeditseditidlistingslanguageimagetypeimageid-delete
      parameters:
      - in: path
        name: editId
        description: Unique identifier for this edit
      - in: path
        name: imageId
        description: Unique identifier an image within the set of images attached
          to this edit
      - in: path
        name: imageType
      - in: path
        name: language
        description: The language code (a BCP-47 language tag) of the localized listing
          whose images are to read or modified
      - in: path
        name: packageName
        description: Unique identifier for the Android app that is being updated;
          for example, com
      responses:
        200:
          description: OK
      tags:
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