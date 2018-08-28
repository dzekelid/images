swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /playlist/widget/image/{playlistId}:
    post:
      summary: Parameters for editing existing image on a layout
      description: Parameters for editing existing image on a layout, for adding new
        images, please refer to POST /library documentation
      operationId: WidgetImageEdit
      x-api-path-slug: playlistwidgetimageplaylistid-post
      parameters:
      - in: formData
        name: alignId
        description: Edit only - Horizontal alignment - left, center, bottom
      - in: formData
        name: duration
        description: Edit Only - The Widget Duration
      - in: formData
        name: name
        description: Edit only - Optional Widget Name
      - in: formData
        name: scaleTypeId
        description: 'Edit only - Select scale type available options: center, stretch'
      - in: formData
        name: useDuration
        description: Edit only (0, 1) Select 1 only if you will provide duration parameter
          as well
      - in: formData
        name: valignId
        description: Edit only - Vertical alignment - top, middle, bottom
      responses:
        200:
          description: OK
      tags:
      - Parametersediting
      - Existing
      - Image
      - "On"
      - Layout