---
name: UK National Archives Discovery
x-slug: uk-national-archives-discovery
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Images
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/apis.md
specificationVersion: "0.14"
apis:
- name: Getty Images Search API Post Downloads Images
  x-api-slug: getty-images-search-api
  description: Download an image.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com////v3/downloads/images/{id}
  tags: Downloads,Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/v3downloadsimagesid-post-openapi.md
- name: Getty Images Search API Get Images
  x-api-slug: getty-images-search-api
  description: Get metadata for multiple images by supplying multiple image ids.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com////v3/images
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/v3images-get-openapi.md
- name: Getty Images Search API Get Images
  x-api-slug: getty-images-search-api
  description: Get metadata for a single image by supplying one image id.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com////v3/images/{id}
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/v3imagesid-get-openapi.md
- name: Getty Images Search API Get Images Similar
  x-api-slug: getty-images-search-api
  description: Search for images similar to an image.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com////v3/images/{id}/similar
  tags: Images,Similar
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/v3imagesidsimilar-get-openapi.md
- name: Getty Images Search API Get Purchased Images
  x-api-slug: getty-images-search-api
  description: Get previously purchased images.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com////v3/purchased-images
  tags: Purchased,Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/v3purchasedimages-get-openapi.md
- name: Getty Images Search API Get Search Images
  x-api-slug: getty-images-search-api
  description: Search for both creative and editorial images.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com////v3/search/images
  tags: Search,Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/v3searchimages-get-openapi.md
- name: Getty Images Search API Get Search Images Creative
  x-api-slug: getty-images-search-api
  description: Search for creative images only.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com////v3/search/images/creative
  tags: Search,Images,Creative
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/v3searchimagescreative-get-openapi.md
- name: Getty Images Search API Get Search Images Editorial
  x-api-slug: getty-images-search-api
  description: Search for editorial images only.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com////v3/search/images/editorial
  tags: Search,Images,Editorial
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/v3searchimageseditorial-get-openapi.md
- name: Getty Images Search API
  x-api-slug: getty-images-search-api
  description: Our set of APIs enable seamless integration of Getty Images expansive
    content, powerful search and rich metadata directly into your internal workflows,
    products and services. With Connects API solutions, you can fully control, customize
    and scale as you grow.
  image: ""
  humanURL: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
  baseURL: https://api.gettyimages.com//
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/uk-national-archives-discovery/openapi.md
x-common:
- type: x-website
  url: http://discovery.nationalarchives.gov.uk/SearchUI/api.htm
- type: x-website
  url: http:///Search
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---