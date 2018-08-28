---
swagger: "2.0"
x-collection-name: AWS EC2 Container Registry Service
x-complete: 0
info:
  title: AWS EC2 Container Registry API Upload Layer Part
  version: 1.0.0
  description: Uploads an image layer part to Amazon ECR.
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
  /?Action=BatchDeleteImage:
    get:
      summary: Batch Delete Image
      description: Deletes a list of specified images within a specified repository.
      operationId: batchDeleteImage
      x-api-path-slug: actionbatchdeleteimage-get
      parameters:
      - in: query
        name: imageIds
        description: A list of image ID references that correspond to images to delete
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the image to delete
        type: string
      - in: query
        name: repositoryName
        description: The repository that contains the image to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Image
  /?Action=BatchGetImage:
    get:
      summary: Batch Get Image
      description: Gets detailed information for specified images within a specified
        repository.
      operationId: batchGetImage
      x-api-path-slug: actionbatchgetimage-get
      parameters:
      - in: query
        name: acceptedMediaTypes
        description: The accepted media types for the request
        type: string
      - in: query
        name: imageIds
        description: A list of image ID references that correspond to images to describe
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the images to describe
        type: string
      - in: query
        name: repositoryName
        description: The repository that contains the images to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Image
  /?Action=BatchCheckLayerAvailability:
    get:
      summary: Batch Check Layer Availability
      description: Check the availability of multiple image layers in a specified
        registry and repository.
      operationId: batchCheckLayerAvailability
      x-api-path-slug: actionbatchchecklayeravailability-get
      parameters:
      - in: query
        name: layerDigests
        description: The digests of the image layers to check
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the image layers to check
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository that is associated with the image
          layers to check
        type: string
      responses:
        200:
          description: OK
      tags:
      - Layer Availability
  /?Action=CompleteLayerUpload:
    get:
      summary: Complete Layer Upload
      description: Inform Amazon ECR that the image layer upload for a specified registry,
        repository name, and upload ID, has completed.
      operationId: completeLayerUpload
      x-api-path-slug: actioncompletelayerupload-get
      responses:
        200:
          description: OK
      tags:
      - Layer Upload
  /?Action=CreateRepository:
    get:
      summary: Create Repository
      description: Creates an image repository.
      operationId: createRepository
      x-api-path-slug: actioncreaterepository-get
      parameters:
      - in: query
        name: repositoryName
        description: The name to use for the repository
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repositories
  /?Action=DeleteRepository:
    get:
      summary: Delete Repository
      description: Deletes an existing image repository.
      operationId: deleteRepository
      x-api-path-slug: actiondeleterepository-get
      parameters:
      - in: query
        name: force
        description: Force the deletion of the repository if it contains images
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the repository to delete
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repositories
  /?Action=DescribeRepositories:
    get:
      summary: Describe Repositories
      description: Describes image repositories in a registry.
      operationId: describeRepositories
      x-api-path-slug: actiondescriberepositories-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of repository results returned by DescribeRepositories
          in            paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated                DescribeRepositories
          request where maxResults was used and            the results exceeded the
          value of that parameter
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the repositories to be described
        type: string
      - in: query
        name: repositoryNames
        description: A list of repositories to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repositories
  /?Action=GetDownloadUrlForLayer:
    get:
      summary: Get Download Url For Layer
      description: .Retrieves the pre-signed Amazon S3 download URL corresponding
        to an image layer. You can only get URLs for image layers that are referenced
        in an image.
      operationId: getDownloadUrlForLayer
      x-api-path-slug: actiongetdownloadurlforlayer-get
      responses:
        200:
          description: OK
      tags:
      - Layers
  /?Action=InitiateLayerUpload:
    get:
      summary: Initiate Layer Upload
      description: Notify Amazon ECR that you intend to upload an image layer.
      operationId: initiateLayerUpload
      x-api-path-slug: actioninitiatelayerupload-get
      responses:
        200:
          description: OK
      tags:
      - Layer Upload
  /?Action=UploadLayerPart:
    get:
      summary: Upload Layer Part
      description: Uploads an image layer part to Amazon ECR.
      operationId: uploadLayerPart
      x-api-path-slug: actionuploadlayerpart-get
      responses:
        200:
          description: OK
      tags:
      - Layer Parts
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