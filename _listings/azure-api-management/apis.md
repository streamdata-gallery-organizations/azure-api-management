---
name: Azure API Management
x-slug: azure-api-management
description: Use Azure API Management as a turnkey solution for publishing APIs to
  external and internal customers. Quickly create consistent and modern API gateways
  for existing back-end services hosted anywhere, secure and protect them from abuse
  and overuse, and get insights into usage and health. Plus, automate and scale developer
  onboarding to help get your API program up and running.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure API Management
created: "2018-05-24"
modified: "2018-05-24"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/apis.md
specificationVersion: "0.14"
apis:
- name: Azure API Management API PolicySnippets ListByService
  x-api-slug: azure-api-management-api
  description: Lists all policy snippets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/policySnippets
  tags: Policy Snippets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepolicysnippets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepolicysnippets-get-openapi.md
- name: Azure API Management API Regions ListByService
  x-api-slug: azure-api-management-api
  description: Lists all azure regions in which the service exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/regions
  tags: Regions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameregions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameregions-get-openapi.md
- name: Azure API Management API Apis ListByService
  x-api-slug: azure-api-management-api
  description: Lists all APIs of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapis-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapis-get-openapi.md
- name: Azure API Management API Apis Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the API specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-get-openapi.md
- name: Azure API Management API Apis CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates new or updates existing specified API of the API Management
    service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  tags: APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-put-openapi.md
- name: Azure API Management API Apis Update
  x-api-slug: azure-api-management-api
  description: Updates the specified API of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  tags: APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-patch-openapi.md
- name: Azure API Management API Apis Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified API of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  tags: APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-delete-openapi.md
- name: Azure API Management API ApiOperations ListByApis
  x-api-slug: azure-api-management-api
  description: Lists a collection of the operations for the specified API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperations-get-openapi.md
- name: Azure API Management API ApiOperations Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the API Operation specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-get-openapi.md
- name: Azure API Management API ApiOperations CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates a new API operation or updates an existing one.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  tags: API Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-put-openapi.md
- name: Azure API Management API ApiOperations Update
  x-api-slug: azure-api-management-api
  description: Updates the details of the operation specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  tags: API Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-patch-openapi.md
- name: Azure API Management API ApiOperations Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-delete-openapi.md
- name: Azure API Management API ApiOperationsPolicy Get
  x-api-slug: azure-api-management-api
  description: Get the policy configuration at the API Operation level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}/policy
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationidpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationidpolicy-get-openapi.md
- name: Azure API Management API ApiOperationsPolicy CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates policy configuration for the API Operation level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}/policy
  tags: API Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationidpolicy-put-openapi.md
- name: Azure API Management API ApiOperationsPolicy Delete
  x-api-slug: azure-api-management-api
  description: Deletes the policy configuration at the Api Operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}/policy
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationidpolicy-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationidpolicy-delete-openapi.md
- name: Azure API Management API ApiProducts ListByApis
  x-api-slug: azure-api-management-api
  description: Lists all API associated products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/products
  tags: API Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidproducts-get-openapi.md
- name: Azure API Management API ApiPolicy Get
  x-api-slug: azure-api-management-api
  description: Get the policy configuration at the API level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/policy
  tags: API Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidpolicy-get-openapi.md
- name: Azure API Management API ApiPolicy CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates policy configuration for the API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/policy
  tags: API Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidpolicy-put-openapi.md
- name: Azure API Management API ApiPolicy Delete
  x-api-slug: azure-api-management-api
  description: Deletes the policy configuration at the Api.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/policy
  tags: API Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidpolicy-delete-openapi.md
- name: Azure API Management API AuthorizationServers ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of authorization servers defined within a service
    instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers
  tags: Authorization Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationservers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationservers-get-openapi.md
- name: Azure API Management API AuthorizationServers Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the authorization server specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers/{authsid}
  tags: Authorization Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-get-openapi.md
- name: Azure API Management API AuthorizationServers CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates new authorization server or updates an existing authorization
    server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers/{authsid}
  tags: Authorization Servers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-put-openapi.md
