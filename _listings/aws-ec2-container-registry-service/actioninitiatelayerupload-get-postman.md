{
  "info": {
    "name": "AWS EC2 Container Registry API Initiate Layer Upload",
    "_postman_id": "cedecebe-6e6e-45d4-8d53-55f4336921ff",
    "description": "Notify Amazon ECR that you intend to upload an image layer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Layer Availability",
      "item": [
        {
          "id": "b496ad75-59c0-44b0-8218-93f611f90d93",
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
              "id": "12dedc73-8c18-4b23-9564-d29fa7385b43"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "0e29014e-deef-464b-b85a-776fd8a9fa47",
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
              "id": "4e3eb040-12ba-4854-8144-4c7331301018"
            }
          ]
        },
        {
          "id": "dc553bd5-4fbe-468c-b613-8335b4cc391e",
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
              "id": "f33bc0f6-2afa-4c42-87ce-a180f8cb8abd"
            }
          ]
        }
      ]
    },
    {
      "name": "Layer Upload",
      "item": [
        {
          "id": "0a58eaa6-5644-4866-bcb8-6c6d41ae4ce4",
          "name": "completeLayerUpload",
          "request": {
            "url": "http://example.com/api/?Action=CompleteLayerUpload",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Inform Amazon ECR that the image layer upload for a specified registry, repository name, and upload ID, has completed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "338f4af3-7a10-4038-acbe-d134ca8113c6"
            }
          ]
        },
        {
          "id": "78e4c6fa-92db-46da-9bb4-4575cc3bc96d",
          "name": "initiateLayerUpload",
          "request": {
            "url": "http://example.com/api/?Action=InitiateLayerUpload",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Notify Amazon ECR that you intend to upload an image layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46df86f8-91db-4115-a328-43a9fb579a1c"
            }
          ]
        }
      ]
    },
    {
      "name": "Repositories",
      "item": [
        {
          "id": "dd388879-274c-4c13-b82c-9a863f568085",
          "name": "createRepository",
          "request": {
            "url": "http://example.com/api/?Action=CreateRepository?repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an image repository."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "593a9e0a-9928-4b61-8768-171f65a174dd"
            }
          ]
        },
        {
          "id": "e745e6dd-2c0d-4b71-99a4-ab9c00734220",
          "name": "deleteRepository",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRepository?force=force&registryId=registryId&repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an existing image repository."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "798a956a-78a0-4b4a-942a-1439dc8edddd"
            }
          ]
        },
        {
          "id": "3a0615fe-9a81-4cce-bd8d-24d14b0513ba",
          "name": "describeRepositories",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRepositories?maxResults=maxResults&nextToken=nextToken&registryId=registryId&repositoryNames=repositoryNames",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes image repositories in a registry."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c72356ee-620f-42b6-9498-575b0b833c9a"
            }
          ]
        }
      ]
    },
    {
      "name": "Repository Policies",
      "item": [
        {
          "id": "a6c06d56-d0bd-4a4b-ad7a-203646049d31",
          "name": "deleteRepositoryPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRepositoryPolicy?registryId=registryId&repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the repository policy from a specified repository."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35738a75-313b-4f6f-ba6c-b09acee769c0"
            }
          ]
        },
        {
          "id": "fae83f01-a812-4006-acae-536d732ae233",
          "name": "getRepositoryPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetRepositoryPolicy?registryId=registryId&repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the repository policy for a specified repository."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "891227a3-ac18-40e4-85e5-c353e97423a6"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "80dd95f2-a75b-4330-80d5-7075ce145851",
          "name": "describeImages",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImages?filter=filter&imageIds=imageIds&maxResults=maxResults&nextToken=nextToken&registryId=registryId&repositoryName=repositoryName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns metadata about the images in a repository, including image size, image\n            tags, and creation date."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b66775b2-bdcd-437b-b6ff-7cc55fab0b65"
            }
          ]
        }
      ]
    },
    {
      "name": "Authorization Tokens",
      "item": [
        {
          "id": "a91d74b5-7b28-4add-8c87-e9e32813a67f",
          "name": "getAuthorizationToken",
          "request": {
            "url": "http://example.com/api/?Action=GetAuthorizationToken?registryIds=registryIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a token that is valid for a specified registry for 12 hours."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b738c23-d626-4d18-8b4e-c35c620d6b4d"
            }
          ]
        }
      ]
    },
    {
      "name": "Layers",
      "item": [
        {
          "id": "9f96ec8b-1fb7-4160-8211-20181f6ecd70",
          "name": "getDownloadUrlForLayer",
          "request": {
            "url": "http://example.com/api/?Action=GetDownloadUrlForLayer",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": ".Retrieves the pre-signed Amazon S3 download URL corresponding to an image layer. You can only get URLs for image layers that are referenced in an image."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e8c4eb2-b2cd-413e-afea-49659c76682c"
            }
          ]
        }
      ]
    }
  ]
}