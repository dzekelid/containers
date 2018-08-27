---
swagger: "2.0"
x-collection-name: NxtPort
x-complete: 0
info:
  title: NxtPort Consignment API Returns the file with corresponding blnumbers and
    containernumber.
  description: Returns the file with corresponding blnumbers and containernumber..
  version: 1.0.0
host: api.nxtport.eu
basePath: /Consignment/v1
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