---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 0
info:
  title: Azure API Management API API Management Services List
  description: Lists all API Management services within an Azure subscription.
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}
  : get:
      summary: Apis Get
      description: Gets the details of the API specified by its identifier.
      operationId: Apis_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperations-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationidpolicy-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationidpolicy-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidoperationsoperationidpolicy-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidproducts-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidpolicy-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidpolicy-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidpolicy-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationservers-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameauthorizationserversauthsid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackends-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackendsbackendid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackendsbackendid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackendsbackendid-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackendsbackendid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificates-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificatescertificateid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificatescertificateid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamecertificatescertificateid-delete
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
      x-api-path-slug: providersmicrosoft-apimanagementoperations-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamemanagedeployments-post
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamerestore-post
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackup-post
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicename-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicename-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicename-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicename-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementservice-get
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
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-apimanagementservice-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Service
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