{
  "info": {
    "name": "BigCommerce Retrieve images for a single product",
    "_postman_id": "3f329d40-3fc4-42c2-b54d-8ce3a79ce70c",
    "description": "GET request for retrieving images associated with a product",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "1ef24669-8c3f-4486-a950-8cda7a658d4d",
          "name": "V3CatalogProductsImagesByStoreHashAndIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bigcommerce.com",
              "path": [
                "stores",
                ":store-hash/v3/catalog/products/:id/images"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "store-hash",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "GET request for retrieving images associated with a product"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "772df6f2-ebc7-4198-ad31-d34932a39010"
            }
          ]
        }
      ]
    }
  ]
}