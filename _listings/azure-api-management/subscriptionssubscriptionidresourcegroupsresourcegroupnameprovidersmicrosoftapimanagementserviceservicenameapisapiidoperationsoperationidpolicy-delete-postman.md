{
  "info": {
    "name": "Azure API Management API ApiOperationsPolicy Delete",
    "_postman_id": "d4ab381c-1138-44f7-94b9-ef5fd57757b9",
    "description": "Deletes the policy configuration at the Api Operation.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "api operations",
      "item": [
        {
          "id": "8b23b24e-75be-48c7-8eda-0371da658e3a",
          "name": "ApiOperationsPolicy_Delete",
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
            "method": "DELETE",
            "header": [
              {
                "key": "If-Match",
                "value": "{}",
                "description": "The entity state (Etag) version of the Api operation policy to update",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the policy configuration at the Api Operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1bbf252d-d1de-4882-b528-f168248e0d33"
            }
          ]
        }
      ]
    }
  ]
}