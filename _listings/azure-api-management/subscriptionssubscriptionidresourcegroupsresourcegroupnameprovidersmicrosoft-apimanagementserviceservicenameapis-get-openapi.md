---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 0
info:
  title: Azure API Management API Apis ListByService
  description: Lists all APIs of the API Management service instance.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/policySnippets
  : get:
      summary: PolicySnippets ListByService
      description: Lists all policy snippets.
      operationId: PolicySnippets_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepolicysnippets-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: scope
        description: Policy scope
      responses:
        200:
          description: OK
      tags:
      - Policy Snippets
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/regions
  : get:
      summary: Regions ListByService
      description: Lists all azure regions in which the service exists.
      operationId: Regions_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameregions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Regions
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis:
    get:
      summary: Apis ListByService
      description: Lists all APIs of the API Management service instance.
      operationId: Apis_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapis-get
      parameters:
      - in: query
        name: $filter
        description: '| Field       | Supported operators    | Supported functions               ||-------------|------------------------|-----------------------------------||
          id          | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          || name        | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          || description | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          || serviceUrl  | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          || path        | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - APIs
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---