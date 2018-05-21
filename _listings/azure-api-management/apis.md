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
created: "2018-05-21"
modified: "2018-05-21"
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepolicysnippets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepolicysnippets-get-openapi.md
- name: Azure API Management API Regions ListByService
  x-api-slug: azure-api-management-api
  description: Lists all azure regions in which the service exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/regions
  tags: Regions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameregions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameregions-get-openapi.md
- name: Azure API Management API Apis ListByService
  x-api-slug: azure-api-management-api
  description: Lists all APIs of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapis-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapis-get-openapi.md
- name: Azure API Management API Apis Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the API specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  tags: APIs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-put-openapi.md
- name: Azure API Management API Apis Update
  x-api-slug: azure-api-management-api
  description: Updates the specified API of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  tags: APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-patch-openapi.md
- name: Azure API Management API Apis Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified API of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  tags: APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-delete-openapi.md
- name: Azure API Management API ApiOperations ListByApis
  x-api-slug: azure-api-management-api
  description: Lists a collection of the operations for the specified API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperations-get-openapi.md
- name: Azure API Management API ApiOperations Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the API Operation specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-get-openapi.md
- name: Azure API Management API ApiOperations CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates a new API operation or updates an existing one.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  tags: API Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-put-openapi.md
- name: Azure API Management API ApiOperations Update
  x-api-slug: azure-api-management-api
  description: Updates the details of the operation specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  tags: API Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-patch-openapi.md
- name: Azure API Management API ApiOperations Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-delete-openapi.md
- name: Azure API Management API ApiOperationsPolicy Get
  x-api-slug: azure-api-management-api
  description: Get the policy configuration at the API Operation level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}/policy
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationidpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationidpolicy-get-openapi.md
- name: Azure API Management API ApiOperationsPolicy CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates policy configuration for the API Operation level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}/policy
  tags: API Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationidpolicy-put-openapi.md
- name: Azure API Management API ApiOperationsPolicy Delete
  x-api-slug: azure-api-management-api
  description: Deletes the policy configuration at the Api Operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}/policy
  tags: API Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationidpolicy-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationidpolicy-delete-openapi.md
- name: Azure API Management API ApiProducts ListByApis
  x-api-slug: azure-api-management-api
  description: Lists all API associated products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/products
  tags: API Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidproducts-get-openapi.md
- name: Azure API Management API ApiPolicy Get
  x-api-slug: azure-api-management-api
  description: Get the policy configuration at the API level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/policy
  tags: API Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidpolicy-get-openapi.md
- name: Azure API Management API ApiPolicy CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates policy configuration for the API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/policy
  tags: API Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidpolicy-put-openapi.md
- name: Azure API Management API ApiPolicy Delete
  x-api-slug: azure-api-management-api
  description: Deletes the policy configuration at the Api.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/policy
  tags: API Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidpolicy-delete-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationservers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationservers-get-openapi.md
- name: Azure API Management API AuthorizationServers Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the authorization server specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers/{authsid}
  tags: Authorization Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-put-openapi.md
- name: Azure API Management API AuthorizationServers Update
  x-api-slug: azure-api-management-api
  description: Updates the details of the authorization server specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers/{authsid}
  tags: Authorization Servers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-patch-openapi.md
- name: Azure API Management API AuthorizationServers Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific authorization server instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers/{authsid}
  tags: Authorization Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-delete-openapi.md
- name: Azure API Management API Backends ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of backends in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackends-get-openapi.md
- name: Azure API Management API Backends Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the backend specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackendsbackendid-get-openapi.md
- name: Azure API Management API Backends CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackendsbackendid-put-openapi.md
- name: Azure API Management API Backends Update
  x-api-slug: azure-api-management-api
  description: Updates an existing backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackendsbackendid-patch-openapi.md
- name: Azure API Management API Backends Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  tags: Backends
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackendsbackendid-delete-openapi.md
- name: Azure API Management API Certificates ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of all certificates in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates
  tags: Certificates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificates-get-openapi.md
