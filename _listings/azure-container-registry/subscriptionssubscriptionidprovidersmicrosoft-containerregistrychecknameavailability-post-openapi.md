---
swagger: "2.0"
x-collection-name: Azure Container Registry
x-complete: 0
info:
  title: Azure Container Registry API Registries Check Name Availability
  version: 1.0.0
  description: Checks whether the container registry name is available for use. The
    name must contain only alphanumeric characters, be globally unique, and between
    5 and 60 characters in length.
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