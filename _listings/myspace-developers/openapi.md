swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 1
info:
  title: My Space
  description: create-apps-and-games-within-the-myspace-platform--monetize-through-advertising-and-virtual-goods-
  version: 1.0.0
host: api.myspace.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /opensearch/images:
    get:
      summary: Get Opensearch Images
      description: Returns search results for images.
      operationId: opensearch.images.get
      x-api-path-slug: opensearchimages-get
      parameters:
      - in: query
        name: count
        description: Number of items to return
      - in: query
        name: culture
        description: The culture context of the search
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: searchTerms
        description: Free form search terms or query words
      - in: query
        name: sortBy
        description: How to sort the images
      - in: query
        name: sortOrder
        description: Indicates whether to sort ascending or descending
      - in: query
        name: startPage
        description: Which page to start at for the results
      responses:
        200:
          description: OK
      tags:
      - Opensearch
      - Images