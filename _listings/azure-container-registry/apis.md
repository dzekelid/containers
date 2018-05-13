---
name: Azure Container Registry
description: Azure Container Registry allows you to store images for all types of
  container deployments including DC/OS, Docker Swarm, Kubernetes, and Azure services
  such as App Service, Batch, Service Fabric, and others. Your DevOps team can manage
  the configuration of apps isolated from the configuration of the hosting environment.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Microsoft
- Containers
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure Container Registry API
  description: Azure Container Registry allows you to store images for all types of
    container deployments including DC/OS, Docker Swarm, Kubernetes, and Azure services
    such as App Service, Batch, Service Fabric, and others
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Containers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-containerregistry-registries-registryname-regeneratecredential-post.md
- name: Azure Container Registry API Registries List
  description: Lists all the container registries under the specified subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: http:://management.azure.com//
  tags: Containers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptions-subscriptionid-providers-microsoft-containerregistry-registries-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptions-subscriptionid-providers-microsoft-containerregistry-registries-get-postman.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/container-registry/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/container-registry/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/container-registry/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/container-registry/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/container-registry/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/container-registry/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/container-registry/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/container-registry/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---