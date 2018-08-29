{
  "info": {
    "name": "Azure API Management API IdentityProviders Delete",
    "_postman_id": "426fd233-4b43-4607-a4ee-a4bb6e699e7b",
    "description": "Deletes the specified identity provider configuration.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "identity providers",
      "item": [
        {
          "id": "1b40b374-ad1b-4247-a5f7-09688aed160c",
          "name": "IdentityProviders_Delete",
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
            "method": "DELETE",
            "header": [
              {
                "key": "If-Match",
                "value": "{}",
                "description": "The entity state (Etag) version of the backend to delete",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified identity provider configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13d951a8-a2f3-43f0-807c-a28b35ac382b"
            }
          ]
        }
      ]
    }
  ]
}