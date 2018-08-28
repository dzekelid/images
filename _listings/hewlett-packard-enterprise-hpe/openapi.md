swagger: "2.0"
x-collection-name: Hewlett Packard Enterprise (HPE)
x-complete: 1
info:
  title: HPE OneSphere API
  description: hpe-onesphere-hybrid-cloud-management-rest-api-for-calls-requiring-authentication-use-restsession-to-get-a-token-
  termsOfService: http://www.hpe.com/onesphere
  contact:
    name: HPE OneSphere API team
    url: http://www.hpe.com/onesphere
  version: 1.0.0
host: deic02-hpe.hpeonesphere.com
basePath: /rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /regions/{id}/connector-image:
    get:
      summary: Get Regions Connector Image
      description: Generates connector-image url for the region. It requires the **administrator**
        role.
      operationId: getConnectorImage
      x-api-path-slug: regionsidconnectorimage-get
      parameters:
      - in: path
        name: id
        description: ID of region to fetch the connector-image
      responses:
        200:
          description: OK
      tags:
      - Regions
      - Connector
      - Image
  /zones/{id}/appliance-image:
    get:
      summary: Get Zones Appliance Image
      description: Generates appliance-image url for the zone
      operationId: appliance-image
      x-api-path-slug: zonesidapplianceimage-get
      parameters:
      - in: path
        name: id
        description: ID of zone to fetch the appliance-image
      responses:
        200:
          description: OK
      tags:
      - Zones
      - Appliance
      - Image