- name: Azure API Management API AuthorizationServers Update
  x-api-slug: azure-api-management-api
  description: Updates the details of the authorization server specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers/{authsid}
  tags: Authorization Servers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-patch-openapi.md
- name: Azure API Management API AuthorizationServers Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific authorization server instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers/{authsid}
  tags: Authorization Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-delete-openapi.md
- name: Azure API Management API Backends ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of backends in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackends-get-openapi.md
- name: Azure API Management API Backends Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the backend specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackendsbackendid-get-openapi.md
- name: Azure API Management API Backends CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackendsbackendid-put-openapi.md
- name: Azure API Management API Backends Update
  x-api-slug: azure-api-management-api
  description: Updates an existing backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackendsbackendid-patch-openapi.md
- name: Azure API Management API Backends Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackendsbackendid-delete-openapi.md
- name: Azure API Management API Certificates ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of all certificates in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates
  tags: Certificates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificates-get-openapi.md
- name: Azure API Management API Certificates Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the certificate specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates/{certificateId}
  tags: Certificates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificatescertificateid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificatescertificateid-get-openapi.md
- name: Azure API Management API Certificates CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates the certificate being used for authentication with
    the backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates/{certificateId}
  tags: Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificatescertificateid-put-openapi.md
- name: Azure API Management API Certificates Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates/{certificateId}
  tags: Certificates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificatescertificateid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificatescertificateid-delete-openapi.md
- name: Azure API Management API API Management Operations List
  x-api-slug: azure-api-management-api
  description: Lists all of the available REST API operations of the Microsoft.ApiManagement
    provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////providers/Microsoft.ApiManagement/operations
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/providersmicrosoft-apimanagementoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/providersmicrosoft-apimanagementoperations-get-openapi.md
- name: Azure API Management API ApiManagementServices ManageDeployments
  x-api-slug: azure-api-management-api
  description: 'Manages deployments of an API Management service. This operation can
    be used to do the following: Change SKU, Change SKU Units, Change Service Tier
    (Developer/Standard/Premium) and Manage VPN Configuration. This is a long running
    operation and can take several minutes to complete.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/managedeployments
  tags: API Management Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamemanagedeployments-post-openapi.md
- name: Azure API Management API ApiManagementServices Restore
  x-api-slug: azure-api-management-api
  description: Restores a backup of an API Management service created using the ApiManagementServices_Backup
    operation on the current service. This is a long running operation and could take
    several minutes to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/restore
  tags: API Management Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamerestore-post-openapi.md
- name: Azure API Management API ApiManagementServices Backup
  x-api-slug: azure-api-management-api
  description: Creates a backup of the API Management service to the given Azure Storage
    Account. This is long running operation and could take several minutes to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backup
  tags: API Management Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackup-post-openapi.md
- name: Azure API Management API ApiManagementServices CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates an API Management service. This is long running
    operation and could take several minutes to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicename-put-openapi.md
- name: Azure API Management API ApiManagementServices Update
  x-api-slug: azure-api-management-api
  description: Updates an existing API Management service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicename-patch-openapi.md
- name: Azure API Management API ApiManagementServices Get
  x-api-slug: azure-api-management-api
  description: Gets an API Management service resource description.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicename-get-openapi.md
- name: Azure API Management API ApiManagementServices Delete
  x-api-slug: azure-api-management-api
  description: Deletes an existing API Management service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicename-delete-openapi.md
- name: Azure API Management API API Management Services ListByResourceGroup
  x-api-slug: azure-api-management-api
  description: List all API Management services within a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementservice-get-openapi.md
- name: Azure API Management API API Management Services List
  x-api-slug: azure-api-management-api
  description: Lists all API Management services within an Azure subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ApiManagement/service/
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidprovidersmicrosoft-apimanagementservice-get-openapi.md
- name: Azure API Management API ApiManagementServices GetSsoToken
  x-api-slug: azure-api-management-api
  description: Gets the Single-Sign-On token for the API Management Service which
    is valid for 5 Minutes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/getssotoken
  tags: API Management Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegetssotoken-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegetssotoken-post-openapi.md
