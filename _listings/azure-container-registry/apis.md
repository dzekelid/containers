---
name: Azure Container Registry
x-slug: azure-container-registry
description: Azure Container Registry allows you to store images for all types of
  container deployments including DC/OS, Docker Swarm, Kubernetes, and Azure services
  such as App Service, Batch, Service Fabric, and others. Your DevOps team can manage
  the configuration of apps isolated from the configuration of the hosting environment.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Containers
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/apis.md
specificationVersion: "0.14"
apis:
- name: ContainerRegistryManagementClient - Registries Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-get
  description: Gets the properties of the specified container registry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com//
  tags: Microsoft, Containers, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-get-openapi.md
- name: ContainerRegistryManagementClient - Registries Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-delete
  description: Deletes a container registry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com//
  tags: Microsoft, Containers, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-delete-openapi.md
- name: ContainerRegistryManagementClient - Registries List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistries-get
  description: Lists all the container registries under the specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com//
  tags: Microsoft, Containers, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistries-get-openapi.md
- name: ContainerRegistryManagementClient - Registries List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-containerregistryregistries-get
  description: Lists all the container registries under the specified subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com//
  tags: Microsoft, Containers, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidprovidersmicrosoft-containerregistryregistries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidprovidersmicrosoft-containerregistryregistries-get-openapi.md
- name: ContainerRegistryManagementClient - Registries List Credentials
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistrynamelistcredentials-post
  description: Lists the login credentials for the specified container registry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com//
  tags: Microsoft, Containers, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistrynamelistcredentials-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistrynamelistcredentials-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.cognitive.services.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.container.registry.stack.network
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