- name: Azure API Management API Certificates Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the certificate specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates/{certificateId}
  tags: Certificates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificatescertificateid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificatescertificateid-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificatescertificateid-put-openapi.md
- name: Azure API Management API Certificates Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates/{certificateId}
  tags: Certificates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificatescertificateid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificatescertificateid-delete-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/providersmicrosoftapimanagementoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/providersmicrosoftapimanagementoperations-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamemanagedeployments-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamerestore-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackup-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicename-put-openapi.md
- name: Azure API Management API ApiManagementServices Update
  x-api-slug: azure-api-management-api
  description: Updates an existing API Management service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicename-patch-openapi.md
- name: Azure API Management API ApiManagementServices Get
  x-api-slug: azure-api-management-api
  description: Gets an API Management service resource description.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicename-get-openapi.md
- name: Azure API Management API ApiManagementServices Delete
  x-api-slug: azure-api-management-api
  description: Deletes an existing API Management service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicename-delete-openapi.md
- name: Azure API Management API API Management Services ListByResourceGroup
  x-api-slug: azure-api-management-api
  description: List all API Management services within a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementservice-get-openapi.md
- name: Azure API Management API API Management Services List
  x-api-slug: azure-api-management-api
  description: Lists all API Management services within an Azure subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ApiManagement/service/
  tags: API Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidprovidersmicrosoftapimanagementservice-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegetssotoken-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegetssotoken-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidprovidersmicrosoftapimanagementchecknameavailability-post-openapi.md
- name: Azure API Management API ApiManagementServices UploadCertificate
  x-api-slug: azure-api-management-api
  description: Upload Custom Domain SSL certificate for an API Management service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/uploadcertificate
  tags: API Management Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameuploadcertificate-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameupdatehostname-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapplynetworkconfigurationupdates-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapplynetworkconfigurationupdates-post-openapi.md
- name: Azure API Management API Groups ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of groups defined within a service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroups-get-openapi.md
- name: Azure API Management API Groups Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the group specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-get-openapi.md
- name: Azure API Management API Groups CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-put-openapi.md
- name: Azure API Management API Groups Update
  x-api-slug: azure-api-management-api
  description: Updates the details of the group specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  tags: Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-patch-openapi.md
- name: Azure API Management API Groups Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific group of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-delete-openapi.md
- name: Azure API Management API GroupUsers ListByGroups
  x-api-slug: azure-api-management-api
  description: Lists a collection of the members of the group, specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}/users
  tags: Group Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusers-get-openapi.md
- name: Azure API Management API GroupUsers Create
  x-api-slug: azure-api-management-api
  description: Adds a user to the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}/users/{uid}
  tags: Group Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusersuid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusersuid-put-openapi.md
- name: Azure API Management API GroupUsers Delete
  x-api-slug: azure-api-management-api
  description: Remove existing user from existing group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}/users/{uid}
  tags: Group Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusersuid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusersuid-delete-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityproviders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityproviders-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-get-openapi.md
- name: Azure API Management API IdentityProviders CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates the IdentityProvider configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  tags: Identity Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-put-openapi.md
- name: Azure API Management API IdentityProviders Update
  x-api-slug: azure-api-management-api
  description: Updates an existing IdentityProvider configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  tags: Identity Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-patch-openapi.md
- name: Azure API Management API IdentityProviders Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified identity provider configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  tags: Identity Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-delete-openapi.md
- name: Azure API Management API Loggers ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of loggers in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggers-get-openapi.md
- name: Azure API Management API Loggers Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the logger specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggersloggerid-get-openapi.md
- name: Azure API Management API Loggers CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a logger.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggersloggerid-put-openapi.md
- name: Azure API Management API Loggers Update
  x-api-slug: azure-api-management-api
  description: Updates an existing logger.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggersloggerid-patch-openapi.md
- name: Azure API Management API Loggers Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified logger.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  tags: Loggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggersloggerid-delete-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamenetworkstatus-get-openapi.md
- name: Azure API Management API OpenIdConnectProviders ListByService
  x-api-slug: azure-api-management-api
  description: Lists all OpenID Connect Providers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders
  tags: OpenId Connect Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectproviders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectproviders-get-openapi.md