- name: Azure API Management API API Management Services Check Name Availability
  x-api-slug: azure-api-management-api
  description: Checks availability and correctness of a name for an API Management
    service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ApiManagement/checkNameAvailability
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidprovidersmicrosoft-apimanagementchecknameavailability-post-openapi.md
- name: Azure API Management API ApiManagementServices UploadCertificate
  x-api-slug: azure-api-management-api
  description: Upload Custom Domain SSL certificate for an API Management service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/uploadcertificate
  tags: API Management Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameuploadcertificate-post-openapi.md
- name: Azure API Management API ApiManagementServices UpdateHostname
  x-api-slug: azure-api-management-api
  description: Creates, updates, or deletes the custom hostnames for an API Management
    service. The custom hostname can be applied to the Proxy and Portal endpoint.
    This is a long running operation and could take several minutes to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/updatehostname
  tags: API Management Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameupdatehostname-post-openapi.md
- name: Azure API Management API ApiManagementServices ApplyNetworkConfigurationUpdates
  x-api-slug: azure-api-management-api
  description: Updates the Microsoft.ApiManagement resource running in the Virtual
    network to pick the updated network settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/applynetworkconfigurationupdates
  tags: API Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapplynetworkconfigurationupdates-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapplynetworkconfigurationupdates-post-openapi.md
- name: Azure API Management API Groups ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of groups defined within a service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroups-get-openapi.md
- name: Azure API Management API Groups Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the group specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-get-openapi.md
- name: Azure API Management API Groups CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-put-openapi.md
- name: Azure API Management API Groups Update
  x-api-slug: azure-api-management-api
  description: Updates the details of the group specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-patch-openapi.md
- name: Azure API Management API Groups Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific group of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-delete-openapi.md
- name: Azure API Management API GroupUsers ListByGroups
  x-api-slug: azure-api-management-api
  description: Lists a collection of the members of the group, specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}/users
  tags: Group Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusers-get-openapi.md
- name: Azure API Management API GroupUsers Create
  x-api-slug: azure-api-management-api
  description: Adds a user to the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}/users/{uid}
  tags: Group Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusersuid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusersuid-put-openapi.md
- name: Azure API Management API GroupUsers Delete
  x-api-slug: azure-api-management-api
  description: Remove existing user from existing group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}/users/{uid}
  tags: Group Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusersuid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusersuid-delete-openapi.md
- name: Azure API Management API IdentityProviders ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of Identity Provider configured in the specified
    service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders
  tags: Identity Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityproviders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityproviders-get-openapi.md
- name: Azure API Management API IdentityProviders Get
  x-api-slug: azure-api-management-api
  description: Gets the configuration details of the identity Provider configured
    in specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  tags: Identity Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-get-openapi.md
- name: Azure API Management API IdentityProviders CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates the IdentityProvider configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  tags: Identity Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-put-openapi.md
- name: Azure API Management API IdentityProviders Update
  x-api-slug: azure-api-management-api
  description: Updates an existing IdentityProvider configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  tags: Identity Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-patch-openapi.md
- name: Azure API Management API IdentityProviders Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified identity provider configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  tags: Identity Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-delete-openapi.md
- name: Azure API Management API Loggers ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of loggers in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggers-get-openapi.md
- name: Azure API Management API Loggers Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the logger specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-get-openapi.md
- name: Azure API Management API Loggers CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a logger.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-put-openapi.md
- name: Azure API Management API Loggers Update
  x-api-slug: azure-api-management-api
  description: Updates an existing logger.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-patch-openapi.md
- name: Azure API Management API Loggers Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified logger.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-delete-openapi.md
- name: Azure API Management API NetworkStatus GetByService
  x-api-slug: azure-api-management-api
  description: Gets the Connectivity Status to the external resources on which the
    Api Management service depends from inside the Cloud Service. This also returns
    the DNS Servers as visible to the CloudService.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/networkstatus
  tags: Network Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamenetworkstatus-get-openapi.md
