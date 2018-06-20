---
swagger: "2.0"
x-collection-name: Constant Contact
x-complete: 0
info:
  title: Constant Contact Delete All Images
  description: Delete All Images
  version: 1.0.0
host: api.constantcontact.com
basePath: /ws/customers/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{username}/library/folders/{folder-id}/images:
    delete:
      summary: Delete All Images
      description: Delete All Images
      operationId: delete-all-images
      x-api-path-slug: usernamelibraryfoldersfolderidimages-delete
      parameters:
      - in: path
        name: folder-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
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