- name: Azure API Management API OpenIdConnectProviders Get
  x-api-slug: azure-api-management-api
  description: Gets specific OpenID Connect Provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders/{opid}
  tags: OpenId Connect Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-get-openapi.md
- name: Azure API Management API OpenIdConnectProviders CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates the OpenID Connect Provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders/{opid}
  tags: OpenId Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-put-openapi.md
- name: Azure API Management API OpenIdConnectProviders Update
  x-api-slug: azure-api-management-api
  description: Updates the specific OpenID Connect Provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders/{opid}
  tags: OpenId Connect Providers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-patch-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-delete-openapi.md
- name: Azure API Management API Products ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of products in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproducts-get-openapi.md
- name: Azure API Management API Products Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the product specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-get-openapi.md
- name: Azure API Management API Products CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-put-openapi.md
- name: Azure API Management API Products Update
  x-api-slug: azure-api-management-api
  description: Update product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-patch-openapi.md
- name: Azure API Management API Products Delete
  x-api-slug: azure-api-management-api
  description: Delete product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-delete-openapi.md
- name: Azure API Management API ProductApis ListByProducts
  x-api-slug: azure-api-management-api
  description: Lists a collection of the APIs associated with a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/apis
  tags: Product APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidapis-get-openapi.md
- name: Azure API Management API ProductApis Create
  x-api-slug: azure-api-management-api
  description: Adds an API to the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/apis/{apiId}
  tags: Product APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidapisapiid-put-openapi.md
- name: Azure API Management API ProductApis Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified API from the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/apis/{apiId}
  tags: Product APIs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidapisapiid-delete-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroups-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroupsgroupid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroupsgroupid-put-openapi.md
- name: Azure API Management API ProductGroups Delete
  x-api-slug: azure-api-management-api
  description: Deletes the association between the specified group and product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/groups/{groupId}
  tags: Product Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroupsgroupid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroupsgroupid-delete-openapi.md
- name: Azure API Management API ProductSubscriptions ListByProducts
  x-api-slug: azure-api-management-api
  description: Lists the collection of subscriptions to the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/subscriptions
  tags: Product Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidsubscriptions-get-openapi.md
- name: Azure API Management API ProductPolicy Get
  x-api-slug: azure-api-management-api
  description: Get the policy configuration at the Product level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/policy
  tags: Product Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidpolicy-get-openapi.md
- name: Azure API Management API ProductPolicy CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates policy configuration for the Product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/policy
  tags: Product Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidpolicy-put-openapi.md
- name: Azure API Management API ProductPolicy Delete
  x-api-slug: azure-api-management-api
  description: Deletes the policy configuration at the Product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/policy
  tags: Product Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidpolicy-delete-openapi.md
- name: Azure API Management API Properties ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of properties defined within a service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties
  tags: Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproperties-get-openapi.md
- name: Azure API Management API Property Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the property specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  tags: Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-get-openapi.md
- name: Azure API Management API Property CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates a property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  tags: Properties
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-put-openapi.md
- name: Azure API Management API Property Update
  x-api-slug: azure-api-management-api
  description: Updates the specific property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  tags: Properties
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-patch-openapi.md
- name: Azure API Management API Property Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific property from the the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  tags: Properties
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-delete-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkey-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkey-patch-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkeyquotaperiodkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkeyquotaperiodkey-get-openapi.md
- name: Azure API Management API QuotaByPeriodKeys Update
  x-api-slug: azure-api-management-api
  description: Updates an existing quota counter value in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/quotas/{quotaCounterKey}/{quotaPeriodKey}
  tags: Quotas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkeyquotaperiodkey-patch-openapi.md
- name: Azure API Management API Reports ListByService
  x-api-slug: azure-api-management-api
  description: Lists report records.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/reports/{aggregation}
  tags: Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamereportsaggregation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamereportsaggregation-get-openapi.md
- name: Azure API Management API Subscriptions List
  x-api-slug: azure-api-management-api
  description: Lists all subscriptions of the API Management service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptions-get-openapi.md
