---
swagger: "2.0"
x-collection-name: AWS EC2 Container Service
x-complete: 0
info:
  title: Amazon EC2 Container Service API Register Container Instance
  version: 1.0.0
  description: Deregisters an Amazon ECS container instance from the specified cluster.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeregisterContainerInstance:
    get:
      summary: Deregister Container Instance
      description: Deregisters an Amazon ECS container instance from the specified
        cluster.
      operationId: deregisterContainerInstance
      x-api-path-slug: actionderegistercontainerinstance-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that hosts the container instance            to deregister
        type: string
      - in: query
        name: containerInstance
        description: The container instance ID or full Amazon Resource Name (ARN)
          of the container instance to            deregister
        type: string
      - in: query
        name: force
        description: Forces the deregistration of the container instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Instances
  /?Action=DescribeContainerInstances:
    get:
      summary: Describe Container Instances
      description: Describes Amazon EC2 Container Service container instances.
      operationId: describeContainerInstances
      x-api-path-slug: actiondescribecontainerinstances-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that hosts the container instances            to describe
        type: string
      - in: query
        name: containerInstances
        description: A space-separated list of container instance IDs or full Amazon
          Resource Name (ARN)            entries
        type: string
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Instances
  /?Action=ListContainerInstances:
    get:
      summary: List Container Instances
      description: Returns a list of container instances in a specified cluster.
      operationId: listContainerInstances
      x-api-path-slug: actionlistcontainerinstances-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that hosts the container instances            to list
        type: string
      - in: query
        name: filter
        description: You can filter the results of a ListContainerInstances operation
          with            cluster query language statements
        type: string
      - in: query
        name: maxResults
        description: The maximum number of container instance results returned by                ListContainerInstances
          in paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated                ListContainerInstances
          request where maxResults was used            and the results exceeded the
          value of that parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Instances
  /?Action=RegisterContainerInstance:
    get:
      summary: Register Container Instance
      description: Deregisters an Amazon ECS container instance from the specified
        cluster.
      operationId: registerContainerInstance
      x-api-path-slug: actionregistercontainerinstance-get
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Instances
  /?Action=UpdateContainerAgent:
    get:
      summary: Update Container Agent
      description: Updates the Amazon ECS container agent on a specified container
        instance.
      operationId: updateContainerAgent
      x-api-path-slug: actionupdatecontaineragent-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that your container instance is            running on
        type: string
      - in: query
        name: containerInstance
        description: The container instance ID or full Amazon Resource Name (ARN)
          entries for the container instance on            which you would like to
          update the Amazon ECS container agent
        type: string
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Agents
  /?Action=DiscoverPollEndpoint:
    get:
      summary: Discover Poll Endpoint
      description: This action is only used by the Amazon EC2 Container Service agent,
        and it is not intended for use outside of the agent.
      operationId: discoverPollEndpoint
      x-api-path-slug: actiondiscoverpollendpoint-get
      responses:
        200:
          description: OK
      tags:
      - Poll Endpoints
  /?Action=SubmitContainerStateChange:
    get:
      summary: Submit Container State Change
      description: This action is only used by the Amazon EC2 Container Service agent,
        and it is not intended for use outside of the agent.
      operationId: submitContainerStateChange
      x-api-path-slug: actionsubmitcontainerstatechange-get
      responses:
        200:
          description: OK
      tags:
      - Container State Change
  /?Action=SubmitTaskStateChange:
    get:
      summary: Submit Task State Change
      description: This action is only used by the Amazon EC2 Container Service agent,
        and it is not intended for use outside of the agent.
      operationId: submitTaskStateChange
      x-api-path-slug: actionsubmittaskstatechange-get
      responses:
        200:
          description: OK
      tags:
      - Task State Change
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