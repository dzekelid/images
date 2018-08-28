swagger: "2.0"
x-collection-name: NewsCred
x-complete: 1
info:
  title: News Cred
  description: returns-a-list-of-articles-according-to-the-specified-set-of-parameters-
  version: v1
host: api.newscred.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  category/{dashed-name}/images/:
    get:
      summary: Category Images
      description: Gets images related to the specified category.
      operationId: getCategoryDashedNameImages
      x-api-path-slug: categorydashednameimages-get
      parameters:
      - in: query
        name: access_key
        description: Unique API access key
      - in: query
        name: safe_search
        description: Returns only images marked as safe when set to true
      responses:
        200:
          description: OK
      tags:
      - News
      - Category
      - Dashed-name
      - Images
  images/:
    get:
      summary: Search Images
      description: Returns images matched by the query string
      operationId: getImages
      x-api-path-slug: images-get
      parameters:
      - in: query
        name: access_key
        description: Unique API access key
      - in: query
        name: from_date
        description: Beginning of date range for which items are searched
      - in: query
        name: offset
        description: Number of items to skip before beginning the result set
      - in: query
        name: pagesize
        description: Number of items to return
      - in: query
        name: query
        description: Query string you want to search for
      - in: query
        name: to_date
        description: End of date range for which items are searched
      responses:
        200:
          description: OK
      tags:
      - Images
  topic/{guide{/images/:
    get:
      summary: Topic Images
      description: Returns images related to the specified topic.
      operationId: getTopicGueImages
      x-api-path-slug: topicguideimages-get
      parameters:
      - in: query
        name: access_key
        description: Unique API access key
      - in: path
        name: guid
        description: The topic guid
      responses:
        200:
          description: OK
      tags:
      - News
      - Topice
      - Images
  image/{guid}/:
    get:
      summary: Image
      description: Returns the image specified by the given GUID.
      operationId: getImageGu
      x-api-path-slug: imageguid-get
      parameters:
      - in: query
        name: access_key
        description: Unique API access key
      - in: path
        name: guid
        description: The guid for the image
      responses:
        200:
          description: OK
      tags:
      - Image