- name: Azure API Management API Subscriptions Get
  x-api-slug: azure-api-management-api
  description: Gets the specified Subscription entity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssid-get-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssid-put-openapi.md
- name: Azure API Management API Subscriptions Update
  x-api-slug: azure-api-management-api
  description: Updates the details of a subscription specificied by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssid-patch-openapi.md
- name: Azure API Management API Subscriptions Delete
  x-api-slug: azure-api-management-api
  description: Deletes the specified subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssid-delete-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssidregenerateprimarykey-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssidregeneratesecondarykey-post-openapi.md
- name: Azure API Management API TenantAccess Get
  x-api-slug: azure-api-management-api
  description: Get tenant access information details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccess-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccess-get-openapi.md
- name: Azure API Management API TenantAccess Update
  x-api-slug: azure-api-management-api
  description: Update tenant access information details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access
  tags: Tenants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccess-patch-openapi.md
- name: Azure API Management API TenantAccess RegeneratePrimaryKey
  x-api-slug: azure-api-management-api
  description: Regenerate primary access key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/regeneratePrimaryKey
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessregenerateprimarykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessregenerateprimarykey-post-openapi.md
- name: Azure API Management API TenantAccess RegenerateSecondaryKey
  x-api-slug: azure-api-management-api
  description: Regenerate secondary access key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/regenerateSecondaryKey
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessregeneratesecondarykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessregeneratesecondarykey-post-openapi.md
- name: Azure API Management API TenantAccessGit Get
  x-api-slug: azure-api-management-api
  description: Gets the Git access configuration for the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgit-get-openapi.md
- name: Azure API Management API TenantAccessGit RegeneratePrimaryKey
  x-api-slug: azure-api-management-api
  description: Regenerate primary access key for GIT.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git/regeneratePrimaryKey
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgitregenerateprimarykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgitregenerateprimarykey-post-openapi.md
- name: Azure API Management API TenantAccessGit RegenerateSecondaryKey
  x-api-slug: azure-api-management-api
  description: Regenerate secondary access key for GIT.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git/regenerateSecondaryKey
  tags: Tenants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgitregeneratesecondarykey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgitregeneratesecondarykey-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationdeploy-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationsave-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationvalidate-post-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationsyncstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationsyncstate-get-openapi.md
- name: Azure API Management API TenantPolicy Get
  x-api-slug: azure-api-management-api
  description: Get the global policy configuration of the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/policy
  tags: Tenant Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantpolicy-get-openapi.md
- name: Azure API Management API TenantPolicy CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or updates global policy configuration for the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/policy
  tags: Tenant Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantpolicy-put-openapi.md
- name: Azure API Management API TenantPolicy Delete
  x-api-slug: azure-api-management-api
  description: Deletes the global tenant policy configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/policy
  tags: Tenant Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantpolicy-delete-openapi.md
- name: Azure API Management API Users ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of registered users in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusers-get-openapi.md
- name: Azure API Management API Users Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the user specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-get-openapi.md
- name: Azure API Management API Users CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-put-openapi.md
- name: Azure API Management API Users Update
  x-api-slug: azure-api-management-api
  description: Updates the details of the user specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-patch-openapi.md
- name: Azure API Management API Users Delete
  x-api-slug: azure-api-management-api
  description: Deletes specific user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-delete-openapi.md
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
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuidgeneratessourl-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuidgeneratessourl-post-openapi.md
- name: Azure API Management API UserGroups ListByUsers
  x-api-slug: azure-api-management-api
  description: Lists all user groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}/groups
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuidgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuidgroups-get-openapi.md
- name: Azure API Management API UserSubscriptions ListByUsers
  x-api-slug: azure-api-management-api
  description: Lists the collection of subscriptions of the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}/subscriptions
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuidsubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuidsubscriptions-get-openapi.md
- name: Azure API Management API UserIdentities ListByUsers
  x-api-slug: azure-api-management-api
  description: Lists all user identities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}/identities
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuididentities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-api-management/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuididentities-get-openapi.md
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