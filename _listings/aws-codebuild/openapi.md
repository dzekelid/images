swagger: "2.0"
x-collection-name: AWS CodeBuild
x-complete: 1
info:
  title: AWS CodeBuild API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListCuratedEnvironmentImages:
    get:
      summary: List Curated Environment Images
      description: Gets information about Docker images that are managed by AWS CodeBuild.
      operationId: listCuratedEnvironmentImages
      x-api-path-slug: actionlistcuratedenvironmentimages-get
      parameters:
      - in: query
        name: platforms
        description: Information about supported platforms for Docker images that
          are managed by AWS CodeBuild
        type: string
      responses:
        200:
          description: OK
      tags:
      - Curated Environments