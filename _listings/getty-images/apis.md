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
- name: Getty Images Search for creative images only
  description: "Use this endpoint to search our contemporary stock photos, illustrations
    and archival images.\r\n\r\nYou'll need an API key and access token to use this
    resource. Please see our [Getting Started](http://developers.gettyimages.com/en/getting-started.html)
    \r\npage for more information on how to sign up for an API key. \r\n \r\nYou can
    show different information in the response by specifying values on the \"fields\"
    parameter (see details below).\r\nYou can search with only an API key, and that
    will give you search results that are equivalent to doing a search on the GettyImages.com
    site without being logged in (anonymous search).  If you are a Getty Images API
    customer and would like to ensure that your API searches return only assets that
    you have a license to use, you need to also include an authorization token in
    the header of your request.  Please consult our [Authorization FAQ](http://developers.gettyimages.com/en/authorization-faq.html)
    for more information on authorization tokens, and our [Authorization Workflows](https://github.com/gettyimages/gettyimages-api/blob/master/OAuth2Workflow.md)
    for code examples of getting a token.\r\n\r\n## Working with Fields Sets\r\n\r\nFields
    sets are used in the **fields** request parameter to receive a suite of metadata
    fields. The following fields sets are available:\r\n\r\n#### Summary Fields Set\r\n\r\nThe
    **summary_set** query string parameter fields value represents a small batch of
    metadata fields that are often used to \r\nbuild search response results. The
    following fields are provided for every image in your result set when you include
    **summary_set** in your request.\r\n\r\n```\r\n{\r\n    \"images\": \r\n    [\r\n
    \       \"asset_family\",\r\n        \"caption\",\r\n        \"collection_code\",\r\n
    \       \"collection_id\",\r\n        \"collection_name\",\r\n        \"display_sizes\":
    \r\n        [\r\n            {\r\n                \"name\": \"thumb\"\r\n            }\r\n
    \       ],\r\n        \"license_model\",\r\n        \"max_dimensions\",\r\n        \"title\"\r\n
    \   ]\r\n}\r\n```\r\n\r\n#### Detail Fields Set\r\n\r\nThe **detail_set** query
    string parameter fields value represents a large batch of metadata fields that
    are often used to \r\nbuild a detailed view of images. The following fields are
    provided for every image in your result set when you include **detail_set** in
    your request.\r\n\r\n```\r\n{\r\n    \"images\": \r\n    [\r\n        \"allowed_use\",\r\n
    \       \"artist\",\r\n        \"asset_family\",\r\n        \"call_for_image\",\r\n
    \       \"caption\",\r\n        \"collection_code\",\r\n        \"collection_id\",\r\n
    \       \"collection_name\",\r\n        \"copyright\",\r\n        \"date_created\",\r\n
    \       \"display_sizes\": \r\n        [\r\n            {\r\n                \"name\":
    \"comp\"\r\n            },\r\n            {\r\n                \"name\": \"preview\"\r\n
    \           },\r\n            {\r\n                \"name\": \"thumb\"\r\n            }\r\n
    \       ],\r\n        \"editorial_segments\",\r\n        \"event_ids\",\r\n        \"graphical_style\",\r\n
    \       \"license_model\",\r\n        \"max_dimensions\",\r\n        \"orientation\",\r\n
    \       \"product_types\",\r\n        \"quality_rank\",\r\n        \"referral_destinations\",\r\n
    \       \"title\"\r\n    ]\r\n]\r\n```\r\n\r\n#### Display Fields Set\r\n\r\nThe
    **display_set** query string parameter fields value represents the fields that
    provide you with URLs for the low resolution\r\nfiles that are most frequently
    used to build a UI displaying search results. The following fields are provided
    for every image \r\nin your result set when you include **display_set** in your
    request.\r\n\r\n```Go\r\n{\r\n    \"images\": \r\n    [\r\n        \"display_sizes\":
    \r\n        [\r\n            {\r\n                \"name\": \"comp\"\r\n            },\r\n
    \           {\r\n                \"name\": \"preview\"\r\n            },\r\n            {\r\n
    \               \"name\": \"thumb\"\r\n            }\r\n        ]\r\n    ]\r\n}\r\n```"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/getty-images.jpeg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com//
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-search-images-creative-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-search-images-creative-get-postman.md
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