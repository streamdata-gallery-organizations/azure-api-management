{
  "info": {
    "name": "Azure API Management API Products Delete",
    "_postman_id": "0ba2f22c-1c6d-4727-bf6a-859781d16297",
    "description": "Delete product.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "products",
      "item": [
        {
          "id": "facf4c54-8e88-4a10-a851-e5f3a2dbe844",
          "name": "Products_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/products/:productId"
              ],
              "query": [
                {
                  "key": "deleteSubscriptions",
                  "value": "%7B%7D",
                  "disabled": false
                },
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
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "If-Match",
                "value": "{}",
                "description": "ETag of the Product Entity",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Delete product"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b14b50b-b0d9-40e6-950c-d1ae25a59d3c"
            }
          ]
        }
      ]
    }
  ]
}