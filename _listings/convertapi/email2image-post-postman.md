{
  "info": {
    "name": "Convert API Email to Image",
    "_postman_id": "3ab2aea9-83d8-44f7-9475-dbd383632b87",
    "description": "The API for converting E-Mail files to PDF files and Images. These file formats eml, mbx, msg, oft can be converted to png, jpg, tif.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Email",
      "item": [
        {
          "id": "c54ba15a-6822-4483-b917-85b2d6d4ad34",
          "name": "email2image",
          "request": {
            "url": "http://do.convertapi.com/Email2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting E-Mail files to PDF files and Images. These file formats eml, mbx, msg, oft can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "289dd217-82c3-4d96-b255-16793f304931"
            }
          ]
        }
      ]
    }
  ]
}