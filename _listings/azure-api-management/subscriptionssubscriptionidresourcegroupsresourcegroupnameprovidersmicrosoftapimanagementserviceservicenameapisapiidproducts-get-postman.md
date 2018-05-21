{
  "info": {
    "name": "Azure API Management API ApiProducts ListByApis",
    "_postman_id": "ad65f3f6-df6a-480d-82ed-6398af935074",
    "description": "Lists all API associated products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "api products",
      "item": [
        {
          "id": "4e973b00-3722-4b37-94a9-8aad2712a47d",
          "name": "ApiProducts_ListByApis",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/apis/:apiId/products"
              ],
              "query": [
                {
                  "key": "$filter",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "serviceName",
                  "value": "serviceName",
                  "type": "string"
                },
                {
                  "id": "apiId",
                  "value": "apiId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all API associated products"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6aa6e4b8-3500-4483-9596-23d09f66ada2"
            }
          ]
        }
      ]
    }
  ]
}