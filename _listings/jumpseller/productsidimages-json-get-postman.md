{
  "info": {
    "name": "Jumpseller Get Products Images",
    "_postman_id": "9ff40e41-ebe0-46a2-ae4b-304a7b3f355f",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Products",
      "item": [
        {
          "id": "c3735924-9ecb-4d26-8ef6-e5b07ef72b8e",
          "name": "getProductsImages.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "products/:id/images.json"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Products Images"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc0afb3a-a5c3-491c-a0e5-f59cc63174a8"
            }
          ]
        }
      ]
    }
  ]
}