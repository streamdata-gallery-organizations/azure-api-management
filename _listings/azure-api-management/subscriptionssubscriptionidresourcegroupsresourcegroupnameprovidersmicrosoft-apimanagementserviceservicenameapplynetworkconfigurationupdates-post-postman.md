{
  "info": {
    "name": "Azure API Management API ApiManagementServices ApplyNetworkConfigurationUpdates",
    "_postman_id": "28985c20-5d56-4f09-a04b-39f254575e33",
    "description": "Updates the Microsoft.ApiManagement resource running in the Virtual network to pick the updated network settings.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "api products",
      "item": [
        {
          "id": "7b998c34-1e70-49e5-acb3-483340a29f6a",
          "name": "ApiManagementServices_ApplyNetworkConfigurationUpdates",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/applynetworkconfigurationupdates"
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the Microsoft"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01041e37-b2e9-45de-b45b-75b531646cdc"
            }
          ]
        }
      ]
    }
  ]
}