{
  "info": {
    "name": "AWS EC2 Container Registry API Get Download Url For Layer",
    "_postman_id": "0eb86c0d-0265-4aa9-8b85-f654016e6b35",
    "description": ".Retrieves the pre-signed Amazon S3 download URL corresponding to an image layer. You can only get URLs for image layers that are referenced in an image.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Layer Availability",
      "item": [
        {
          "id": "b26ab628-fea9-4311-a545-9341b2fad718",
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
              "id": "118130f1-a093-4ad1-88a6-3e29afca80e0"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "5b77e3e6-001d-4305-9e1d-09541e7a1d46",
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
              "id": "457c44e6-c227-4ead-9b1c-17fe5edb9976"
            }
          ]
        },
        {
          "id": "da6bec08-25b0-487c-a627-20bdf011ab5f",
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
              "id": "925d4302-fb83-46e3-b3de-91400236cc02"
            }
          ]
        }
      ]
    },
    {
      "name": "Layer Upload",
      "item": [
        {
          "id": "211fd82e-21da-441d-9417-01cd856ca092",
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
              "id": "eba91cdb-1aeb-40a2-abce-0b9111dbe488"
            }
          ]
        }
      ]
    },
    {
      "name": "Repositories",
      "item": [
        {
          "id": "5885a6bd-6c5c-4a15-8e4d-eea4612efca8",
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
              "id": "135ad766-46dd-4d7f-bc9f-9b107d344cbc"
            }
          ]
        },
        {
          "id": "fc955f8d-dd7a-4cd7-bcc9-066f1974f3d7",
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
              "id": "656e231a-9aea-47dc-844d-432ce7c19720"
            }
          ]
        },
        {
          "id": "44a7464b-a96b-4897-8252-3dbdd9963be3",
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
              "id": "42896665-1372-47bf-903c-700b8685e423"
            }
          ]
        }
      ]
    },
    {
      "name": "Repository Policies",
      "item": [
        {
          "id": "18ed63ef-f858-47dd-881c-1be3fbca78f5",
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
              "id": "8e599fc5-592a-4a99-b840-8401cc1da844"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "529e1780-bce3-4527-953f-0903e95d86cd",
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
              "id": "32e51e71-bd0e-4de9-9f1a-bbc5e0f1b2bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Authorization Tokens",
      "item": [
        {
          "id": "1b16b4f0-49a1-4395-aa24-4c6913a22c2e",
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
              "id": "739b679e-bbd8-4572-adae-49af9d051af2"
            }
          ]
        }
      ]
    },
    {
      "name": "Layers",
      "item": [
        {
          "id": "d2f74022-6cbe-4bca-84cf-739969ce77e8",
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
              "id": "73b29c4d-9270-4df3-bccc-55bc12484d60"
            }
          ]
        }
      ]
    }
  ]
}