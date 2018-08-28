---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Images
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image with Polylines
  x-api-slug: route-get
  description: "*Request an image of a map including a polyline*\n\nIt supports also
    different map schemes, image sizes; image formats as \r\nwell as zooming out from
    automatically calculated zoom level.\n  \n\n\n\n* **r0**  `text`\n \\- List of
    coordinates describing the first route\n\n* **r1**  `text`\n \\- List of coordinates
    describing the second route\n\n* **m0**  `text`\n \\- First route marker on the
    map\n\n* **m1**  `text`\n \\- Second route marker on the map\n\n* **lc0**  `text`\n
    \\- Color of the first route line displayed on the map\n\n* **sc0**  `text`\n
    \\- Shadow color of the first route line displayed on the map\n\n* **lw0**  `number`\n
    \\- Width of the first route line displayed on the map\n\n* **lc1**  `text`\n
    \\- Color of the second route line displayed on the map\n\n* **sc1**  `text`\n
    \\- Shadow color of the second route line displayed on the map\n\n* **lw1**  `number`\n
    \\- Width of the second route line displayed on the map\n\n* **w**  `number`\n
    \\- Image width in pixels, maximum 2048.\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/route-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/route-get-openapi.md
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-openapi.md
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-openapi.md
- name: Map Image API - Map Image using Bounding Box
  x-api-slug: mapview-get
  description: |-
    *Request an image of a map based around a given area*

    To specify a bounding box, add the `bbox` parameter to the request URL. On desktop browsers, redirection to `here.com` will occur automatically unless the `nord` parameter is also added to URL.



    * **bbox**  `text`
     \- Bounding box of the map specifying the top-right and bottom left corners.    e.g. `52.515,13.377,52.134,13.978`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/images/master/_listings/here/mapview-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---