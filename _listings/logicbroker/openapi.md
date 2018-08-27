swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 1
info:
  title: CommerceAPI
  version: 1.0.0
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Shipments/ContainerCode:
    get:
      summary: Gets a new SSCC18 container code.
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Shipment_GetContainerCode
      x-api-path-slug: apiv1shipmentscontainercode-get
      parameters:
      - in: query
        name: containerType
        description: Container type, valid types are box and pallet
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - SSCC18
      - Container
      - Code