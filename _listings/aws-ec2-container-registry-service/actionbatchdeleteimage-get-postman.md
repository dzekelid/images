{
  "info": {
    "name": "AWS EC2 Container Registry API Batch Delete Image",
    "_postman_id": "d6400cf8-5ea9-48d8-9251-f0f1c0f2ad8e",
    "description": "Deletes a list of specified images within a specified repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Layer Availability",
      "item": [
        {
          "id": "e9e79125-4c55-49c4-b0e2-6a6bf4645382",
          "name": "batchCheckLayerAvailability",
          "request": {
            "url": "http://example.com/api/?Action=BatchCheckLayerAvailability?layerDigests=layerDigests&registryId=registryId&repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Check the availability of multiple image layers in a specified registry and repository."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44a3f533-c986-41a4-88c2-694078d24de9"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "aa9b7d60-b865-449d-b2b0-1677ef37ba12",
          "name": "batchDeleteImage",
          "request": {
            "url": "http://example.com/api/?Action=BatchDeleteImage?imageIds=imageIds&registryId=registryId&repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a list of specified images within a specified repository."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fcfec62-2bd7-4f6f-81d0-9fa630b494b7"
            }
          ]
        }
      ]
    }
  ]
}