- name: Azure API Management API OpenIdConnectProviders ListByService
  x-api-slug: azure-api-management-api
  description: Lists all OpenID Connect Providers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders
  tags: OpenId Connect Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectproviders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectproviders-get-openapi.md
- name: Azure API Management API OpenIdConnectProviders Get
  x-api-slug: azure-api-management-api
  description: Gets specific OpenID Connect Provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders/{opid}
  tags: OpenId Connect Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-get-openapi.md
- name: Azure API Management API OpenIdConnectProviders CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates the OpenID Connect Provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders/{opid}
  tags: OpenId Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-put-openapi.md
- name: Azure API Management API OpenIdConnectProviders Update
  x-api-slug: azure-api-management-api
  description: Updates the specific OpenID Connect Provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders/{opid}
  tags: OpenId Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-patch-openapi.md
- name: Azure API Management API OpenIdConnectProviders Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific OpenID Connect Provider of the API Management service
    instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders/{opid}
  tags: OpenId Connect Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-delete-openapi.md
- name: Azure API Management API Products ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of products in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproducts-get-openapi.md
- name: Azure API Management API Products Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the product specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-get-openapi.md
- name: Azure API Management API Products CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-put-openapi.md
- name: Azure API Management API Products Update
  x-api-slug: azure-api-management-api
  description: Update product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-patch-openapi.md
- name: Azure API Management API Products Delete
  x-api-slug: azure-api-management-api
  description: Delete product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-delete-openapi.md
- name: Azure API Management API ProductApis ListByProducts
  x-api-slug: azure-api-management-api
  description: Lists a collection of the APIs associated with a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/apis
  tags: Product APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidapis-get-openapi.md
- name: Azure API Management API ProductApis Create
  x-api-slug: azure-api-management-api
  description: Adds an API to the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/apis/{apiId}
  tags: Product APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidapisapiid-put-openapi.md
- name: Azure API Management API ProductApis Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified API from the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/apis/{apiId}
  tags: Product APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidapisapiid-delete-openapi.md
- name: Azure API Management API ProductGroups ListByProducts
  x-api-slug: azure-api-management-api
  description: Lists the collection of developer groups associated with the specified
    product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/groups
  tags: Product Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidgroups-get-openapi.md
- name: Azure API Management API ProductGroups Create
  x-api-slug: azure-api-management-api
  description: Adds the association between the specified developer group with the
    specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/groups/{groupId}
  tags: Product Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidgroupsgroupid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidgroupsgroupid-put-openapi.md
- name: Azure API Management API ProductGroups Delete
  x-api-slug: azure-api-management-api
  description: Deletes the association between the specified group and product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/groups/{groupId}
  tags: Product Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidgroupsgroupid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidgroupsgroupid-delete-openapi.md
- name: Azure API Management API ProductSubscriptions ListByProducts
  x-api-slug: azure-api-management-api
  description: Lists the collection of subscriptions to the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/subscriptions
  tags: Product Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidsubscriptions-get-openapi.md
- name: Azure API Management API ProductPolicy Get
  x-api-slug: azure-api-management-api
  description: Get the policy configuration at the Product level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/policy
  tags: Product Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidpolicy-get-openapi.md
- name: Azure API Management API ProductPolicy CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates policy configuration for the Product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/policy
  tags: Product Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidpolicy-put-openapi.md
- name: Azure API Management API ProductPolicy Delete
  x-api-slug: azure-api-management-api
  description: Deletes the policy configuration at the Product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/policy
  tags: Product Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidpolicy-delete-openapi.md
- name: Azure API Management API Properties ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of properties defined within a service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties
  tags: Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproperties-get-openapi.md
