---
name: Getty Images
description: Getty Images, Inc. is an American stock photo agency, based in Seattle,
  Washington, United States. It is a supplier of stock images for business and consumers
  with an archive of 80 million still images and illustrations and more than 50,000
  hours of stock film footage. It targets three markets???creative professionals (advertising
  and graphic design), the media (print and online publishing), and corporate (in-house
  design, marketing and communication departments).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/getty-images.jpeg
x-kinRank: "8"
x-alexaRank: ""
tags:
- Videos
- Stock
- Stack Network
- Photos
- Photo API
- Photo
- Images
- Getting Started
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/apis.yaml
specificationVersion: "0.14"
apis:
- name: Getty Images
  description: Getty Images, Inc
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/getty-images.jpeg
  humanURL: ""
  baseURL: https://api.gettyimages.com//
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-videos-id-similar-get.md
- name: Getty Images Search Images by Image
  description: "Allows searching for similar creative images by passing the URL to
    an existing image.\r\n\r\nBefore calling the search by image endpoint, an image
    must be uploaded to a specific AWS S3 bucket. The bucket name is `search-by-image.s3.amazonaws.com`.\r\nFor
    example, using cURL:\r\n```sh\r\ncurl -i -X PUT https://search-by-image.s3.amazonaws.com/my-test-image.jpg
    -H \"Content-Type: image/jpeg\" --data-binary \"@testimage.jpg\"\r\n```\r\n\r\nUploads
    can be overwritten if the names are the same, so using a prefix like the API Key,
    application name or company name would help keep that\r\nfrom happening.\r\n\r\nOnce
    the image has been uploaded, use the full URL in the `image_url` parameter, e.g.
    `image_url=https://search-by-image.s3.amazonaws.com/my-test-image.jpg`.\r\n\r\nSubsequent
    searches for the same image can be executed using the `image_fingerprint` that
    is returned by the inital search."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/getty-images.jpeg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com//
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-search-images-creative-by-image-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-search-images-creative-by-image-get-postman.md
x-common:
- type: x-authentication
  url: https://github.com/gettyimages/connect#authentication
- type: x-base
  url: https://connect.gettyimages.com/
- type: x-net-sdk
  url: https://github.com/gettyimages/connect_sdk_csharp
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ge-tt
- type: x-developer
  url: http://api.gettyimages.com/
- type: x-documentation
  url: https://api.gettyimages.com/swagger/ui/index.html
- type: x-embeddable
  url: https://github.com/gettyimages/connect#oembed
- type: x-forum
  url: http://api.gettyimages.com/forum
- type: x-getting-started
  url: https://github.com/gettyimages/connect#getting-started
- type: x-github
  url: https://github.com/gettyimages
- type: x-java-sdk
  url: https://github.com/gettyimages/connect_sdk_java
- type: x-nodejs-sdk
  url: https://github.com/gettyimages/connect_sdk_nodejs
- type: x-objectivec-sdk
  url: https://github.com/gettyimages/connect_sdk_objective-c
- type: x-php-sdk
  url: https://github.com/gettyimages/connect_sdk_php
- type: x-pricing
  url: http://www.gettyimages.com/subscribe
- type: x-ruby-sdk
  url: https://github.com/gettyimages/connect_sdk_ruby
- type: x-twitter
  url: https://twitter.com/GettyImages
- type: x-website
  url: http://www.gettyimages.com/
- type: x-authentication
  url: https://github.com/gettyimages/connect#authentication
- type: x-base
  url: https://connect.gettyimages.com/
- type: x-net-sdk
  url: https://github.com/gettyimages/connect_sdk_csharp
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ge-tt
- type: x-developer
  url: http://api.gettyimages.com/
- type: x-documentation
  url: https://api.gettyimages.com/swagger/ui/index.html
- type: x-embeddable
  url: https://github.com/gettyimages/connect#oembed
- type: x-forum
  url: http://api.gettyimages.com/forum
- type: x-getting-started
  url: https://github.com/gettyimages/connect#getting-started
- type: x-github
  url: https://github.com/gettyimages
- type: x-java-sdk
  url: https://github.com/gettyimages/connect_sdk_java
- type: x-nodejs-sdk
  url: https://github.com/gettyimages/connect_sdk_nodejs
- type: x-objectivec-sdk
  url: https://github.com/gettyimages/connect_sdk_objective-c
- type: x-php-sdk
  url: https://github.com/gettyimages/connect_sdk_php
- type: x-pricing
  url: http://www.gettyimages.com/subscribe
- type: x-ruby-sdk
  url: https://github.com/gettyimages/connect_sdk_ruby
- type: x-twitter
  url: https://twitter.com/GettyImages
- type: x-website
  url: http://www.gettyimages.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---