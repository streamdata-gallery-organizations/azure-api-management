{
  "info": {
    "name": "Azure API Management API API Management Operations List",
    "_postman_id": "fe4d446a-8c31-46e8-a7a3-2994d670bec2",
    "description": "Lists all of the available REST API operations of the Microsoft.ApiManagement provider.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "api operations",
      "item": [
        {
          "id": "8efa5b41-f31f-40ca-aea6-ae90a6c79a50",
          "name": "ApiManagementOperations_List",
          "request": {
            "url": "http://management.azure.com/providers/Microsoft.ApiManagement/operations?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the available REST API operations of the Microsoft"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0064c6d-0e42-44ff-8bac-170240003cef"
            }
          ]
        }
      ]
    }
  ]
}