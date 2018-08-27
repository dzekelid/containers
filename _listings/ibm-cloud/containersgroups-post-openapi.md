---
swagger: "2.0"
x-collection-name: IBM Cloud
x-complete: 0
info:
  title: IBM Containers Create and start a container group.
  description: "This endpoint creates and starts a new container group in your space.
    A container group consists of two or more single containers that are all created
    from the same container image and as a consequence are configured in the same
    way. Container groups offer different options at no cost to make your app highly
    available, such as in-built load balancing, auto-recovery of unhealthy container
    instances, and auto-scaling of container instances based on CPU and memory usage.\n\nTo
    create a container group with IBM Containers, you must at least define a container
    group name and the image that the container group is based on. Required attributes:\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n-
    Name: The container group name must start with a letter and then can include uppercase
    letters, lowercase letters, numbers, periods (.), underscores (_), or hyphens
    (-). \n- Image: You must include the full path to the image in your private Bluemix
    registry in the format:`registry.ng.bluemix.net/<namespace>/<image>`."
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
  /containers/floating-ips/{ip}/release:
    post:
      summary: Release public IP address
      description: 'This endpoint releases a public IP address from a space (corresponding
        IBM Containers command: `cf ic ip release <ip_adress>`). The public IP address
        is no longer allocated to the space. If a container was bound to the IP address,
        it is automatically unbound.'
      operationId: this-endpoint-releases-a-public-ip-address-from-a-space-corresponding-ibm-containers-command-cf-ic-i
      x-api-path-slug: containersfloatingipsiprelease-post
      parameters:
      - in: path
        name: ip
        description: The public IP address that you want to release
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
      - Ip
      - Release
  /containers/groups:
    get:
      summary: List all container groups in a space
      description: 'This endpoint returns a list of all container groups in a space
        independent of their current state. (corresponding IBM Containers command:
        `cf ic group list`).'
      operationId: this-endpoint-returns-a-list-of-all-container-groups-in-a-space-independent-of-their-current-state--
      x-api-path-slug: containersgroups-get
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
      - Groups
    post:
      summary: Create and start a container group.
      description: "This endpoint creates and starts a new container group in your
        space. A container group consists of two or more single containers that are
        all created from the same container image and as a consequence are configured
        in the same way. Container groups offer different options at no cost to make
        your app highly available, such as in-built load balancing, auto-recovery
        of unhealthy container instances, and auto-scaling of container instances
        based on CPU and memory usage.\n\nTo create a container group with IBM Containers,
        you must at least define a container group name and the image that the container
        group is based on. Required attributes:\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n-
        Name: The container group name must start with a letter and then can include
        uppercase letters, lowercase letters, numbers, periods (.), underscores (_),
        or hyphens (-). \n- Image: You must include the full path to the image in
        your private Bluemix registry in the format:`registry.ng.bluemix.net/<namespace>/<image>`."
      operationId: this-endpoint-creates-and-starts-a-new-container-group-in-your-space--a-container-group-consists-of-
      x-api-path-slug: containersgroups-post
      parameters:
      - in: body
        name: RequiredAttributes
        description: Attributes that are required to create a container group in your
          space
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
      - Groups
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