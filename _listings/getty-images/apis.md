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
- name: Getty Images Get Image
  description: "This endpoint returns the detailed image metadata for a specified
    image. Due to a wide variety of available image resolutions, \r\nthe images are
    grouped into a handful of size categories for simplicity. \r\n\r\nYou'll need
    an API key and access token to use this resource. Please see our [Getting Started](http://developers.gettyimages.com/en/getting-started.html)
    \r\npage for more information on how to sign up for an API key. \r\n \r\n## Working
    with Fields Sets\r\n\r\nFields sets are used in the **fields** request parameter
    to receive a suite of metadata fields. The following fields sets are available:\r\n\r\n####
    Summary Fields Set\r\n\r\nThe **summary_set** query string parameter fields value
    represents a small batch of metadata fields that\r\nare often used to build search
    response results. The following fields are provided for every image in your\r\nresult
    set when you include **summary_set** in your request.\r\n\r\n```\r\n{\r\n    \"images\":\r\n
    \   [\r\n        \"artist\",\r\n        \"asset_family\",\r\n        \"caption\",\r\n
    \       \"collection_code\",\r\n        \"collection_id\",\r\n        \"collection_name\",\r\n
    \       \"license_model\",\r\n        \"max_dimensions\",\r\n        \"title\"\r\n
    \   ]\r\n}\r\n```\r\n\r\n#### Detail Fields Set\r\n\r\nThe **detail_set** query
    string parameter fields value represents a large batch of metadata fields that
    are \r\noften used to build a detailed view of images. The following fields are
    provided for every image in your \r\nresult set when you include **detail_set**
    in your request.\r\n\r\n```\r\n{\r\n    \"images\":\r\n    [\r\n        \"allowed_use\",\r\n
    \       \"artist\", \r\n        \"artist_title\", \r\n        \"asset_family\",\r\n
    \       \"call_for_image\",\r\n        \"caption\", \r\n        \"city\",\r\n
    \       \"collection_code\",\r\n        \"collection_id\", \r\n        \"collection_name\",\r\n
    \       \"color_type\", \r\n        \"copyright\", \r\n        \"country\", \r\n
    \       \"credit_line\", \r\n        \"date_created\", \r\n        \"date_submitted\",\r\n
    \       \"download_sizes\", \r\n        \"editorial_segments\",\r\n        \"event_ids\",\r\n
    \       \"graphical_style\",\r\n        \"license_model\",\r\n        \"max_dimensions\",\r\n
    \       \"orientation\",\r\n        \"prestige\",\r\n        \"product_types\",\r\n
    \       \"quality_rank\",\r\n        \"referral_destinations\",\r\n        \"state_province\",
    \r\n        \"title\"\r\n    ]\r\n}\r\n```\r\n\r\n#### Display Fields Set\r\n\r\nThe
    **display_set** query string parameter fields value represents the fields that
    provide you with URLs for the low\r\nresolution files that are most frequently
    used to build a UI displaying search results. The following fields are provided
    \r\nfor every image in your result set when you include **display_set** in your
    request.\r\n\r\n```\r\n{\r\n    \"images\":\r\n    [\r\n        \"display_sizes\":
    \r\n        [\r\n            {\r\n                \"name\": \"comp\"\r\n            },\r\n
    \           {\r\n                \"name\": \"preview\"\r\n            },\r\n            {\r\n
    \               \"name\": \"thumb\"\r\n            }\r\n        ]\r\n    ]\r\n}\r\n```\r\n\r\n##
    Request Usage Considerations\r\n\r\n- Specifying the \"entity_details\" response
    field can have significant performance implications. The field should be used
    only when necessary."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/getty-images.jpeg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com//
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-images-id-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-images-id-get-postman.md
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