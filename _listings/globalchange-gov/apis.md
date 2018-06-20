---
name: GlobalChange.gov
x-slug: globalchange-gov
description: The U.S. Global Change Research Program (USGCRP) was established by Presidential
  Initiative in 1989 and mandated by Congress in the Global Change Research Act (GCRA)
  of 1990 to &ldquo;assist the Nation and the world to understand, assess, predict,
  and respond to human-induced and natural processes of global change.&rdquo;
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Images
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/globalchange-gov/apis.md
specificationVersion: "0.14"
apis:
- name: Global Change Information System API List images.
  x-api-slug: global-change-information-system-api
  description: List the images, 20 per page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov////image
  tags: Images
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/globalchange-gov/image-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/globalchange-gov/image-get-openapi.md
- name: Global Change Information System API List images associated with a report.
  x-api-slug: global-change-information-system-api
  description: List the images associated with a report, 20 per page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov////report/{report_identifier}/image
  tags: Images,Associated,Report
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/globalchange-gov/reportreport-identifierimage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/globalchange-gov/reportreport-identifierimage-get-openapi.md
- name: Global Change Information System API
  x-api-slug: global-change-information-system-api
  description: The U.S. Global Change Research Program (USGCRP) was established by
    Presidential Initiative in 1989 and mandated by Congress in the Global Change
    Research Act (GCRA) of 1990 to &ldquo;assist the Nation and the world to understand,
    assess, predict, and respond to human-induced and natural processes of global
    change.&rdquo;
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov//
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/globalchange-gov/openapi.md
x-common:
- type: x-developer
  url: http://data.globalchange.gov/
- type: x-website
  url: http://globalchange.gov/
- type: x-website
  url: http://globalchange.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---