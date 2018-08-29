{
  "info": {
    "name": "Azure API Management API ApiOperations Get",
    "_postman_id": "37e35460-5f78-41c2-b4d8-9fc28a5ab8b8",
    "description": "Gets the details of the API Operation specified by its identifier.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "api operations",
      "item": [
        {
          "id": "2db8ad13-e923-4663-8144-5648caa9e6c3",
          "name": "ApiOperations_Get",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the details of the API Operation specified by its identifier"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f908fe67-52b5-4b32-acdb-74854999b2f4"
            }
          ]
        }
      ]
    }
  ]
}