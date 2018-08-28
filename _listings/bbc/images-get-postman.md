{
  "info": {
    "name": "BBC Nitro Find metadata for images",
    "_postman_id": "364fa819-3acd-4ace-af62-b552cb877640",
    "description": "Find metadata for images, particularly those in galleries",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Images",
      "item": [
        {
          "id": "38fe553c-8c85-4be1-bc47-38a4fb3a6e60",
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
              "id": "3b5437c1-ad1b-49bd-a505-cf4e8f89801b"
            }
          ]
        }
      ]
    }
  ]
}