{
  "info": {
    "name": "API Evangelist Building Block API Get Images for Building Block",
    "_postman_id": "162c718f-a537-4141-a678-fd4fb4d32889",
    "description": "get building block images",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building",
      "item": [
        {
          "id": "7e2cdbee-33b8-4a67-8635-911e662cc70e",
          "name": "getBuildingBlocks",
          "request": {
            "url": "http://buildingblock.api.kinlane.com/buildingblocks/?appid=%7B%7D&appkey=%7B%7D&count=%7B%7D&page=%7B%7D&query=%7B%7D&sort=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "all building blocks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a785b030-49b3-4cdf-9f0f-f5aab48dabe4"
            }
          ]
        },
        {
          "id": "2a9393da-1980-43fc-b4bd-54637184c97b",
          "name": "addBuildingBlock",
          "request": {
            "url": "http://buildingblock.api.kinlane.com/buildingblocks/?about=%7B%7D&appid=%7B%7D&appkey=%7B%7D&building_block_category_id=%7B%7D&name=%7B%7D&sort_order=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "add a building block post"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a4a3a19-fb76-45bb-83b3-722b9fb6f94d"
            }
          ]
        },
        {
          "id": "976066dc-33ed-4755-9738-3b87997d7a29",
          "name": "getBuildingBlocksByCategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "buildingblock.api.kinlane.com",
              "path": [
                "buildingblocks/bycategory/:category"
              ],
              "query": [
                {
                  "key": "appid",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "appkey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "building blocks by category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "954acc68-16b1-4fe4-96e4-36fa790d8878"
            }
          ]
        },
        {
          "id": "38549c5b-d652-4642-81aa-37c3edacc203",
          "name": "getBuildingBlocksByType",
          "request": {
            "url": {
              "protocol": "http",
              "host": "buildingblock.api.kinlane.com",
              "path": [
                "buildingblocks/bytype/:type"
              ],
              "query": [
                {
                  "key": "appid",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "appkey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "type",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "building blocks by type"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1de951e8-05cd-4d39-b80e-cf397ced9510"
            }
          ]
        },
        {
          "id": "f27dab72-9ac2-4a92-b479-bfbb1c83804b",
          "name": "getBuildingBlock",
          "request": {
            "url": {
              "protocol": "http",
              "host": "buildingblock.api.kinlane.com",
              "path": [
                "buildingblocks/:building_block_id/"
              ],
              "query": [
                {
                  "key": "appid",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "appkey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "building_block_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the building block detail"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9d0219b-9191-4d29-85e2-c0628c6bdab4"
            }
          ]
        },
        {
          "id": "96db6b56-1259-4329-ba0d-ea827fb710b6",
          "name": "updateBuildingBlock",
          "request": {
            "url": {
              "protocol": "http",
              "host": "buildingblock.api.kinlane.com",
              "path": [
                "buildingblocks/:building_block_id/"
              ],
              "query": [
                {
                  "key": "about",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "appid",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "appkey",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "building_block_category_id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort_order",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "building_block_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "update building block"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cb63ec3-9b11-4163-a6fd-35453225b0a6"
            }
          ]
        },
        {
          "id": "255edf14-a257-4a14-94f5-a0423fefc6ff",
          "name": "deleteBuildingBlock",
          "request": {
            "url": {
              "protocol": "http",
              "host": "buildingblock.api.kinlane.com",
              "path": [
                "buildingblocks/:building_block_id/"
              ],
              "query": [
                {
                  "key": "appid",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "appkey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "building_block_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "delete building block"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8219f910-fcac-4338-a0cc-f8b5759741a0"
            }
          ]
        }
      ]
    },
    {
      "name": "CategoriesBuilding",
      "item": [
        {
          "id": "0ec9db36-d237-451e-b10d-2f0c0b1eb773",
          "name": "getBuildingBlockCategories",
          "request": {
            "url": "http://buildingblock.api.kinlane.com/buildingblocks/categories/?appid=%7B%7D&appkey=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "retrieve building block categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78f2081f-1748-4c54-825e-2da37b020d9c"
            }
          ]
        }
      ]
    },
    {
      "name": "CategoryBuilding",
      "item": [
        {
          "id": "be07c6df-099a-4e50-b448-cfb8de992c8b",
          "name": "addBuildingBlockCategory",
          "request": {
            "url": "http://buildingblock.api.kinlane.com/buildingblocks/categories/",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "appid",
                  "value": "{}",
                  "disabled": false,
                  "description": "your appid for accessing the building block"
                },
                {
                  "key": "appkey",
                  "value": "{}",
                  "disabled": false,
                  "description": "your appkey for accessing the building block"
                },
                {
                  "key": "name",
                  "value": "{}",
                  "disabled": false,
                  "description": "a name for the url"
                },
                {
                  "key": "type",
                  "value": "{}",
                  "disabled": false,
                  "description": "type of url"
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": "the url"
                }
              ]
            },
            "description": "add building block category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f81f8e8-e7d9-4517-85a8-e64b0cf7b5d6"
            }
          ]
        },
        {
          "id": "6a76e52b-d5d8-4530-8a43-96a325d2b8a7",
          "name": "deleteBuildingBlockCategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "buildingblock.api.kinlane.com",
              "path": [
                "buildingblocks/categories/:category_id"
              ],
              "query": [
                {
                  "key": "appid",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "appkey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "category_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "delete a building block category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0482082-86e5-4efa-aec6-73bf544e1812"
            }
          ]
        }
      ]
    },
    {
      "name": "ImagesBuilding",
      "item": [
        {
          "id": "6105bd6a-108e-40f1-a714-4fa9e2fc8703",
          "name": "getBuildingBlockImages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "buildingblock.api.kinlane.com",
              "path": [
                "buildingblocks/:building_block_id/images/"
              ],
              "query": [
                {
                  "key": "appid",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "appkey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "building_block_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "get building block images"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60d7da4d-949f-4b84-90e8-5b6df4873490"
            }
          ]
        }
      ]
    }
  ]
}