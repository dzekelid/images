---
name: AWS EC2 Container Registry Service
x-slug: aws-ec2-container-registry-service
description: Amazon EC2 Container Registry (ECR) is a fully-managedDockercontainer
  registry that makes it easy for developers to store, manage, and deploy Docker container
  images. Amazon ECR is integrated withAmazon EC2 Container Service (ECS), simplifying
  your development to production workflow. Amazon ECR eliminates the need to operate
  your own container repositories or worry about scaling the underlying infrastructure.
  Amazon ECR hosts your images in a highly available and scalable architecture, allowing
  you to reliably deploy containers for your applications. Integration with AWS Identity
  and Access Management (IAM) provides resource-level control of each repository.
  With Amazon ECR, there are no upfront fees or commitments. You pay only for the
  amount of data you store in your repositories and data transferred to the Internet.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Images
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 Container Registry API - Describe Images
  x-api-slug: actiondescribeimages-get
  description: |-
    Returns metadata about the images in a repository, including image size, image
                tags, and creation date.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actiondescribeimages-get-openapi.md
- name: AWS EC2 Container Registry API - List Images
  x-api-slug: actionlistimages-get
  description: Lists all the image IDs for a given repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionlistimages-get-openapi.md
- name: AWS EC2 Container Registry API - Put Image
  x-api-slug: actionputimage-get
  description: Creates or updates the image manifest and tags associated with an image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionputimage-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Delete Image
  x-api-slug: actionbatchdeleteimage-get
  description: Deletes a list of specified images within a specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchdeleteimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchdeleteimage-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Get Image
  x-api-slug: actionbatchgetimage-get
  description: Gets detailed information for specified images within a specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchgetimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchgetimage-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Delete Image
  x-api-slug: actionbatchdeleteimage-get
  description: Deletes a list of specified images within a specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchdeleteimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchdeleteimage-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Get Image
  x-api-slug: actionbatchgetimage-get
  description: Gets detailed information for specified images within a specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchgetimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchgetimage-get-openapi.md
- name: AWS EC2 Container Registry API - Describe Images
  x-api-slug: actiondescribeimages-get
  description: |-
    Returns metadata about the images in a repository, including image size, image
                tags, and creation date.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actiondescribeimages-get-openapi.md
- name: AWS EC2 Container Registry API - List Images
  x-api-slug: actionlistimages-get
  description: Lists all the image IDs for a given repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionlistimages-get-openapi.md
- name: AWS EC2 Container Registry API - Put Image
  x-api-slug: actionputimage-get
  description: Creates or updates the image manifest and tags associated with an image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionputimage-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Delete Image
  x-api-slug: actionbatchdeleteimage-get
  description: Deletes a list of specified images within a specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchdeleteimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchdeleteimage-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Get Image
  x-api-slug: actionbatchgetimage-get
  description: Gets detailed information for specified images within a specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchgetimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchgetimage-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Check Layer Availability
  x-api-slug: actionbatchchecklayeravailability-get
  description: Check the availability of multiple image layers in a specified registry
    and repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchchecklayeravailability-get-openapi.md
- name: AWS EC2 Container Registry API - Complete Layer Upload
  x-api-slug: actioncompletelayerupload-get
  description: Inform Amazon ECR that the image layer upload for a specified registry,
    repository name, and upload ID, has completed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actioncompletelayerupload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actioncompletelayerupload-get-openapi.md
- name: AWS EC2 Container Registry API - Create Repository
  x-api-slug: actioncreaterepository-get
  description: Creates an image repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actioncreaterepository-get-openapi.md
- name: AWS EC2 Container Registry API - Delete Repository
  x-api-slug: actiondeleterepository-get
  description: Deletes an existing image repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actiondeleterepository-get-openapi.md
- name: AWS EC2 Container Registry API - Describe Images
  x-api-slug: actiondescribeimages-get
  description: |-
    Returns metadata about the images in a repository, including image size, image
                tags, and creation date.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actiondescribeimages-get-openapi.md
- name: AWS EC2 Container Registry API - Describe Repositories
  x-api-slug: actiondescriberepositories-get
  description: Describes image repositories in a registry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actiondescriberepositories-get-openapi.md
- name: AWS EC2 Container Registry API - Get Download Url For Layer
  x-api-slug: actiongetdownloadurlforlayer-get
  description: .Retrieves the pre-signed Amazon S3 download URL corresponding to an
    image layer. You can only get URLs for image layers that are referenced in an
    image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actiongetdownloadurlforlayer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actiongetdownloadurlforlayer-get-openapi.md
- name: AWS EC2 Container Registry API - Initiate Layer Upload
  x-api-slug: actioninitiatelayerupload-get
  description: Notify Amazon ECR that you intend to upload an image layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actioninitiatelayerupload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actioninitiatelayerupload-get-openapi.md
- name: AWS EC2 Container Registry API - List Images
  x-api-slug: actionlistimages-get
  description: Lists all the image IDs for a given repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionlistimages-get-openapi.md
- name: AWS EC2 Container Registry API - Put Image
  x-api-slug: actionputimage-get
  description: Creates or updates the image manifest and tags associated with an image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionputimage-get-openapi.md
- name: AWS EC2 Container Registry API - Upload Layer Part
  x-api-slug: actionuploadlayerpart-get
  description: Uploads an image layer part to Amazon ECR.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionuploadlayerpart-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionuploadlayerpart-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Delete Image
  x-api-slug: actionbatchdeleteimage-get
  description: Deletes a list of specified images within a specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchdeleteimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchdeleteimage-get-openapi.md
- name: AWS EC2 Container Registry API - Batch Get Image
  x-api-slug: actionbatchgetimage-get
  description: Gets detailed information for specified images within a specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Amazon Web Services, Containers, Discovery, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchgetimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionbatchgetimage-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.ec2.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.container.registry.service.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonECR/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ecr/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/ecr/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/ecr/pricing/
- type: x-website
  url: https://aws.amazon.com/ecr/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---