---
name: BBC
x-slug: bbc
description: Breaking news, sport, TV, radio and a whole lot more. The BBC informs,
  educates and entertains - wherever you are, whatever your age.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
x-kinRank: "7"
x-alexaRank: "93"
tags: Images
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/bbc/apis.md
specificationVersion: "0.14"
apis:
- name: BBC Nitro Find metadata for images
  x-api-slug: bbc-nitro
  description: Find metadata for images, particularly those in galleries
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//images
  tags: Images
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/bbc/images-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/bbc/images-get-openapi.md
- name: BBC Nitro Get raw image
  x-api-slug: bbc-nitro
  description: Get raw image
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/images/{pid}
  tags: V1,Images,Pid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/bbc/v1imagespid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/bbc/v1imagespid-get-openapi.md
- name: BBC Nitro
  x-api-slug: bbc-nitro
  description: Breaking news, sport, TV, radio and a whole lot more. The BBC informs,
    educates and entertains - wherever you are, whatever your age.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/bbc/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/bbc-news
- type: x-email
  url: dataprotection@bbc.com
- type: x-email
  url: bbcworldwidelearning@bbc.com
- type: x-twitter
  url: https://twitter.com/BBCNews
- type: x-website
  url: http://www.bbc.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---