- name: Azure API Management API Property Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the property specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  tags: Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepropertiespropid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepropertiespropid-get-openapi.md
- name: Azure API Management API Property CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates a property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  tags: Properties
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepropertiespropid-put-openapi.md
- name: Azure API Management API Property Update
  x-api-slug: azure-api-management-api
  description: Updates the specific property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  tags: Properties
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepropertiespropid-patch-openapi.md
- name: Azure API Management API Property Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific property from the the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  tags: Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepropertiespropid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamepropertiespropid-delete-openapi.md
- name: Azure API Management API QuotaByCounterKeys ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of current quota counter periods associated with
    the counter-key configured in the policy on the specified service instance. The
    api does not support paging yet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/quotas/{quotaCounterKey}
  tags: Quotas
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamequotasquotacounterkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamequotasquotacounterkey-get-openapi.md
- name: Azure API Management API QuotaByCounterKeys Update
  x-api-slug: azure-api-management-api
  description: Updates all the quota counter values specified with the existing quota
    counter key to a value in the specified service instance. This should be used
    for reset of the quota counter values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/quotas/{quotaCounterKey}
  tags: Quotas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamequotasquotacounterkey-patch-openapi.md
- name: Azure API Management API QuotaByPeriodKeys Get
  x-api-slug: azure-api-management-api
  description: Gets the value of the quota counter associated with the counter-key
    in the policy for the specific period in service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/quotas/{quotaCounterKey}/{quotaPeriodKey}
  tags: Quotas
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamequotasquotacounterkeyquotaperiodkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamequotasquotacounterkeyquotaperiodkey-get-openapi.md
- name: Azure API Management API QuotaByPeriodKeys Update
  x-api-slug: azure-api-management-api
  description: Updates an existing quota counter value in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/quotas/{quotaCounterKey}/{quotaPeriodKey}
  tags: Quotas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamequotasquotacounterkeyquotaperiodkey-patch-openapi.md
- name: Azure API Management API Reports ListByService
  x-api-slug: azure-api-management-api
  description: Lists report records.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/reports/{aggregation}
  tags: Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamereportsaggregation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamereportsaggregation-get-openapi.md
- name: Azure API Management API Subscriptions List
  x-api-slug: azure-api-management-api
  description: Lists all subscriptions of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamesubscriptions-get-openapi.md
- name: Azure API Management API Subscriptions Get
  x-api-slug: azure-api-management-api
  description: Gets the specified Subscription entity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamesubscriptionssid-get-openapi.md
- name: Azure API Management API Subscriptions CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates the subscription of specified user to the specified
    product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamesubscriptionssid-put-openapi.md
- name: Azure API Management API Subscriptions Update
  x-api-slug: azure-api-management-api
  description: Updates the details of a subscription specificied by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamesubscriptionssid-patch-openapi.md
- name: Azure API Management API Subscriptions Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamesubscriptionssid-delete-openapi.md
- name: Azure API Management API Subscriptions RegeneratePrimaryKey
  x-api-slug: azure-api-management-api
  description: Regenerates primary key of existing subscription of the API Management
    service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}/regeneratePrimaryKey
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamesubscriptionssidregenerateprimarykey-post-openapi.md
- name: Azure API Management API Subscriptions RegenerateSecondaryKey
  x-api-slug: azure-api-management-api
  description: Regenerates secondary key of existing subscription of the API Management
    service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}/regenerateSecondaryKey
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamesubscriptionssidregeneratesecondarykey-post-openapi.md
- name: Azure API Management API TenantAccess Get
  x-api-slug: azure-api-management-api
  description: Get tenant access information details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccess-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccess-get-openapi.md
- name: Azure API Management API TenantAccess Update
  x-api-slug: azure-api-management-api
  description: Update tenant access information details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access
  tags: Tenants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccess-patch-openapi.md
- name: Azure API Management API TenantAccess RegeneratePrimaryKey
  x-api-slug: azure-api-management-api
  description: Regenerate primary access key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/regeneratePrimaryKey
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessregenerateprimarykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessregenerateprimarykey-post-openapi.md
- name: Azure API Management API TenantAccess RegenerateSecondaryKey
  x-api-slug: azure-api-management-api
  description: Regenerate secondary access key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/regenerateSecondaryKey
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessregeneratesecondarykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessregeneratesecondarykey-post-openapi.md
- name: Azure API Management API TenantAccessGit Get
  x-api-slug: azure-api-management-api
  description: Gets the Git access configuration for the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessgit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessgit-get-openapi.md
