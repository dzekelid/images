{
  "info": {
    "name": "Framesocket Query Images",
    "_postman_id": "17214057-f926-4acd-9817-4c5067f85f7b",
    "description": "Query Images",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Media",
      "item": [
        {
          "id": "0fa07e39-4d21-46f4-b201-f10475969164",
          "name": "getMediaActivate.php",
          "request": {
            "url": "http://www.framesocket.com/api/media/activate.php?customid=%7B%7D&hash=%7B%7D&key=%7B%7D&secret=%7B%7D&sig=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Activate Media"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10478255-72a7-4ce6-ab8d-d7f00a1d53ff"
            }
          ]
        },
        {
          "id": "e805ac0b-2404-4561-a790-871e0a92290b",
          "name": "getMediaDeactivate.php",
          "request": {
            "url": "http://www.framesocket.com/api/media/deactivate.php?customid=%7B%7D&hash=%7B%7D&key=%7B%7D&secret=%7B%7D&sig=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deactive Media"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ccd2af3-3cc7-4b3c-a906-d6cd4773e013"
            }
          ]
        },
        {
          "id": "9099f72a-840f-4f97-8d52-df4e5dcead01",
          "name": "getMediaImages.php",
          "request": {
            "url": "http://www.framesocket.com/api/media/images.php?customid=%7B%7D&hash=%7B%7D&key=%7B%7D&secret=%7B%7D&sig=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Query Images"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6399e29-4abc-4b73-94ab-b5c18b113281"
            }
          ]
        }
      ]
    }
  ]
}