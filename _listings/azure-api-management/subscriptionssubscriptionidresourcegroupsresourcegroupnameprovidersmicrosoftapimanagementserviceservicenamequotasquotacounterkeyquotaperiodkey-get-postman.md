{
  "info": {
    "name": "Azure API Management API QuotaByPeriodKeys Get",
    "_postman_id": "b586f5ce-0d8b-4672-bcf1-5a236953bd4e",
    "description": "Gets the value of the quota counter associated with the counter-key in the policy for the specific period in service instance.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "quotas",
      "item": [
        {
          "id": "d274fca8-9f24-424f-990a-fc92fc01b198",
          "name": "QuotaByPeriodKeys_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/quotas/:quotaCounterKey/:quotaPeriodKey"
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
                },
                {
                  "id": "quotaPeriodKey",
                  "value": "quotaPeriodKey",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the value of the quota counter associated with the counter-key in the policy for the specific period in service instance"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39bcbc9f-3116-4fca-b837-779f0dd83965"
            }
          ]
        }
      ]
    }
  ]
}