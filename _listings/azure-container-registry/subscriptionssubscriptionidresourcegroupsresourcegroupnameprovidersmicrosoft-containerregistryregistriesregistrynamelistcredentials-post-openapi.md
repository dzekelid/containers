---
swagger: "2.0"
x-collection-name: Azure Container Registry
x-complete: 0
info:
  title: Azure Container Registry API Registries List Credentials
  version: 1.0.0
  description: Lists the login credentials for the specified container registry.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.ContainerRegistry/checkNameAvailability:
    post:
      summary: Registries Check Name Availability
      description: Checks whether the container registry name is available for use.
        The name must contain only alphanumeric characters, be globally unique, and
        between 5 and 60 characters in length.
      operationId: Registries_CheckNameAvailability
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-containerregistrychecknameavailability-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: registryNameCheckRequest
        description: The object containing information for the availability request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Registries
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries/{registryName}
  : get:
      summary: Registries Get
      description: Gets the properties of the specified container registry.
      operationId: Registries_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Registries
    put:
      summary: Registries Create
      description: Creates a container registry with the specified parameters.
      operationId: Registries_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: registryCreateParameters
        description: The parameters for creating a container registry
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Registries
    delete:
      summary: Registries Delete
      description: Deletes a container registry.
      operationId: Registries_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Registries
    patch:
      summary: Registries Update
      description: Updates a container registry with the specified parameters.
      operationId: Registries_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: registryUpdateParameters
        description: The parameters for updating a container registry
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Registries
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries:
    get:
      summary: Registries List By Resource Group
      description: Lists all the container registries under the specified resource
        group.
      operationId: Registries_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistries-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Registries
  /subscriptions/{subscriptionId}/providers/Microsoft.ContainerRegistry/registries:
    get:
      summary: Registries List
      description: Lists all the container registries under the specified subscription.
      operationId: Registries_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-containerregistryregistries-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Registries
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries/{registryName}/listCredentials
  : post:
      summary: Registries List Credentials
      description: Lists the login credentials for the specified container registry.
      operationId: Registries_ListCredentials
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistrynamelistcredentials-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Registries
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