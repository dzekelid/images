{
  "info": {
    "name": "BBC Nitro Get raw image",
    "_postman_id": "e01474fc-9884-400f-a26a-d769d1ef7aa2",
    "description": "Get raw image",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Images",
      "item": [
        {
          "id": "454fc343-c920-45bb-b2eb-cc7899ed7a07",
          "name": "listImages",
          "request": {
            "url": "http://programmes.api.bbc.com/nitro/api/images?embargoed=%7B%7D&group=%7B%7D&image_type=%7B%7D&is_alternate_image_for=%7B%7D&is_image_for=%7B%7D&page=%7B%7D&page_size=%7B%7D&partner_id=%7B%7D&partner_pid=%7B%7D&pid=%7B%7D&q=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Find metadata for images, particularly those in galleries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6558a1f-0b60-446e-a4d3-c40156e52cbd"
            }
          ]
        }
      ]
    },
    {
      "name": "V1",
      "item": [
        {
          "id": "70261b29-d494-4ce9-b384-4942a8d493e6",
          "name": "Get_Raw_image",
          "request": {
            "url": {
              "protocol": "http",
              "host": "programmes.api.bbc.com",
              "path": [
                "nitro",
                "api",
                "v1/images/:pid"
              ],
              "variable": [
                {
                  "id": "pid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get raw image"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "875da43a-f733-4279-bad1-2469d0fd1559"
            }
          ]
        }
      ]
    }
  ]
}