---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 0
info:
  title: Azure API Management API Users Update
  description: Updates the details of the user specified by its identifier.
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepolicysnippets-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameregions-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapis-get
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  : get:
      summary: Apis Get
      description: Gets the details of the API specified by its identifier.
      operationId: Apis_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - APIs
    put:
      summary: Apis CreateOrUpdate
      description: Creates new or updates existing specified API of the API Management
        service instance.
      operationId: Apis_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-put
      parameters:
      - in: header
        name: If-Match
        description: ETag of the Api Entity
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create or update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - APIs
    patch:
      summary: Apis Update
      description: Updates the specified API of the API Management service instance.
      operationId: Apis_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-patch
      parameters:
      - in: header
        name: If-Match
        description: ETag of the API entity
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: API Update Contract parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - APIs
    delete:
      summary: Apis Delete
      description: Deletes the specified API of the API Management service instance.
      operationId: Apis_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiid-delete
      parameters:
      - in: header
        name: If-Match
        description: ETag of the API Entity
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - APIs
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations
  : get:
      summary: ApiOperations ListByApis
      description: Lists a collection of the operations for the specified API.
      operationId: ApiOperations_ListByApis
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperations-get
      parameters:
      - in: query
        name: $filter
        description: '| Field       | Supported operators    | Supported functions               ||-------------|------------------------|-----------------------------------||
          name        | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          || method      | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          || description | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          || urlTemplate | ge, le, eq, ne, gt, lt | substringof, startswith, endswith
          |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Operations
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}
  : get:
      summary: ApiOperations Get
      description: Gets the details of the API Operation specified by its identifier.
      operationId: ApiOperations_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Operations
    put:
      summary: ApiOperations CreateOrUpdate
      description: Creates a new API operation or updates an existing one.
      operationId: ApiOperations_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Operations
    patch:
      summary: ApiOperations Update
      description: Updates the details of the operation specified by its identifier.
      operationId: ApiOperations_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-patch
      parameters:
      - in: header
        name: If-Match
        description: ETag of the API Operation Entity
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: API Operation Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Operations
    delete:
      summary: ApiOperations Delete
      description: Deletes the specified operation.
      operationId: ApiOperations_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationid-delete
      parameters:
      - in: header
        name: If-Match
        description: ETag of the API Operation Entity
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Operations
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/operations/{operationId}/policy
  : get:
      summary: ApiOperationsPolicy Get
      description: Get the policy configuration at the API Operation level.
      operationId: ApiOperationsPolicy_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationidpolicy-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Operations
    put:
      summary: ApiOperationsPolicy CreateOrUpdate
      description: Creates or updates policy configuration for the API Operation level.
      operationId: ApiOperationsPolicy_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationidpolicy-put
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the Api Operation policy to
          update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The policy contents to apply
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Operations
    delete:
      summary: ApiOperationsPolicy Delete
      description: Deletes the policy configuration at the Api Operation.
      operationId: ApiOperationsPolicy_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidoperationsoperationidpolicy-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the Api operation policy to
          update
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Operations
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/products
  : get:
      summary: ApiProducts ListByApis
      description: Lists all API associated products.
      operationId: ApiProducts_ListByApis
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidproducts-get
      parameters:
      - in: query
        name: $filter
        description: '| Field | Supported operators    | Supported functions                         ||-------|------------------------|---------------------------------------------||
          name  | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Products
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/policy
  : get:
      summary: ApiPolicy Get
      description: Get the policy configuration at the API level.
      operationId: ApiPolicy_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidpolicy-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Policy
    put:
      summary: ApiPolicy CreateOrUpdate
      description: Creates or updates policy configuration for the API.
      operationId: ApiPolicy_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidpolicy-put
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the Api Policy to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The policy contents to apply
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Policy
    delete:
      summary: ApiPolicy Delete
      description: Deletes the policy configuration at the Api.
      operationId: ApiPolicy_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapisapiidpolicy-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the Api policy to update
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Policy
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers
  : get:
      summary: AuthorizationServers ListByService
      description: Lists a collection of authorization servers defined within a service
        instance.
      operationId: AuthorizationServers_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationservers-get
      parameters:
      - in: query
        name: $filter
        description: '| Field | Supported operators    | Supported functions                         ||-------|------------------------|---------------------------------------------||
          id    | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          || name  | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Authorization Servers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/authorizationServers/{authsid}
  : get:
      summary: AuthorizationServers Get
      description: Gets the details of the authorization server specified by its identifier.
      operationId: AuthorizationServers_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Authorization Servers
    put:
      summary: AuthorizationServers CreateOrUpdate
      description: Creates new authorization server or updates an existing authorization
        server.
      operationId: AuthorizationServers_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create or update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Authorization Servers
    patch:
      summary: AuthorizationServers Update
      description: Updates the details of the authorization server specified by its
        identifier.
      operationId: AuthorizationServers_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the authorization server to
          update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: OAuth2 Server settings Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Authorization Servers
    delete:
      summary: AuthorizationServers Delete
      description: Deletes specific authorization server instance.
      operationId: AuthorizationServers_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameauthorizationserversauthsid-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the authentication server
          to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Authorization Servers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends
  : get:
      summary: Backends ListByService
      description: Lists a collection of backends in the specified service instance.
      operationId: Backends_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackends-get
      parameters:
      - in: query
        name: $filter
        description: '| Field | Supported operators    | Supported functions                         ||-------|------------------------|---------------------------------------------||
          id    | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          || host  | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Backends
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backends/{backendid}
  : get:
      summary: Backends Get
      description: Gets the details of the backend specified by its identifier.
      operationId: Backends_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackendsbackendid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Backends
    put:
      summary: Backends CreateOrUpdate
      description: Creates or Updates a backend.
      operationId: Backends_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackendsbackendid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Backends
    patch:
      summary: Backends Update
      description: Updates an existing backend.
      operationId: Backends_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackendsbackendid-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the backend to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Backends
    delete:
      summary: Backends Delete
      description: Deletes the specified backend.
      operationId: Backends_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackendsbackendid-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the backend to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Backends
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates
  : get:
      summary: Certificates ListByService
      description: Lists a collection of all certificates in the specified service
        instance.
      operationId: Certificates_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificates-get
      parameters:
      - in: query
        name: $filter
        description: '| Field          | Supported operators    | Supported functions                         ||----------------|------------------------|---------------------------------------------||
          id             | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || subject        | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || thumbprint     | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || expirationDate | ge, le, eq, ne, gt, lt
          | N/A                                         |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Certificates
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/certificates/{certificateId}
  : get:
      summary: Certificates Get
      description: Gets the details of the certificate specified by its identifier.
      operationId: Certificates_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificatescertificateid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Certificates
    put:
      summary: Certificates CreateOrUpdate
      description: Creates or updates the certificate being used for authentication
        with the backend.
      operationId: Certificates_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificatescertificateid-put
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the certificate to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Certificates
    delete:
      summary: Certificates Delete
      description: Deletes specific certificate.
      operationId: Certificates_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamecertificatescertificateid-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the certificate to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Certificates
  /providers/Microsoft.ApiManagement/operations:
    get:
      summary: API Management Operations List
      description: Lists all of the available REST API operations of the Microsoft.ApiManagement
        provider.
      operationId: ApiManagementOperations_List
      x-api-path-slug: providersmicrosoftapimanagementoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Operations
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/managedeployments
  : post:
      summary: ApiManagementServices ManageDeployments
      description: 'Manages deployments of an API Management service. This operation
        can be used to do the following: Change SKU, Change SKU Units, Change Service
        Tier (Developer/Standard/Premium) and Manage VPN Configuration. This is a
        long running operation and can take several minutes to complete.'
      operationId: ApiManagementServices_ManageDeployments
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamemanagedeployments-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the ManageDeployments operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Service
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/restore
  : post:
      summary: ApiManagementServices Restore
      description: Restores a backup of an API Management service created using the
        ApiManagementServices_Backup operation on the current service. This is a long
        running operation and could take several minutes to complete.
      operationId: ApiManagementServices_Restore
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamerestore-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Restore API Management service from
          backup operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Services
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backup
  : post:
      summary: ApiManagementServices Backup
      description: Creates a backup of the API Management service to the given Azure
        Storage Account. This is long running operation and could take several minutes
        to complete.
      operationId: ApiManagementServices_Backup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamebackup-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the ApiManagementServices_Backup operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Service
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}:
    put:
      summary: ApiManagementServices CreateOrUpdate
      description: Creates or updates an API Management service. This is long running
        operation and could take several minutes to complete.
      operationId: ApiManagementServices_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicename-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the CreateOrUpdate API Management service
          operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Services
    patch:
      summary: ApiManagementServices Update
      description: Updates an existing API Management service.
      operationId: ApiManagementServices_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicename-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the CreateOrUpdate API Management service
          operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Service
    get:
      summary: ApiManagementServices Get
      description: Gets an API Management service resource description.
      operationId: ApiManagementServices_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicename-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Service
    delete:
      summary: ApiManagementServices Delete
      description: Deletes an existing API Management service.
      operationId: ApiManagementServices_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicename-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Service
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/:
    get:
      summary: API Management Services ListByResourceGroup
      description: List all API Management services within a resource group.
      operationId: ApiManagementServices_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementservice-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Service
  /subscriptions/{subscriptionId}/providers/Microsoft.ApiManagement/service/:
    get:
      summary: API Management Services List
      description: Lists all API Management services within an Azure subscription.
      operationId: ApiManagementServices_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftapimanagementservice-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Service
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/getssotoken
  : post:
      summary: ApiManagementServices GetSsoToken
      description: Gets the Single-Sign-On token for the API Management Service which
        is valid for 5 Minutes.
      operationId: ApiManagementServices_GetSsoToken
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegetssotoken-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Management Service
  /subscriptions/{subscriptionId}/providers/Microsoft.ApiManagement/checkNameAvailability:
    post:
      summary: API Management Services Check Name Availability
      description: Checks availability and correctness of a name for an API Management
        service.
      operationId: ApiManagementServices_CheckNameAvailability
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftapimanagementchecknameavailability-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the CheckNameAvailability operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Service
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/uploadcertificate
  : post:
      summary: ApiManagementServices UploadCertificate
      description: Upload Custom Domain SSL certificate for an API Management service.
      operationId: ApiManagementServices_UploadCertificate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameuploadcertificate-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Upload SSL certificate for an API
          Management service operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Services
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/updatehostname
  : post:
      summary: ApiManagementServices UpdateHostname
      description: Creates, updates, or deletes the custom hostnames for an API Management
        service. The custom hostname can be applied to the Proxy and Portal endpoint.
        This is a long running operation and could take several minutes to complete.
      operationId: ApiManagementServices_UpdateHostname
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameupdatehostname-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the UpdateHostname operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Services
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/applynetworkconfigurationupdates
  : post:
      summary: ApiManagementServices ApplyNetworkConfigurationUpdates
      description: Updates the Microsoft.ApiManagement resource running in the Virtual
        network to pick the updated network settings.
      operationId: ApiManagementServices_ApplyNetworkConfigurationUpdates
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameapplynetworkconfigurationupdates-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Products
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups
  : get:
      summary: Groups ListByService
      description: Lists a collection of groups defined within a service instance.
      operationId: Groups_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroups-get
      parameters:
      - in: query
        name: $filter
        description: '| Field       | Supported operators    | Supported functions                         ||-------------|------------------------|---------------------------------------------||
          id          | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || name        | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || description | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || type        | eq, ne                 |
          N/A                                         |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Groups
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}
  : get:
      summary: Groups Get
      description: Gets the details of the group specified by its identifier.
      operationId: Groups_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Groups
    put:
      summary: Groups CreateOrUpdate
      description: Creates or Updates a group.
      operationId: Groups_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Groups
    patch:
      summary: Groups Update
      description: Updates the details of the group specified by its identifier.
      operationId: Groups_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-patch
      parameters:
      - in: header
        name: If-Match
        description: ETag of the Group Entity
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Groups
    delete:
      summary: Groups Delete
      description: Deletes specific group of the API Management service instance.
      operationId: Groups_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupid-delete
      parameters:
      - in: header
        name: If-Match
        description: ETag of the Group Entity
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Groups
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}/users
  : get:
      summary: GroupUsers ListByGroups
      description: Lists a collection of the members of the group, specified by its
        identifier.
      operationId: GroupUsers_ListByGroups
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusers-get
      parameters:
      - in: query
        name: $filter
        description: '| Field            | Supported operators    | Supported functions               ||------------------|------------------------|-----------------------------------||
          id               | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || firstName        | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || lastName         | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || email            | ge, le, eq, ne, gt,
          lt | substringof, contains, startswith, endswith || state            | eq                     |
          N/A                               || registrationDate | ge, le, eq, ne,
          gt, lt | N/A                               || note             | ge, le,
          eq, ne, gt, lt | substringof, contains, startswith, endswith |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Group Users
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/groups/{groupId}/users/{uid}
  : put:
      summary: GroupUsers Create
      description: Adds a user to the specified group.
      operationId: GroupUsers_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusersuid-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Group Users
    delete:
      summary: GroupUsers Delete
      description: Remove existing user from existing group.
      operationId: GroupUsers_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamegroupsgroupidusersuid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Group Users
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders
  : get:
      summary: IdentityProviders ListByService
      description: Lists a collection of Identity Provider configured in the specified
        service instance.
      operationId: IdentityProviders_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityproviders-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/identityProviders/{identityProviderName}
  : get:
      summary: IdentityProviders Get
      description: Gets the configuration details of the identity Provider configured
        in specified service instance.
      operationId: IdentityProviders_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
    put:
      summary: IdentityProviders CreateOrUpdate
      description: Creates or Updates the IdentityProvider configuration.
      operationId: IdentityProviders_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
    patch:
      summary: IdentityProviders Update
      description: Updates an existing IdentityProvider configuration.
      operationId: IdentityProviders_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the identity provider configuration
          to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
    delete:
      summary: IdentityProviders Delete
      description: Deletes the specified identity provider configuration.
      operationId: IdentityProviders_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameidentityprovidersidentityprovidername-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the backend to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Identity Providers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers
  : get:
      summary: Loggers ListByService
      description: Lists a collection of loggers in the specified service instance.
      operationId: Loggers_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggers-get
      parameters:
      - in: query
        name: $filter
        description: '| Field | Supported operators    | Supported functions                         ||-------|------------------------|---------------------------------------------||
          id    | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          || type  | eq                     |                                             |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Loggers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  : get:
      summary: Loggers Get
      description: Gets the details of the logger specified by its identifier.
      operationId: Loggers_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggersloggerid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Loggers
    put:
      summary: Loggers CreateOrUpdate
      description: Creates or Updates a logger.
      operationId: Loggers_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggersloggerid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Loggers
    patch:
      summary: Loggers Update
      description: Updates an existing logger.
      operationId: Loggers_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggersloggerid-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the logger to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Loggers
    delete:
      summary: Loggers Delete
      description: Deletes the specified logger.
      operationId: Loggers_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameloggersloggerid-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the logger to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Loggers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/networkstatus
  : get:
      summary: NetworkStatus GetByService
      description: Gets the Connectivity Status to the external resources on which
        the Api Management service depends from inside the Cloud Service. This also
        returns the DNS Servers as visible to the CloudService.
      operationId: NetworkStatus_GetByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamenetworkstatus-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Network Status
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders
  : get:
      summary: OpenIdConnectProviders ListByService
      description: Lists all OpenID Connect Providers.
      operationId: OpenIdConnectProviders_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectproviders-get
      parameters:
      - in: query
        name: $filter
        description: '| Field | Supported operators    | Supported functions                         ||-------|------------------------|---------------------------------------------||
          id    | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          || name  | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - OpenId Connect Providers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/openidConnectProviders/{opid}
  : get:
      summary: OpenIdConnectProviders Get
      description: Gets specific OpenID Connect Provider.
      operationId: OpenIdConnectProviders_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - OpenId Connect Providers
    put:
      summary: OpenIdConnectProviders CreateOrUpdate
      description: Creates or updates the OpenID Connect Provider.
      operationId: OpenIdConnectProviders_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - OpenId Connect Providers
    patch:
      summary: OpenIdConnectProviders Update
      description: Updates the specific OpenID Connect Provider.
      operationId: OpenIdConnectProviders_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the OpenID Connect Provider
          to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - OpenId Connect Providers
    delete:
      summary: OpenIdConnectProviders Delete
      description: Deletes specific OpenID Connect Provider of the API Management
        service instance.
      operationId: OpenIdConnectProviders_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameopenidconnectprovidersopid-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the OpenID Connect Provider
          to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - OpenId Connect Providers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products
  : get:
      summary: Products ListByService
      description: Lists a collection of products in the specified service instance.
      operationId: Products_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproducts-get
      parameters:
      - in: query
        name: $filter
        description: '| Field       | Supported operators    | Supported functions                         ||-------------|------------------------|---------------------------------------------||
          id          | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || name        | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || description | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || terms       | ge, le, eq, ne, gt, lt |
          substringof, contains, startswith, endswith || state       | eq                     |                                             |'
      - in: query
        name: expandGroups
        description: When set to true, the response contains an array of groups that
          have visibility to the product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  : get:
      summary: Products Get
      description: Gets the details of the product specified by its identifier.
      operationId: Products_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
    put:
      summary: Products CreateOrUpdate
      description: Creates or Updates a product.
      operationId: Products_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create or update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Products
    patch:
      summary: Products Update
      description: Update product.
      operationId: Products_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-patch
      parameters:
      - in: header
        name: If-Match
        description: ETag of the Product Entity
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Products
    delete:
      summary: Products Delete
      description: Delete product.
      operationId: Products_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductid-delete
      parameters:
      - in: query
        name: deleteSubscriptions
        description: Delete existing subscriptions to the product or not
      - in: header
        name: If-Match
        description: ETag of the Product Entity
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/apis
  : get:
      summary: ProductApis ListByProducts
      description: Lists a collection of the APIs associated with a product.
      operationId: ProductApis_ListByProducts
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidapis-get
      parameters:
      - in: query
        name: $filter
        description: '| Field       | Supported operators    | Supported functions                         ||-------------|------------------------|---------------------------------------------||
          id          | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || name        | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || description | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || serviceUrl  | ge, le, eq, ne, gt, lt |
          substringof, contains, startswith, endswith || path        | ge, le, eq,
          ne, gt, lt | substringof, contains, startswith, endswith |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product APIs
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/apis/{apiId}
  : put:
      summary: ProductApis Create
      description: Adds an API to the specified product.
      operationId: ProductApis_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidapisapiid-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product APIs
    delete:
      summary: ProductApis Delete
      description: Deletes the specified API from the specified product.
      operationId: ProductApis_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidapisapiid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product APIs
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/groups
  : get:
      summary: ProductGroups ListByProducts
      description: Lists the collection of developer groups associated with the specified
        product.
      operationId: ProductGroups_ListByProducts
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroups-get
      parameters:
      - in: query
        name: $filter
        description: '| Field       | Supported operators    | Supported functions                         ||-------------|------------------------|---------------------------------------------||
          id          | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || name        | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || description | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || type        | eq, ne                 |
          N/A                                         |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product Groups
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/groups/{groupId}
  : put:
      summary: ProductGroups Create
      description: Adds the association between the specified developer group with
        the specified product.
      operationId: ProductGroups_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroupsgroupid-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product Groups
    delete:
      summary: ProductGroups Delete
      description: Deletes the association between the specified group and product.
      operationId: ProductGroups_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidgroupsgroupid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product Groups
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/subscriptions
  : get:
      summary: ProductSubscriptions ListByProducts
      description: Lists the collection of subscriptions to the specified product.
      operationId: ProductSubscriptions_ListByProducts
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidsubscriptions-get
      parameters:
      - in: query
        name: $filter
        description: '| Field        | Supported operators    | Supported functions                         ||--------------|------------------------|---------------------------------------------||
          id           | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || name         | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || stateComment | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || userId       | ge, le, eq, ne, gt, lt
          | substringof, contains, startswith, endswith || productId    | ge, le,
          eq, ne, gt, lt | substringof, contains, startswith, endswith || state        |
          eq                     |                                             |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product Subscriptions
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}/policy
  : get:
      summary: ProductPolicy Get
      description: Get the policy configuration at the Product level.
      operationId: ProductPolicy_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidpolicy-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product Policy
    put:
      summary: ProductPolicy CreateOrUpdate
      description: Creates or updates policy configuration for the Product.
      operationId: ProductPolicy_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidpolicy-put
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the product policy to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The policy contents to apply
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Product Policy
    delete:
      summary: ProductPolicy Delete
      description: Deletes the policy configuration at the Product.
      operationId: ProductPolicy_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproductsproductidpolicy-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the product policy to update
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Product Policy
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties
  : get:
      summary: Properties ListByService
      description: Lists a collection of properties defined within a service instance.
      operationId: Properties_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameproperties-get
      parameters:
      - in: query
        name: $filter
        description: '| Field | Supported operators    | Supported functions                                   ||-------|------------------------|-------------------------------------------------------||
          tags  | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith,
          any, all || name  | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith           |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Properties
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/properties/{propId}
  : get:
      summary: Property Get
      description: Gets the details of the property specified by its identifier.
      operationId: Property_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Properties
    put:
      summary: Property CreateOrUpdate
      description: Creates or updates a property.
      operationId: Property_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Properties
    patch:
      summary: Property Update
      description: Updates the specific property.
      operationId: Property_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the property to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Properties
    delete:
      summary: Property Delete
      description: Deletes specific property from the the API Management service instance.
      operationId: Property_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamepropertiespropid-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the property to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Properties
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/quotas/{quotaCounterKey}
  : get:
      summary: QuotaByCounterKeys ListByService
      description: Lists a collection of current quota counter periods associated
        with the counter-key configured in the policy on the specified service instance.
        The api does not support paging yet.
      operationId: QuotaByCounterKeys_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Quotas
    patch:
      summary: QuotaByCounterKeys Update
      description: Updates all the quota counter values specified with the existing
        quota counter key to a value in the specified service instance. This should
        be used for reset of the quota counter values.
      operationId: QuotaByCounterKeys_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkey-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The value of the quota counter to be applied to all quota counter
          periods
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Quotas
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/quotas/{quotaCounterKey}/{quotaPeriodKey}
  : get:
      summary: QuotaByPeriodKeys Get
      description: Gets the value of the quota counter associated with the counter-key
        in the policy for the specific period in service instance.
      operationId: QuotaByPeriodKeys_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkeyquotaperiodkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Quotas
    patch:
      summary: QuotaByPeriodKeys Update
      description: Updates an existing quota counter value in the specified service
        instance.
      operationId: QuotaByPeriodKeys_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamequotasquotacounterkeyquotaperiodkey-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The value of the Quota counter to be applied on the specified
          period
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Quotas
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/reports/{aggregation}
  : get:
      summary: Reports ListByService
      description: Lists report records.
      operationId: Reports_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamereportsaggregation-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: path
        name: aggregation
        description: Report aggregation
      - in: query
        name: interval
        description: By time interval
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Reports
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions
  : get:
      summary: Subscriptions List
      description: Lists all subscriptions of the API Management service instance.
      operationId: Subscriptions_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptions-get
      parameters:
      - in: query
        name: $filter
        description: '| Field        | Supported operators    | Supported functions                         ||--------------|------------------------|---------------------------------------------||
          id           | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || name         | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || stateComment | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || userId       | ge, le, eq, ne, gt, lt
          | substringof, contains, startswith, endswith || productId    | ge, le,
          eq, ne, gt, lt | substringof, contains, startswith, endswith || state        |
          eq                     |                                             |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}
  : get:
      summary: Subscriptions Get
      description: Gets the specified Subscription entity.
      operationId: Subscriptions_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
    put:
      summary: Subscriptions CreateOrUpdate
      description: Creates or updates the subscription of specified user to the specified
        product.
      operationId: Subscriptions_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
    patch:
      summary: Subscriptions Update
      description: Updates the details of a subscription specificied by its identifier.
      operationId: Subscriptions_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssid-patch
      parameters:
      - in: header
        name: If-Match
        description: ETag of the Subscription Entity
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
    delete:
      summary: Subscriptions Delete
      description: Deletes the specified subscription.
      operationId: Subscriptions_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssid-delete
      parameters:
      - in: header
        name: If-Match
        description: ETag of the Subscription Entity
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}/regeneratePrimaryKey
  : post:
      summary: Subscriptions RegeneratePrimaryKey
      description: Regenerates primary key of existing subscription of the API Management
        service instance.
      operationId: Subscriptions_RegeneratePrimaryKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssidregenerateprimarykey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/subscriptions/{sid}/regenerateSecondaryKey
  : post:
      summary: Subscriptions RegenerateSecondaryKey
      description: Regenerates secondary key of existing subscription of the API Management
        service instance.
      operationId: Subscriptions_RegenerateSecondaryKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenamesubscriptionssidregeneratesecondarykey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access
  : get:
      summary: TenantAccess Get
      description: Get tenant access information details.
      operationId: TenantAccess_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccess-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenants
    patch:
      summary: TenantAccess Update
      description: Update tenant access information details.
      operationId: TenantAccess_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccess-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the tenant access settings
          to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/regeneratePrimaryKey
  : post:
      summary: TenantAccess RegeneratePrimaryKey
      description: Regenerate primary access key.
      operationId: TenantAccess_RegeneratePrimaryKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessregenerateprimarykey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/regenerateSecondaryKey
  : post:
      summary: TenantAccess RegenerateSecondaryKey
      description: Regenerate secondary access key.
      operationId: TenantAccess_RegenerateSecondaryKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessregeneratesecondarykey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git
  : get:
      summary: TenantAccessGit Get
      description: Gets the Git access configuration for the tenant.
      operationId: TenantAccessGit_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgit-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git/regeneratePrimaryKey
  : post:
      summary: TenantAccessGit RegeneratePrimaryKey
      description: Regenerate primary access key for GIT.
      operationId: TenantAccessGit_RegeneratePrimaryKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgitregenerateprimarykey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/access/git/regenerateSecondaryKey
  : post:
      summary: TenantAccessGit RegenerateSecondaryKey
      description: Regenerate secondary access key for GIT.
      operationId: TenantAccessGit_RegenerateSecondaryKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantaccessgitregeneratesecondarykey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/configuration/deploy
  : post:
      summary: TenantConfiguration Deploy
      description: This operation applies changes from the specified Git branch to
        the configuration database. This is a long running operation and could take
        several minutes to complete.
      operationId: TenantConfiguration_Deploy
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationdeploy-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Deploy Configuration parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/configuration/save
  : post:
      summary: TenantConfiguration Save
      description: This operation creates a commit with the current configuration
        snapshot to the specified branch in the repository. This is a long running
        operation and could take several minutes to complete.
      operationId: TenantConfiguration_Save
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationsave-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Save Configuration parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/configuration/validate
  : post:
      summary: TenantConfiguration Validate
      description: This operation validates the changes in the specified Git branch.
        This is a long running operation and could take several minutes to complete.
      operationId: TenantConfiguration_Validate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationvalidate-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Validate Configuration parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/configuration/syncState
  : get:
      summary: TenantConfigurationSyncState Get
      description: Gets the status of the most recent synchronization between the
        configuration database and the Git repository.
      operationId: TenantConfigurationSyncState_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantconfigurationsyncstate-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenants
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/tenant/policy
  : get:
      summary: TenantPolicy Get
      description: Get the global policy configuration of the tenant.
      operationId: TenantPolicy_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantpolicy-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenant Policy
    put:
      summary: TenantPolicy CreateOrUpdate
      description: Creates or updates global policy configuration for the tenant.
      operationId: TenantPolicy_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantpolicy-put
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the tenant policy to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The policy content details
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Tenant Policy
    delete:
      summary: TenantPolicy Delete
      description: Deletes the global tenant policy configuration.
      operationId: TenantPolicy_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenametenantpolicy-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the tenant policy to update
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Tenant Policy
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users:
    get:
      summary: Users ListByService
      description: Lists a collection of registered users in the specified service
        instance.
      operationId: Users_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusers-get
      parameters:
      - in: query
        name: $filter
        description: '| Field            | Supported operators    | Supported functions               ||------------------|------------------------|-----------------------------------||
          id               | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || firstName        | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || lastName         | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || email            | ge, le, eq, ne, gt,
          lt | substringof, contains, startswith, endswith || state            | eq                     |
          N/A                               || registrationDate | ge, le, eq, ne,
          gt, lt | N/A                               || note             | ge, le,
          eq, ne, gt, lt | substringof, contains, startswith, endswith |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/users/{uid}
  : get:
      summary: Users Get
      description: Gets the details of the user specified by its identifier.
      operationId: Users_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
    put:
      summary: Users CreateOrUpdate
      description: Creates or Updates a user.
      operationId: Users_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create or update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
    patch:
      summary: Users Update
      description: Updates the details of the user specified by its identifier.
      operationId: Users_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftapimanagementserviceservicenameusersuid-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the user to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
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