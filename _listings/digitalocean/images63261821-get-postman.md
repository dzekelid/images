{
  "info": {
    "name": "Digital Ocean Retrieve an existing Image by id",
    "_postman_id": "eddc23e0-aa27-4652-90c9-7383fad8eaf6",
    "description": "To retrieve information about an image (public or private), send a GET request to /v2/images/$IMAGE_ID.\r\n\r\nThe response will be a JSON object with a key called image. The value of this will be an image object containing the standard image attributes:",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Retrieve",
      "item": [
        {
          "id": "d7a36d94-b750-4f86-99a9-8de1512e198c",
          "name": "Certificates892071a0Bb9549bc80213afd67a210bfGet",
          "request": {
            "url": "http://example.com/certificates/892071a0-bb95-49bc-8021-3afd67a210bf",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "To show information about an existing certificate, send a GET request to /v2/certificates/$CERTIFICATE_ID.\r\n\r\nThe response will be a JSON object with a certificate key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9f72427-7e0a-4349-87ae-aa4743313d47"
            }
          ]
        },
        {
          "id": "e31d9d43-e209-4358-96b6-a94534905065",
          "name": "Images63261821Get",
          "request": {
            "url": "http://example.com/images/63261821",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "To retrieve information about an image (public or private), send a GET request to /v2/images/$IMAGE_ID.\r\n\r\nThe response will be a JSON object with a key called image. The value of this will be an image object containing the standard image attributes:"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6084b786-48f4-4043-87ef-12d81da870b1"
            }
          ]
        }
      ]
    }
  ]
}