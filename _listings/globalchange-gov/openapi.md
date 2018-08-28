swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 1
info:
  title: Global Change Information System API
  description: who-we-are-what-the-gcis-is-and-how-we-use-identifiers-and-semantic-information-to-provide-points-of-reference-and-traceability--examples-and-tutorials-for-using-this-system-as-a-researcher-citizen-scientist-application-developer-or-information-theorist--a-description-of-how-the-information-is-structured-including-the-overlaps-between-relational-and-semantic-representations-of-the-information--complete-documentation-for-the-api-including-methods-for-browsing-and-finding-resources-
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /image:
    get:
      summary: List images.
      description: List the images, 20 per page.
      operationId: list-the-images-20-per-page
      x-api-path-slug: image-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the images
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Images
  /report/{report_identifier}/image:
    get:
      summary: List images associated with a report.
      description: List the images associated with a report, 20 per page.
      operationId: list-the-images-associated-with-a-report-20-per-page
      x-api-path-slug: reportreport-identifierimage-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the images
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: report_identifier
        description: report_identifier description
      responses:
        200:
          description: OK
      tags:
      - Images
      - Associated
      - Report
  /image/{image_identifier}:
    get:
      summary: Get a representation of an image.
      description: Get JSON which represents the structure of an image.
      operationId: get-json-which-represents-the-structure-of-an-image
      x-api-path-slug: imageimage-identifier-get
      parameters:
      - in: path
        name: image_identifier
        description: image_identifier description
      - in: query
        name: with_gcmd
        description: Include GCMD keywords associated with the image
      - in: query
        name: with_regions
        description: Include regions associated with the image
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Image