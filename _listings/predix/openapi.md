swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /instances/{instanceId}/appattempts/{attemptId}/containers:
    get:
      summary: Get Instances Instanceid Appattempts Attemptid Containers
      description: Get instances instanceid appattempts attemptid containers.
      operationId: getInstanceAttemptContainersUsingGET
      x-api-path-slug: instancesinstanceidappattemptsattemptidcontainers-get
      parameters:
      - in: path
        name: attemptId
        description: attemptId
      - in: path
        name: instanceId
        description: instanceId
      responses:
        200:
          description: Successful response
      tags:
      - Instances
      - Instanceid
      - Appattempts
      - Attemptid
      - Containers
  /instances/{instanceId}/containers:
    get:
      summary: Get Instances Instanceid Containers
      description: Get instances instanceid containers.
      operationId: getInstanceContainersUsingGET
      x-api-path-slug: instancesinstanceidcontainers-get
      parameters:
      - in: path
        name: instanceId
        description: instanceId
      responses:
        200:
          description: Successful response
      tags:
      - Instances
      - Instanceid
      - Containers
  /instances/{instanceId}/containers/{containerId}/logs:
    get:
      summary: Get Instances Instanceid Containers Containerid Logs
      description: Get instances instanceid containers containerid logs.
      operationId: getInstanceContainerLogsUsingGET
      x-api-path-slug: instancesinstanceidcontainerscontaineridlogs-get
      parameters:
      - in: path
        name: containerId
        description: containerId
      - in: path
        name: instanceId
        description: instanceId
      responses:
        200:
          description: Successful response
      tags:
      - Instances
      - Instanceid
      - Containers
      - Containerid
      - Logs
  /instances/{instanceId}/containers/{containerId}/logs/{logName}:
    get:
      summary: Get Instances Instanceid Containers Containerid Logs Logname
      description: Get instances instanceid containers containerid logs logname.
      operationId: getInstanceContainerLogContentsUsingGET
      x-api-path-slug: instancesinstanceidcontainerscontaineridlogslogname-get
      parameters:
      - in: path
        name: containerId
        description: containerId
      - in: path
        name: instanceId
        description: instanceId
      - in: query
        name: length
        description: length
      - in: path
        name: logName
        description: logName
      - in: query
        name: offset
        description: offset
      responses:
        200:
          description: Successful response
      tags:
      - Instances
      - Instanceid
      - Containers
      - Containerid
      - Logs
      - Logname