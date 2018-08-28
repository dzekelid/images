swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/issuetype/{id}/avatar2:
    post:
      summary: Create issue type avatar
      description: |-
        Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

        *   `X-Atlassian-Token: no-check`
        *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

        For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
      operationId: com.atlassian.jira.rest.v2.issue.IssueTypeResource.createIssueTypeAvatar_post
      x-api-path-slug: api2issuetypeidavatar2-post
      parameters:
      - in: path
        name: id
        description: The ID of the issue type
      - in: query
        name: size
        description: The length of each side of the crop region
      - in: query
        name: x
        description: The X coordinate of the top-left corner of the crop region
      - in: query
        name: "y"
        description: The Y coordinate of the top-left corner of the crop region
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Type
      - Avatar
  /api/2/project/{projectIdOrKey}/avatar2:
    post:
      summary: Create project avatar
      description: Creates an avatar for a single project. Use it to upload an image
        to be be set as a project's avatar. The uploaded image will be cropped according
        to the crop parameters defined in the request. If no crop parameters are specified,
        the image will be cropped to a square. The square will originate at the top
        left of the image and the length of each side will be set to the smaller of
        the height or width of the image.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectResource.createProjectAvatar_post
      x-api-path-slug: api2projectprojectidorkeyavatar2-post
      parameters:
      - in: path
        name: projectIdOrKey
        description: The project ID or project key (case sensitive)
      - in: query
        name: size
        description: (optional) Length of each side of the crop region
      - in: query
        name: x
        description: (optional) X coordinate of the top-left corner of the crop region
      - in: query
        name: "y"
        description: (optional) Y coordinate of the top-left corner of the crop region
      responses:
        200:
          description: OK
      tags:
      - Project
      - Avatar
  /api/2/universal_avatar/type/{type}/owner/{entityId}:
    post:
      summary: Store avatar
      description: Creates an avatar for a given entity, for the given entity ID and
        type of entity. For example, you can create an avatar for an issue type, given
        the issue type Id. Uploading an avatar is supported for different types of
        entities across the Jira products. However, it is supported for the "project"
        and "issuetype" entity types for all Jira products. The uploaded image will
        be cropped according to the crop parameters listed below. If no crop parameters
        are specified, the image will be cropped to a square. The square will originate
        at the top left of the image and the length of each side will be set to the
        smaller of the height or width of the image.
      operationId: com.atlassian.jira.rest.v2.issue.UniversalAvatarResource.storeAvatar_post
      x-api-path-slug: api2universal-avatartypetypeownerentityid-post
      parameters:
      - in: path
        name: entityId
        description: The Id of the entity that you want to update the avatar of
      - in: query
        name: size
        description: (optional) The length of each side of the crop region
      - in: path
        name: type
        description: The type of the entity that you want to update the avatar of
      - in: query
        name: x
        description: (optional) The X coordinate of the top-left corner of the crop
          region
      - in: query
        name: "y"
        description: (optional) The Y coordinate of the top-left corner of the crop
          region
      responses:
        200:
          description: OK
      tags:
      - Store
      - Avatar