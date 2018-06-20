{
  "info": {
    "name": "Constant Contact List Images",
    "_postman_id": "648b444b-32bd-43a5-90f2-43a8e56ef617",
    "description": "List Images",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "e4dcc562-04d7-429f-b692-e8f9c6057d96",
          "name": "list-images",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/library/folders/:folder-id/images"
              ],
              "query": [
                {
                  "key": "Accept",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Content-Type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "folder-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Images"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b718dec-8608-4cdc-89a4-f10e68cf84a7"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "ec614904-9968-4c92-8d62-319c5a535fbe",
          "name": "delete-all-images",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.constantcontact.com",
              "path": [
                "ws",
                "customers",
                ":username/library/folders/:folder-id/images"
              ],
              "variable": [
                {
                  "id": "folder-id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete All Images"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e4a69c9-6d4f-44a5-9bda-205e9fc3c10c"
            }
          ]
        }
      ]
    }
  ]
}