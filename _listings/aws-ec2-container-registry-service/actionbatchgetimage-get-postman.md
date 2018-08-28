{
  "info": {
    "name": "AWS EC2 Container Registry API Batch Get Image",
    "_postman_id": "d520b3ab-c79c-4e9f-8ccd-ebd55f25862d",
    "description": "Gets detailed information for specified images within a specified repository.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Layer Availability",
      "item": [
        {
          "id": "b66c93d1-8922-49ef-a75d-96008b970953",
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
              "id": "9817d934-c1b8-474f-867e-a8b9f0482ee2"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "12df77c8-f645-4af2-8158-8f94e9d1d1c2",
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
              "id": "8f7e0730-c8ff-4509-a1e6-ece2c5067afd"
            }
          ]
        },
        {
          "id": "03463b79-5645-474d-a6f0-32adf58bddcd",
          "name": "batchGetImage",
          "request": {
            "url": "http://example.com/api/?Action=BatchGetImage?acceptedMediaTypes=acceptedMediaTypes&imageIds=imageIds&registryId=registryId&repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets detailed information for specified images within a specified repository."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "956db933-20c3-4b2a-92d6-e1d65d79c016"
            }
          ]
        }
      ]
    }
  ]
}