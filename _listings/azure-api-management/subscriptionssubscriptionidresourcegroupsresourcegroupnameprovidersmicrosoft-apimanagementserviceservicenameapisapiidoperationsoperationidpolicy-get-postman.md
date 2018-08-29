{
  "info": {
    "name": "Azure API Management API ApiOperationsPolicy Get",
    "_postman_id": "6e3ed946-817a-49b4-946f-e2092510cf52",
    "description": "Get the policy configuration at the API Operation level.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "api operations",
      "item": [
        {
          "id": "006c52cd-bd9e-420c-b227-8b897646df14",
          "name": "ApiOperationsPolicy_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/apis/:apiId/operations/:operationId/policy"
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
            "description": "Get the policy configuration at the API Operation level"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "675ea458-778c-4477-b731-fa9711647387"
            }
          ]
        }
      ]
    }
  ]
}