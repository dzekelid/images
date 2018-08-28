swagger: "2.0"
x-collection-name: IBM Cloud
x-complete: 1
info:
  title: IBM Containers
  description: containers-are-virtual-software-objects-that-include-all-the-elements-that-an-app-needs-to-run--a-container-has-the-benefits-of-resource-isolation-and-allocation-but-is-more-portable-and-efficient-than-for-example-a-virtual-machine--this-documentation-describes-the-ibm-containers-api-which-is-based-on-the-docker-remote-api--the-api-provides-endpoints-that-you-can-use-to-create-and-manage-your-single-containers-and-container-groups-in-bluemix--endpoints-are-summarized-under-the-following-tags--authentication-retrieve-and-refresh-your-tls-certificates---private-docker-images-registry-create-your-own-private-docker-images-registry-in-bluemix-by-setting-a-namespace-for-your-organization---images-view-build-and-push-your-images-to-your-private-bluemix-registry-so-you-can-use-them-with-ibm-containers--you-can-also-scan-your-container-images-with-the-vulnerability-advisor-against-standard-policies-set-by-the-organization-manager-and-a-database-of-known-ubuntu-issues---single-containers-create-and-manage-single-containers-in-bluemix--use-a-single-container-to-implement-shortlived-processes-or-to-run-simple-tests-as-you-develop-an-app-or-service--to-make-your-single-container-available-from-the-internet-review-the-public-ip-addresses-endpoints---container-groups-create-and-manage-your-container-groups-in-bluemix--a-container-group-consists-of-multiple-single-containers-that-are-all-created-from-the-same-container-image-and-as-a-consequence-are-configured-in-the-same-way--container-groups-offer-further-options-at-no-cost-to-make-your-app-highly-available--these-options-include-inbuilt-load-balancing-autorecovery-of-unhealthy-container-instances-and-autoscaling-of-container-instances-based-on-cpu-and-memory-usage--map-a-public-route-to-your-container-group-to-make-your-app-accessible-from-the-internet----public-ip-addresses-use-these-endpoints-to-request-public-ip-addresses-for-your-space--you-can-bind-this-ip-address-to-your-container-to-make-your-container-accessible-from-the-internet---file-shares-create-list-and-delete-file-shares-in-a-space--a-file-share-is-a-nfs-storage-system-that-hosts-docker-volumes----volumes-create-and-manage-container-volumes-in-your-space-to-persist-the-data-of-your-containers----each-api-request-requires-an-http-header-that-includes-the-xauthtoken-and-xauthprojectid-parameter---xauthtoken-the-json-web-token-jwt-that-you-receive-when-logging-into-the-bluemix-platform--it-allows-you-to-use-the-ibm-containers-rest-api-access-services-and-resources--run-cf-oauthtoken-to-retrieve-your-access-token-information--xauthprojectid-the-unique-id-of-your-organization-space-where-you-want-to-create-or-work-with-your-containers--run-cf-space-space-name-guid-where-space-name-is-the-name-of-your-space-to-retrieve-your-space-id--for-further-information-about-how-containers-work-in-the-ibm-containers-service-review-the-documentation-under-httpsnewconsole-ng-bluemix-netdocscontainerscontainer-index-html--
  version: 3.0.0
host: containers-api.ng.bluemix.net
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /images/json:
    get:
      summary: List all Docker images that are available in your private Bluemix registry.
      description: 'This endpoint returns a list of all available Docker images in
        a private Bluemix registry (corresponding IBM Containers command: `cf ic images`.'
      operationId: this-endpoint-returns-a-list-of-all-available-docker-images-in-a-private-bluemix-registry-correspond
      x-api-path-slug: imagesjson-get
      parameters:
      - in: header
        name: X-Auth-Project-Id
        description: The unique ID of your organization space where you want to create
          or work with your containers
      - in: header
        name: X-Auth-Token
        description: The Bluemix JSON web token that you receive when logging into
          Bluemix
      responses:
        200:
          description: OK
      tags:
      - Images
      - Json
  /images/{id}:
    delete:
      summary: Remove a Docker image.
      description: 'Remove a Docker image from the private Bluemix registry that is
        identified by the image ID (corresponding IBM Containers command: `cf ic rmi
        <image>`).'
      operationId: remove-a-docker-image-from-the-private-bluemix-registry-that-is-identified-by-the-image-id-correspon
      x-api-path-slug: imagesid-delete
      parameters:
      - in: path
        name: id
        description: The unique identifier representing a Docker image
      - in: header
        name: X-Auth-Project-Id
        description: The unique ID of your organization space where you want to create
          or work with your containers
      - in: header
        name: X-Auth-Token
        description: The Bluemix JSON web token that you receive when logging into
          Bluemix
      responses:
        200:
          description: OK
      tags:
      - Images
  /images/{name_or_id}/json:
    get:
      summary: Inspect a Docker image in private Bluemix registry
      description: 'This endpoint returns detailed information about a Docker image
        that is stored in the private Bluemix registry of an organization (corresponding
        IBM Containers command: `cf ic inspect <image_name_or_id>`).'
      operationId: this-endpoint-returns-detailed-information-about-a-docker-image-that-is-stored-in-the-private-bluemi
      x-api-path-slug: imagesname-or-idjson-get
      parameters:
      - in: path
        name: name_or_id
        description: The full private Bluemix registry path to your image or the unique
          ID of the image that you want to inspect
      - in: header
        name: X-Auth-Project-Id
        description: The unique ID of your organization space where you want to create
          or work with your containers
      - in: header
        name: X-Auth-Token
        description: The Bluemix JSON web token that you receive when logging into
          Bluemix
      responses:
        200:
          description: OK
      tags:
      - Images
      - Name
      - Json