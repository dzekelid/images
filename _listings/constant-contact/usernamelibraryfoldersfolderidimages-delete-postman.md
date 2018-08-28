{
  "info": {
    "name": "Constant Contact Delete All Images",
    "_postman_id": "98b588f7-fa4b-4a93-9057-5b6420131d0d",
    "description": "Delete All Images",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Images",
      "item": [
        {
          "id": "d2756a43-0b1b-48d1-b9c2-4799dcbc0b8a",
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
              "id": "591adc3b-ce2f-463d-8734-9ff25baefd7f"
            }
          ]
        }
      ]
    }
  ]
}