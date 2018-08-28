{
  "info": {
    "name": "Data.gov API Add Post Image",
    "_postman_id": "5d52ace2-ee96-4fc1-89d9-7ef0fac693ce",
    "description": "Upload a new image",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "posts",
      "item": [
        {
          "id": "44121629-ee14-4f06-9d97-9d63d784252b",
          "name": "postPostsPostImage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "catalog.data.gov",
              "path": [
                "api",
                "3",
                "posts/:post/image"
              ],
              "variable": [
                {
                  "id": "post",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "bbox",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "file",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Upload a new image"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0651ed9f-8aaf-4e4a-98ab-c7e097ea0271"
            }
          ]
        }
      ]
    }
  ]
}