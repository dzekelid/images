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
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 Container Registry API Describe Images
  x-api-slug: aws-ec2-container-registry-api
  description: |-
    Returns metadata about the images in a repository, including image size, image
                tags, and creation date.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: ://///?Action=DescribeImages
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actiondescribeimages-get-openapi.md
- name: AWS EC2 Container Registry API List Images
  x-api-slug: aws-ec2-container-registry-api
  description: Lists all the image IDs for a given repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: ://///?Action=ListImages
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionlistimages-get-openapi.md
- name: AWS EC2 Container Registry API Put Image
  x-api-slug: aws-ec2-container-registry-api
  description: Creates or updates the image manifest and tags associated with an image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: ://///?Action=PutImage
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/actionputimage-get-openapi.md
- name: AWS EC2 Container Registry API
  x-api-slug: aws-ec2-container-registry-api
  description: Amazon EC2 Container Registry (ECR) is a fully-managedDockercontainer
    registry that makes it easy for developers to store, manage, and deploy Docker
    container images. Amazon ECR is integrated withAmazon EC2 Container Service (ECS),
    simplifying your development to production workflow. Amazon ECR eliminates the
    need to operate your own container repositories or worry about scaling the underlying
    infrastructure. Amazon ECR hosts your images in a highly available and scalable
    architecture, allowing you to reliably deploy containers for your applications.
    Integration with AWS Identity and Access Management (IAM) provides resource-level
    control of each repository. With Amazon ECR, there are no upfront fees or commitments.
    You pay only for the amount of data you store in your repositories and data transferred
    to the Internet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECR.png
  humanURL: https://aws.amazon.com/ecr/
  baseURL: :///
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/aws-ec2-container-registry-service/openapi.md
x-common:
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