---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Extension Profile Image (Scaled)
  description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile image is
    not found for scale size [92]"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/profile-image:
    get:
      summary: Get User Profile Image
      description: "Returns a profile image of an extension.\nApp Permission\nReadAccounts\nUser
        Permission\nReadExtensions\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-401\nAuthorization
        header is not specified\n\n\n401\nAGW-402\nInvalid Authorization header\n\n\n403\nCMN-109\nFeature
        Profile Image Streaming is unavailable\n\n\n403\nCMN-401\nIn order to call
        this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
        for parameter [extensionId] is not found"
      operationId: downloadImage
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-get
      parameters:
      - in: path
        name: accountId
      - in: path
        name: extensionId
      responses:
        200:
          description: OK
      tags:
      - User
      - Profile
      - Image
    post:
      summary: Upload User Profile Image
      description: "Returns the extension profile image.\nApp Permission\nEditExtensions\nUser
        Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [EditExtensions]
        permission"
      operationId: uploadImageByPostForm
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-post
      parameters:
      - in: path
        name: accountId
      - in: path
        name: extensionId
      - in: formData
        name: image
      responses:
        200:
          description: OK
      tags:
      - Upload
      - User
      - Profile
      - Image
    put:
      summary: Update User Profile Image
      description: "Updates profile image of an extension.\nApp Permission\nEditExtensions\nUser
        Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nACT-331\nProfile
        image not valid\n\n\n400\nACT-334\nProfile image file is more than 12 megapixel\n\n\n400\nCMN-101\nParameter
        [image] value is invalid\n\n\n403\nACT-332\nProfile image could not be set
        for an extension in unassigned status\n\n\n403\nCMN-401\nIn order to call
        this API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
        order to call this API endpoint, user needs to have [EditUserInfo] permission
        for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
        is not found\n\n\n415\nACT-330\nUnsupported image content type"
      operationId: uploadImageByPutForm
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-put
      parameters:
      - in: path
        name: accountId
      - in: path
        name: extensionId
      - in: formData
        name: image
      responses:
        200:
          description: OK
      tags:
      - User
      - Profile
      - Image
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/profile-image/{scaleSize}:
    get:
      summary: Get Extension Profile Image (Scaled)
      description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
        Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile
        image is not found for scale size [92]"
      operationId: loadExtensionProfileImage
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: path
        name: scaleSize
        description: Dimensions of a profile image which will be returned in response
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Profile
      - Image
      - (Scaled)
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