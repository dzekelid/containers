---
swagger: "2.0"
x-collection-name: IBM Cloud
x-complete: 0
info:
  title: IBM Containers Request a public IP address for a space
  description: 'This endpoint requests a new public IP address for a space (corresponding
    IBM Containers command: `cf ic ip request`). The number of public IP addresses
    depends on the quota that is assigned to the space. If there is not enough quota
    left to request a new public IP address, you can either contact your organization
    manager to increase the quota, or unbind an existing IP address from a container
    by running `cf ic ip unbind <ip_adress> <container>` command, or  calling the
    `POST /container/{name_or_id}/floating-ips/{ip}/unbind` endpoint.'
  version: 3.0.0
host: containers-api.ng.bluemix.net
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /containers/create:
    post:
      summary: Create and start a single container
      description: "This endpoint creates and starts a single container in your space
        based on the Docker image that is specified in the Image field of the request
        json. A single container in IBM Containers is similar to a container that
        you create in your local Docker environment. Single containers are a good
        way to start with IBM Containers and to learn about how containers work in
        the IBM Cloud and the features that IBM Containers provides. They are also
        recommended when you want to run simple app tests or during the development
        process of an app. \n\n In the Docker API there are two separate APIs to create
        and start a container. However in IBM Containers a container is created and
        started in a single API call. Therefore, this API merges parameters from the
        Docker API to create and start container. \n\n To create a container with
        IBM Containers, you must at least define the image that the container is based
        on.\n\n- Image: You must include the full path to the image in your private
        Bluemix registry in the format: `registry.ng.bluemix.net/<namespace>/<image>`."
      operationId: this-endpoint-creates-and-starts-a-single-container-in-your-space-based-on-the-docker-image-that-is-
      x-api-path-slug: containerscreate-post
      parameters:
      - in: query
        name: name
        description: Choose a name for your container
      - in: body
        name: Param
        description: Summary of input parameter to create a container in IBM Containers
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-Auth-Project-Id
        description: The unique ID of your organization space where you want to create
          or work with your containers
      - in: header
        name: X-Auth-Token
        description: The Bluemix JSON web token that you receive when logging into
          Bluemix
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Create
  /containers/floating-ips:
    get:
      summary: List available public IP addresses in a space
      description: 'This endpoint returns a list of all public IP addresses that are
        allocated to a space and not bound to a container. If you want to list all
        public IP addresses that are allocated to a space, even those that are already
        bound to a container, use the `all` query parameter (corrsponding IBM Containers
        command: `cf ic ip list`).'
      operationId: this-endpoint-returns-a-list-of-all-public-ip-addresses-that-are-allocated-to-a-space-and-not-bound-
      x-api-path-slug: containersfloatingips-get
      parameters:
      - in: query
        name: all
        description: If this option is set to `all=1`, `all=True`, or `all=true`,
          all public IP addresses that are allocated to a space are returned
      - in: header
        name: X-Auth-Project-Id
        description: The unique ID of your organization space where you want to create
          or work with your containers
      - in: header
        name: X-Auth-Token
        description: The Bluemix JSON web token that you receive when logging into
          Bluemix
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Floating-ips
  /containers/floating-ips/request:
    post:
      summary: Request a public IP address for a space
      description: 'This endpoint requests a new public IP address for a space (corresponding
        IBM Containers command: `cf ic ip request`). The number of public IP addresses
        depends on the quota that is assigned to the space. If there is not enough
        quota left to request a new public IP address, you can either contact your
        organization manager to increase the quota, or unbind an existing IP address
        from a container by running `cf ic ip unbind <ip_adress> <container>` command,
        or  calling the `POST /container/{name_or_id}/floating-ips/{ip}/unbind` endpoint.'
      operationId: this-endpoint-requests-a-new-public-ip-address-for-a-space-corresponding-ibm-containers-command-cf-i
      x-api-path-slug: containersfloatingipsrequest-post
      parameters:
      - in: header
        name: X-Auth-Project-Id
        description: The unique ID of your organization space where you want to create
          or work with your containers
      - in: header
        name: X-Auth-Token
        description: The Bluemix JSON web token that you receive when logging into
          Bluemix
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Floating-ips
      - Request
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