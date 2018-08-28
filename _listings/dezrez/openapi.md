swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/group/backgroundimages:
    get:
      summary: Return all background images.
      description: Return all background images..
      operationId: Group_BackgroundImagesBypageSizeBypageNumber
      x-api-path-slug: apigroupbackgroundimages-get
      parameters:
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Return
      - ""
      - Background
      - Images
  /api/role/{id}/images:
    get:
      summary: Get a list of ordered images belonging to a role
      description: Get a list of ordered images belonging to a role.
      operationId: Role_ImagesByidBypageSizeBypageNumberBysubtype
      x-api-path-slug: apiroleidimages-get
      parameters:
      - in: path
        name: id
        description: The id of the role to get the images for
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: subtype
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Ordered
      - Images
      - Belonging
      - To
      - Role
  /api/document/{id}/savedescription:
    put:
      summary: Save the document description. Used for the image caption for the portals.
      description: Save the document description. used for the image caption for the
        portals..
      operationId: Document_SaveDescriptionByidBydescription
      x-api-path-slug: apidocumentidsavedescription-put
      parameters:
      - in: query
        name: description
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Document
      - Description
      - ""
      - Usedthe
      - Image
      - Captionthe
      - Portals
  /api/group/{id}/displaysettings:
    put:
      summary: Edit Display settings for the Group. Primarily shown in the GroupHub
        e.g. the icon and background image.
      description: Edit display settings for the group. primarily shown in the grouphub
        e.g. the icon and background image..
      operationId: Group_SetDisplaySettingsByidBygroupDisplaySettingsDataContract
      x-api-path-slug: apigroupiddisplaysettings-put
      parameters:
      - in: body
        name: groupDisplaySettingsDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Display
      - Settingsthe
      - Group
      - ""
      - Primarily
      - Shown
      - In
      - GroupHub
      - E
      - G
      - ""
      - Icon
      - Background
      - Image
  /api/role/{id}/SetRoleImageOrder:
    put:
      summary: Updates the image order on a role
      description: Updates the image order on a role.
      operationId: Role_SetRoleImageOrderByidByimageOrderCommandDataContract
      x-api-path-slug: apiroleidsetroleimageorder-put
      parameters:
      - in: path
        name: id
        description: The id of the role to update
      - in: body
        name: imageOrderCommandDataContract
        description: The role image order
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Image
      - Order
      - "On"
      - Role
  /api/role/{id}/setdefaultimage:
    put:
      summary: Sets the default image of a property marketing role
      description: Sets the default image of a property marketing role.
      operationId: Role_SetDefaultImageByidBydocumentId
      x-api-path-slug: apiroleidsetdefaultimage-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to set as the default image
      - in: path
        name: id
        description: The id of the role
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Default
      - Image
      - Of
      - Property
      - Marketing
      - Role
  /api/roomdescription/setimages:
    post:
      summary: Allows you to specify a list of documentIds for a roomDescriptions
        room - this list will overwrite any existing list of documents on that room,
        and order will be honoured.
      description: Allows you to specify a list of documentids for a roomdescriptions
        room - this list will overwrite any existing list of documents on that room,
        and order will be honoured..
      operationId: RoomDescription_SetImagesByroomImageOrder
      x-api-path-slug: apiroomdescriptionsetimages-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: roomImageOrder
        description: The room image order
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Specify
      - List
      - Of
      - DocumentIdsa
      - RoomDescriptions
      - Room
      - '-'
      - This
      - List
      - Will
      - Overwrite
      - Any
      - Existing
      - List
      - Of
      - Documents
      - "On"
      - That
      - Room
      - ""
      - Order
      - Will
      - Be
      - Honoured