---
swagger: "2.0"
x-collection-name: AWS EC2 Container Registry Service
x-complete: 1
info:
  title: AWS EC2 Container Registry API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeImages:
    get:
      summary: Describe Images
      description: |-
        Returns metadata about the images in a repository, including image size, image
                    tags, and creation date.
      operationId: describeImages
      x-api-path-slug: actiondescribeimages-get
      parameters:
      - in: query
        name: filter
        description: The filter key and value with which to filter your DescribeImages            results
        type: string
      - in: query
        name: imageIds
        description: The list of image IDs for the requested repository
        type: string
      - in: query
        name: maxResults
        description: The maximum number of repository results returned by DescribeImages
          in            paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated            DescribeImages
          request where maxResults was used and            the results exceeded the
          value of that parameter
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the repository in            which to describe images
        type: string
      - in: query
        name: repositoryName
        description: A list of repositories to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Images
  /?Action=ListImages:
    get:
      summary: List Images
      description: Lists all the image IDs for a given repository.
      operationId: listImages
      x-api-path-slug: actionlistimages-get
      parameters:
      - in: query
        name: filter
        description: The filter key and value with which to filter your ListImages            results
        type: string
      - in: query
        name: maxResults
        description: The maximum number of image results returned by ListImages in
          paginated            output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated                ListImages
          request where maxResults was used and the            results exceeded the
          value of that parameter
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the repository to list images in
        type: string
      - in: query
        name: repositoryName
        description: The repository whose image IDs are to be listed
        type: string
      responses:
        200:
          description: OK
      tags:
      - Images
  /?Action=PutImage:
    get:
      summary: Put Image
      description: Creates or updates the image manifest and tags associated with
        an image.
      operationId: putImage
      x-api-path-slug: actionputimage-get
      parameters:
      - in: query
        name: imageManifest
        description: The image manifest corresponding to the image to be uploaded
        type: string
      - in: query
        name: imageTag
        description: The tag to associate with the image
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the repository in which to put the image
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository in which to put the image
        type: string
      responses:
        200:
          description: OK
      tags:
      - Images
---