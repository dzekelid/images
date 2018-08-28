swagger: "2.0"
x-collection-name: Constant Contact
x-complete: 1
info:
  title: ConstantContact
  description: constant-contact-inc-is-an-online-marketing-company-offering-email-marketing-social-media-marketing-online-survey-and-event-marketing-tools-primarily-to-small-businesses-nonprofit-organizations-and-membership-associations-
  termsOfService: http://www.constantcontact.com/uidocs/CCSiteOwnerAgreement.jsp
  version: 1.0.0
host: api.constantcontact.com
basePath: /v2
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
    get:
      summary: List Images
      description: List Images
      operationId: list-images
      x-api-path-slug: usernamelibraryfoldersfolderidimages-get
      parameters:
      - in: query
        name: Accept
        description: Specifies Accept
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: path
        name: folder-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - List
      - Images
  /{username}/library/folders/{folder-id}/images/{image-id}:
    delete:
      summary: Delete Image
      description: Delete Image
      operationId: delete-image
      x-api-path-slug: usernamelibraryfoldersfolderidimagesimageid-delete
      parameters:
      - in: path
        name: folder-id
      - in: path
        name: image-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Image
    get:
      summary: Get Image
      description: Get Image
      operationId: get-image
      x-api-path-slug: usernamelibraryfoldersfolderidimagesimageid-get
      parameters:
      - in: query
        name: Accept
        description: Specifies Accept
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: path
        name: folder-id
      - in: path
        name: image-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Image