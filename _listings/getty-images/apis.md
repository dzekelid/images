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
- name: Getty Images Search for events
  description: "Use this endpoint to search Getty Images news, sports and entertainment
    events. Getty Images photographers and videographers cover editorially relevant
    events occurring around the world.  All images or video clips produced in association
    with an event, are assigned the same EventID. EventIDs are part of the meta-data
    returned in Search Results. Only content produced under a Getty Images brand name
    (Getty Images News, Getty Images Sports, Getty Images Entertainment, Film Magic,
    Wire Image) will be consistently assigned an EventID. The Event framework may
    also be used to group similar content, such as \"Hats from the Royal Wedding\"
    or \"Odd-ballOffbeat images of the week\".   \r\n\r\nYou'll need an API key and
    access token to use this resource. Please see our [Getting Started](http://developers.gettyimages.com/en/getting-started.html)
    page for more information on how to sign up for an API key.\r\n\r\n\r\nYou can
    show different information in the response by specifying values on the \"fields\"
    parameter (see details below).\r\nYou can search with only an API key, and that
    will give you search results that are equivalent to doing a search on the GettyImages.com
    site without being logged in (anonymous search).  If you are a Getty Images API
    customer and would like to ensure that your API searches return only assets that
    you have a license to use, you need to also include an authorization token in
    the header of your request.  Please consult our [Authorization FAQ](http://developers.gettyimages.com/en/authorization-faq.html)
    for more information on authorization tokens, and our [Authorization Workflows](https://github.com/gettyimages/gettyimages-api/blob/master/OAuth2Workflow.md)
    for code examples of getting a token."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/getty-images.jpeg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com//
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-search-events-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/getty-images/v3-search-events-get-postman.md
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