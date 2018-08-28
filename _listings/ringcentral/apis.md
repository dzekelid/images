---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Images
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-get
  description: "Returns a profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-401\nAuthorization header
    is not specified\n\n\n401\nAGW-402\nInvalid Authorization header\n\n\n403\nCMN-109\nFeature
    Profile Image Streaming is unavailable\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Upload User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-post
  description: "Returns the extension profile image.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [EditExtensions] permission"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Update User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-put
  description: "Updates profile image of an extension.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nACT-331\nProfile image not
    valid\n\n\n400\nACT-334\nProfile image file is more than 12 megapixel\n\n\n400\nCMN-101\nParameter
    [image] value is invalid\n\n\n403\nACT-332\nProfile image could not be set for
    an extension in unassigned status\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserInfo] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found\n\n\n415\nACT-330\nUnsupported image content type"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Profile Image (Scaled)
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
  description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile image is
    not found for scale size [92]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-get
  description: "Returns a profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-401\nAuthorization header
    is not specified\n\n\n401\nAGW-402\nInvalid Authorization header\n\n\n403\nCMN-109\nFeature
    Profile Image Streaming is unavailable\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Upload User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-post
  description: "Returns the extension profile image.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [EditExtensions] permission"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Update User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-put
  description: "Updates profile image of an extension.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nACT-331\nProfile image not
    valid\n\n\n400\nACT-334\nProfile image file is more than 12 megapixel\n\n\n400\nCMN-101\nParameter
    [image] value is invalid\n\n\n403\nACT-332\nProfile image could not be set for
    an extension in unassigned status\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserInfo] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found\n\n\n415\nACT-330\nUnsupported image content type"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Profile Image (Scaled)
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
  description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile image is
    not found for scale size [92]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Profile Image (Scaled)
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
  description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile image is
    not found for scale size [92]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Extension Profile Image (Scaled)
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get
  description: "Returns profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nACT-333\nProfile image is
    not found for scale size [92]"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimagescalesize-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-put
  description: "Updates profile image of an extension.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nACT-331\nProfile image not
    valid\n\n\n400\nACT-334\nProfile image file is more than 12 megapixel\n\n\n400\nCMN-101\nParameter
    [image] value is invalid\n\n\n403\nACT-332\nProfile image could not be set for
    an extension in unassigned status\n\n\n403\nCMN-401\nIn order to call this API
    endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserInfo] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found\n\n\n415\nACT-330\nUnsupported image content type"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Upload User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-post
  description: "Returns the extension profile image.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [EditExtensions] permission"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Upload User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-post
  description: "Returns the extension profile image.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserInfo\nUsage Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n403\nCMN-401\nIn order to call
    this API endpoint, application needs to have [EditExtensions] permission"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-get
  description: "Returns a profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-401\nAuthorization header
    is not specified\n\n\n401\nAGW-402\nInvalid Authorization header\n\n\n403\nCMN-109\nFeature
    Profile Image Streaming is unavailable\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get User Profile Image
  x-api-slug: restapiv1-0accountaccountidextensionextensionidprofileimage-get
  description: "Returns a profile image of an extension.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-401\nAuthorization header
    is not specified\n\n\n401\nAGW-402\nInvalid Authorization header\n\n\n403\nCMN-109\nFeature
    Profile Image Streaming is unavailable\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [extensionId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidprofileimage-get-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---