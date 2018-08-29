{
  "info": {
    "name": "Azure API Management API ApiOperations Delete",
    "_postman_id": "f70bbc99-60f4-45cf-959d-c3065259e600",
    "description": "Deletes the specified operation.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "api operations",
      "item": [
        {
          "id": "25145f17-cfc0-45d7-a91c-b51609e9c5d0",
          "name": "ApiOperations_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/apis/:apiId/operations/:operationId"
              ],
              "query": [
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
                },
                {
                  "id": "operationId",
                  "value": "operationId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "If-Match",
                "value": "{}",
                "description": "ETag of the API Operation Entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a7bf47e-6f54-4bd2-9508-5c643ac23be3"
            }
          ]
        }
      ]
    }
  ]
}