- name: Azure API Management API TenantAccessGit RegeneratePrimaryKey
  x-api-slug: azure-api-management-api
  description: Regenerate primary access key for GIT.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git/regeneratePrimaryKey
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessgitregenerateprimarykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessgitregenerateprimarykey-post-openapi.md
- name: Azure API Management API TenantAccessGit RegenerateSecondaryKey
  x-api-slug: azure-api-management-api
  description: Regenerate secondary access key for GIT.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git/regenerateSecondaryKey
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessgitregeneratesecondarykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantaccessgitregeneratesecondarykey-post-openapi.md
- name: Azure API Management API TenantConfiguration Deploy
  x-api-slug: azure-api-management-api
  description: This operation applies changes from the specified Git branch to the
    configuration database. This is a long running operation and could take several
    minutes to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/configuration/deploy
  tags: Tenants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantconfigurationdeploy-post-openapi.md
- name: Azure API Management API TenantConfiguration Save
  x-api-slug: azure-api-management-api
  description: This operation creates a commit with the current configuration snapshot
    to the specified branch in the repository. This is a long running operation and
    could take several minutes to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/configuration/save
  tags: Tenants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantconfigurationsave-post-openapi.md
- name: Azure API Management API TenantConfiguration Validate
  x-api-slug: azure-api-management-api
  description: This operation validates the changes in the specified Git branch. This
    is a long running operation and could take several minutes to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/configuration/validate
  tags: Tenants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantconfigurationvalidate-post-openapi.md
- name: Azure API Management API TenantConfigurationSyncState Get
  x-api-slug: azure-api-management-api
  description: Gets the status of the most recent synchronization between the configuration
    database and the Git repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/configuration/syncState
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantconfigurationsyncstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantconfigurationsyncstate-get-openapi.md
- name: Azure API Management API TenantPolicy Get
  x-api-slug: azure-api-management-api
  description: Get the global policy configuration of the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/policy
  tags: Tenant Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantpolicy-get-openapi.md
- name: Azure API Management API TenantPolicy CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates global policy configuration for the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/policy
  tags: Tenant Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantpolicy-put-openapi.md
- name: Azure API Management API TenantPolicy Delete
  x-api-slug: azure-api-management-api
  description: Deletes the global tenant policy configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/policy
  tags: Tenant Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenametenantpolicy-delete-openapi.md
- name: Azure API Management API Users ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of registered users in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusers-get-openapi.md
- name: Azure API Management API Users Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the user specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuid-get-openapi.md
- name: Azure API Management API Users CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuid-put-openapi.md
- name: Azure API Management API Users Update
  x-api-slug: azure-api-management-api
  description: Updates the details of the user specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuid-patch-openapi.md
- name: Azure API Management API Users Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuid-delete-openapi.md
- name: Azure API Management API Users GenerateSsoUrl
  x-api-slug: azure-api-management-api
  description: Retrieves a redirection URL containing an authentication token for
    signing a given user into the developer portal.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}/generateSsoUrl
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuidgeneratessourl-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuidgeneratessourl-post-openapi.md
- name: Azure API Management API UserGroups ListByUsers
  x-api-slug: azure-api-management-api
  description: Lists all user groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}/groups
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuidgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuidgroups-get-openapi.md
- name: Azure API Management API UserSubscriptions ListByUsers
  x-api-slug: azure-api-management-api
  description: Lists the collection of subscriptions of the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}/subscriptions
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuidsubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuidsubscriptions-get-openapi.md
- name: Azure API Management API UserIdentities ListByUsers
  x-api-slug: azure-api-management-api
  description: Lists all user identities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}/identities
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuididentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameusersuididentities-get-openapi.md
- name: Azure API Management API
  x-api-slug: azure-api-management-api
  description: Use Azure API Management as a turnkey solution for publishing APIs
    to external and internal customers. Quickly create consistent and modern API gateways
    for existing back-end services hosted anywhere, secure and protect them from abuse
    and overuse, and get insights into usage and health. Plus, automate and scale
    developer onboarding to help get your API program up and running.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com//
  tags: Azure API Management
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/api-management/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/api-management/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/api-management/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/api-management/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---