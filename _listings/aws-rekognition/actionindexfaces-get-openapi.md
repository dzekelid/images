---
swagger: "2.0"
x-collection-name: AWS Rekognition
x-complete: 0
info:
  title: AWS Rekognition API Index Faces
  version: 1.0.0
  description: Detects faces in the input image and adds them to the specified collection.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SearchFacesByImage:
    get:
      summary: Search Faces By Image
      description: |-
        For a given input image, first detects the largest face in the image, and
              then searches the specified collection for matching faces.
      operationId: searchFacesByImage
      x-api-path-slug: actionsearchfacesbyimage-get
      parameters:
      - in: query
        name: CollectionId
        description: ID of the collection to search
        type: string
      - in: query
        name: FaceMatchThreshold
        description: (Optional) Specifies the minimum confidence in the face match
          to return
        type: string
      - in: query
        name: Image
        description: Provides the source image either as bytes or an S3 object
        type: string
      - in: query
        name: MaxFaces
        description: Maximum number of faces to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Faces
  /?Action=CompareFaces:
    get:
      summary: Compare Faces
      description: |-
        Compares a face in the source input image with
              each face detected in the target input image.
      operationId: compareFaces
      x-api-path-slug: actioncomparefaces-get
      parameters:
      - in: query
        name: SimilarityThreshold
        description: The minimum level of confidence in the match you want included
          in the result
        type: string
      - in: query
        name: SourceImage
        description: Source image either as bytes or an S3 object
        type: string
      - in: query
        name: TargetImage
        description: Target image either as bytes or an S3 object
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Faces
  /?Action=DetectFaces:
    get:
      summary: Detect Faces
      description: Detects faces within an image (JPEG or PNG) that is provided as
        input.
      operationId: detectFaces
      x-api-path-slug: actiondetectfaces-get
      parameters:
      - in: query
        name: Attributes
        description: A list of facial attributes you would like to be returned
        type: string
      - in: query
        name: Image
        description: The image in which you want to detect faces
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Faces
  /?Action=DetectLabels:
    get:
      summary: Detect Labels
      description: |-
        Detects instances of real-world labels within an image (JPEG or PNG)
               provided as input.
      operationId: detectLabels
      x-api-path-slug: actiondetectlabels-get
      parameters:
      - in: query
        name: Image
        description: The input image
        type: string
      - in: query
        name: MaxLabels
        description: Maximum number of labels you want the service to return in the
          response
        type: string
      - in: query
        name: MinConfidence
        description: Specifies the minimum confidence level for the labels to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Labels
  /?Action=IndexFaces:
    get:
      summary: Index Faces
      description: Detects faces in the input image and adds them to the specified
        collection.
      operationId: indexFaces
      x-api-path-slug: actionindexfaces-get
      parameters:
      - in: query
        name: CollectionId
        description: ID of an existing collection to which you want to add the faces
          that are detected in the      input images
        type: string
      - in: query
        name: DetectionAttributes
        description: (Optional) Returns detailed attributes of indexed faces
        type: string
      - in: query
        name: ExternalImageId
        description: ID you want to assign to all the faces detected in the image
        type: string
      - in: query
        name: Image
        description: Provides the source image either as bytes or an S3 object
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Faces
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