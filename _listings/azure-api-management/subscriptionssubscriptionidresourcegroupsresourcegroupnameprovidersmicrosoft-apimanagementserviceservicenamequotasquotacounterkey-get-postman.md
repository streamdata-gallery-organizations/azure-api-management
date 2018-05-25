{
  "info": {
    "name": "Azure API Management API QuotaByCounterKeys ListByService",
    "_postman_id": "d55418e0-0401-4c6b-a78e-560c75b05cb4",
    "description": "Lists a collection of current quota counter periods associated with the counter-key configured in the policy on the specified service instance. The api does not support paging yet.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "quotas",
      "item": [
        {
          "id": "0b887b3c-6cac-4c97-a634-f4a53350f79c",
          "name": "QuotaByCounterKeys_ListByService",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/quotas/:quotaCounterKey"
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
                  "id": "quotaCounterKey",
                  "value": "quotaCounterKey",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists a collection of current quota counter periods associated with the counter-key configured in the policy on the specified service instance"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "391862ee-326b-4fe5-a65d-3c7de530fff0"
            }
          ]
        }
      ]
    }
  ]
}