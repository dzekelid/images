{
  "info": {
    "name": "News Cred Search Images",
    "_postman_id": "291d574a-b804-4de0-a675-f9b03fe0ed8b",
    "description": "Returns images matched by the query string",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "fa0b490f-eaca-411d-b29b-7f7c06762f1e",
          "name": "getCategoryDashedNameImages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "category/:dashed-name/images/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "safe_search",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "dashed-name",
                  "value": "dashed-name",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets images related to the specified category."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9dac029-5fca-4902-b85c-c27530843e16"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "4d7ec1a9-1f6b-4c73-8d61-7af2d7c7698f",
          "name": "getImages",
          "request": {
            "url": "http://api.newscred.com/images/?access_key=%7B%7D&from_date=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&query=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns images matched by the query string"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3021f53f-8e6f-4c7d-a046-33eb544ac89e"
            }
          ]
        }
      ]
    }
  ]
}