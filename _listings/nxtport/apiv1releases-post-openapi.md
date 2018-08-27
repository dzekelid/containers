---
swagger: "2.0"
x-collection-name: NxtPort
x-complete: 0
info:
  title: NxtPort T-mining Secure Container Release API Create release
  description: Serves to create a Container together with its PickupRight that gets
    automatically transferred to the consignee.
  contact:
    name: T-Mining API support
    url: http://support.t-mining.be/
    email: support@t-mining.be
  version: 1.0.0
host: api.nxtport.eu
basePath: /blockchain
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /nxtportdocument/{blnumber}/cn/{containerNumber}:
    get:
      summary: Returns the file with corresponding blnumbers and containernumber.
      description: Returns the file with corresponding blnumbers and containernumber..
      operationId: NxtportdocumentByBlnumberCnByContainerNumberGet
      x-api-path-slug: nxtportdocumentblnumbercncontainernumber-get
      parameters:
      - in: path
        name: blnumber
        description: blnumber
      - in: path
        name: containerNumber
        description: containernumber
      - in: header
        name: Ocp-Apim-Subscription-Key
      responses:
        200:
          description: OK
      tags:
      - Returns
      - File
      - Corresponding
      - Blnumbers
      - Containernumber
  /api/v1/containers:
    get:
      summary: List Containers
      description: Get all containers currently in the database. Only Containers accessible
        by the user will be reported.
      operationId: getApiV1Containers
      x-api-path-slug: apiv1containers-get
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      responses:
        200:
          description: OK
      tags:
      - List
      - Containers
    post:
      summary: Create a new Container
      description: |-
        Create a new container.
        If all goes well, a 200 status code is returned.
        If the create fails, a 500 status code is returned.
      operationId: postApiV1Containers
      x-api-path-slug: apiv1containers-post
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - New
      - Container
  /api/v1/containers/{id}/events:
    get:
      summary: Get container events
      description: Get the list of Events related to a container
      operationId: getApiV1ContainersEvents
      x-api-path-slug: apiv1containersidevents-get
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      - in: path
        name: id
        description: id of the Container
      responses:
        200:
          description: OK
      tags:
      - Container
      - Events
  /api/v1/container_types:
    get:
      summary: List
      description: List all ContainerTypes
      operationId: getApiV1ContainerTypes
      x-api-path-slug: apiv1container-types-get
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      responses:
        200:
          description: OK
      tags:
      - List
  /api/v1/events/:
    post:
      summary: Create an Event
      description: |-
        Used to create an event for a container at a specific location and time.
        Each event is defined by a type.
        Currently a limited number of events (pickup and availability) are supported, but this may be extended with e.g. passage events.
        There are 2 ways to refer to a Container: by means of its id as defined in the Blockchain (this requires recording these ids in your app), or by means of a combination of the blNumber and isoNumber. Similarly, locations can be specified in 2 ways: by means of their id as defined in the Blockchain or by means of their name. In the latter case the name must be defined in a mapping   file for the Organization you - as a user- belong to. Also note that the container may not yet be known in the Blockchain at the time
        an availability event is created!
      operationId: postApiV1Events
      x-api-path-slug: apiv1events-post
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Event
  /api/v1/releases/:
    post:
      summary: Create release
      description: Serves to create a Container together with its PickupRight that
        gets automatically transferred to the consignee.
      operationId: postApiV1Releases
      x-api-path-slug: apiv1releases-post
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Release
  /api/v1/releases/{id}:
    delete:
      summary: Block
      description: |-
        Blocking a release is done by a delete. This will revoke the PickupRight from the consignee. The Container and its PickupRight are deleted. Afterwards it is still possible to release again.
         The following conditions apply for this to work:
        * the container must have been released, i.e. there must be a vallid PickupRight   for the Container
        * the PickupRight should not be transferred to another Organization than the one that got the relesase initially
        * the PickupRight should not yet be assigned (to a driver / skipper)
      operationId: deleteApiV1Releases
      x-api-path-slug: apiv1releasesid-delete
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      - in: path
        name: id
        description: original id of the release as defined in the client system and
          passed during the creation
      responses:
        200:
          description: OK
      tags:
      - Block
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