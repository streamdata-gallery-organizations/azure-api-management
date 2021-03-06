---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 0
info:
  title: Azure API Management API ProductGroups ListByProducts
  description: Lists the collection of developer groups associated with the specified
    product.
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/getssotoken
  : post:
      summary: ApiManagementServices GetSsoToken
      description: Gets the Single-Sign-On token for the API Management Service which
        is valid for 5 Minutes.
      operationId: ApiManagementServices_GetSsoToken
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegetssotoken-post
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
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-apimanagementchecknameavailability-post
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameuploadcertificate-post
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameupdatehostname-post
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapplynetworkconfigurationupdates-post
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroups-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusers-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusersuid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegroupsgroupidusersuid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityproviders-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameidentityprovidersidentityprovidername-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggers-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamenetworkstatus-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectproviders-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameopenidconnectprovidersopid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproducts-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidapis-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidapisapiid-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidapisapiid-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductidgroups-get
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