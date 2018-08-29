{
  "info": {
    "name": "Azure API Management API IdentityProviders Get",
    "_postman_id": "0ec0269e-cdb3-41c9-9374-8ce89257aa22",
    "description": "Gets the configuration details of the identity Provider configured in specified service instance.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "identity providers",
      "item": [
        {
          "id": "d2cfb89d-f060-4396-b967-cd20cda49671",
          "name": "IdentityProviders_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/identityProviders/:identityProviderName"
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
                  "id": "identityProviderName",
                  "value": "identityProviderName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the configuration details of the identity Provider configured in specified service instance"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "751ed59c-17fd-4035-b1d8-ca6ab6d09fe9"
            }
          ]
        }
      ]
    }
  ]
}