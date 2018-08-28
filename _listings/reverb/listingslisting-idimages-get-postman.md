{
  "info": {
    "name": "reverb Get Listings Listing Images",
    "_postman_id": "24ba155c-59c4-4049-91ba-d89bd814f3c7",
    "description": "View the images associated with a particular listing",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Listings",
      "item": [
        {
          "id": "11f7ebd7-5e6b-4004-a048-6a7bbe00c7c9",
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
              "id": "c57d4e4d-7738-4066-b475-8e22c98b7761"
            }
          ]
        }
      ]
    }
  ]
}