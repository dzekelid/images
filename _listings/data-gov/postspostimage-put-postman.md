{
  "info": {
    "name": "Data.gov API Update Post Image",
    "_postman_id": "778704f6-3477-4e60-9f5d-5d3e99e605c7",
    "description": "Set the image BBox",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "posts",
      "item": [
        {
          "id": "3081f457-3540-4c31-bec3-e3bd140f728a",
          "name": "putPostsPostImage",
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
            "method": "PUT",
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
            "description": "Set the image BBox"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c0ed4f31-e51a-481f-a24c-30dfac6aa04d"
            }
          ]
        }
      ]
    }
  ]
}