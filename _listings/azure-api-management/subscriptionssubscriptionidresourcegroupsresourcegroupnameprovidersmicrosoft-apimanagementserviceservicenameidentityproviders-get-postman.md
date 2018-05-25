{
  "info": {
    "name": "Azure API Management API IdentityProviders ListByService",
    "_postman_id": "c7fc96ec-5709-43ae-b721-1326486edeb1",
    "description": "Lists a collection of Identity Provider configured in the specified service instance.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "identity providers",
      "item": [
        {
          "id": "47182478-e81a-4f9d-adde-0d5724f9c292",
          "name": "IdentityProviders_ListByService",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/identityProviders"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists a collection of Identity Provider configured in the specified service instance"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa2859b0-119d-408e-8fe0-21b8f8b32c32"
            }
          ]
        }
      ]
    }
  ]
}