---
name: IBM Cloud
x-slug: ibm-cloud
description: The IBM Cloud has been built to help you solve problems and advance opportunities
  in a world flush with data. Whether it&rsquo;s data you possess, data outside your
  firewall, or data that&rsquo;s coming, the IBM Cloud helps you protect it, move
  it, integrate it and unlock intelligence from it &mdash; giving you what it takes
  to prevail in a competitive market.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28560-ibm-containers.jpg
x-kinRank: "8"
x-alexaRank: "11207"
tags: Images
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ibm-cloud/apis.md
specificationVersion: "0.14"
apis:
- name: IBM Containers - List all Docker images that are available in your private
    Bluemix registry.
  x-api-slug: imagesjson-get
  description: 'This endpoint returns a list of all available Docker images in a private
    Bluemix registry (corresponding IBM Containers command: `cf ic images`.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28560-ibm-containers.jpg
  humanURL: https://www.ibm.com/cloud/
  baseURL: https://containers-api.ng.bluemix.net//v3
  tags: SaaS, Technology, Enterprise, API Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ibm-cloud/imagesjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ibm-cloud/imagesjson-get-openapi.md
- name: IBM Containers - Remove a Docker image.
  x-api-slug: imagesid-delete
  description: 'Remove a Docker image from the private Bluemix registry that is identified
    by the image ID (corresponding IBM Containers command: `cf ic rmi <image>`).'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28560-ibm-containers.jpg
  humanURL: https://www.ibm.com/cloud/
  baseURL: https://containers-api.ng.bluemix.net//v3
  tags: SaaS, Technology, Enterprise, API Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ibm-cloud/imagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ibm-cloud/imagesid-delete-openapi.md
- name: IBM Containers - Inspect a Docker image in private Bluemix registry
  x-api-slug: imagesname-or-idjson-get
  description: 'This endpoint returns detailed information about a Docker image that
    is stored in the private Bluemix registry of an organization (corresponding IBM
    Containers command: `cf ic inspect <image_name_or_id>`).'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28560-ibm-containers.jpg
  humanURL: https://www.ibm.com/cloud/
  baseURL: https://containers-api.ng.bluemix.net//v3
  tags: SaaS, Technology, Enterprise, API Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ibm-cloud/imagesname-or-idjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ibm-cloud/imagesname-or-idjson-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://hsbc.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ibm.cloud.stack.network
- type: x-blog
  url: https://www.ibm.com/blogs/bluemix/
- type: x-crunchbase
  url: https://crunchbase.com/organization/product/ibm-bluemix
- type: x-github
  url: https://github.com/IBM-Cloud
- type: x-twitter
  url: https://twitter.com/IBMcloud
- type: x-website
  url: https://www.ibm.com/cloud/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---