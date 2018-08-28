{
  "info": {
    "name": "reverb Delete Listings Listing Images Image",
    "_postman_id": "379bb175-727e-43c6-8e0e-fcc8f01b302b",
    "description": "Delete listings listing images image.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Listings",
      "item": [
        {
          "id": "904ebdcd-2f1d-4d8d-a34e-1acebe15dc5b",
          "name": "getListingsListingImages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "listings/:listing_id/images"
              ],
              "variable": [
                {
                  "id": "listing_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "View the images associated with a particular listing"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b49d7be0-a007-466a-ae28-adf9075495ac"
            }
          ]
        },
        {
          "id": "9904f55d-6d19-40a6-9d3e-2e40ff4b010a",
          "name": "deleteListingsListingImagesImage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "listings/:listing_id/images/:image_id"
              ],
              "variable": [
                {
                  "id": "image_id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "listing_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete listings listing images image."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "061c9865-1855-4106-9aa5-24006b51e79d"
            }
          ]
        }
      ]
    }
  ]
}