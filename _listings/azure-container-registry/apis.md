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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Container Registry API Registries Check Name Availability
  x-api-slug: azure-container-registry-api
  description: Checks whether the container registry name is available for use. The
    name must contain only alphanumeric characters, be globally unique, and between
    5 and 60 characters in length.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ContainerRegistry/checkNameAvailability
  tags: Containers,Registries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidprovidersmicrosoft-containerregistrychecknameavailability-post-openapi.md
- name: Azure Container Registry API Registries Get
  x-api-slug: azure-container-registry-api
  description: Gets the properties of the specified container registry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries/{registryName}
  tags: Containers,Registries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-get-openapi.md
- name: Azure Container Registry API Registries Create
  x-api-slug: azure-container-registry-api
  description: Creates a container registry with the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries/{registryName}
  tags: Containers,Registries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-put-openapi.md
- name: Azure Container Registry API Registries Delete
  x-api-slug: azure-container-registry-api
  description: Deletes a container registry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries/{registryName}
  tags: Containers,Registries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-delete-openapi.md
- name: Azure Container Registry API Registries Update
  x-api-slug: azure-container-registry-api
  description: Updates a container registry with the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries/{registryName}
  tags: Containers,Registries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistryname-patch-openapi.md
- name: Azure Container Registry API Registries List By Resource Group
  x-api-slug: azure-container-registry-api
  description: Lists all the container registries under the specified resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries
  tags: Containers,Registries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistries-get-openapi.md
- name: Azure Container Registry API Registries List
  x-api-slug: azure-container-registry-api
  description: Lists all the container registries under the specified subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ContainerRegistry/registries
  tags: Containers,Registries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidprovidersmicrosoft-containerregistryregistries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidprovidersmicrosoft-containerregistryregistries-get-openapi.md
- name: Azure Container Registry API Registries List Credentials
  x-api-slug: azure-container-registry-api
  description: Lists the login credentials for the specified container registry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries/{registryName}/listCredentials
  tags: Containers,Registries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistrynamelistcredentials-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistrynamelistcredentials-post-openapi.md
- name: Azure Container Registry API Registries Regenerate Credential
  x-api-slug: azure-container-registry-api
  description: Regenerates one of the login credentials for the specified container
    registry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerRegistry/registries/{registryName}/regenerateCredential
  tags: Containers,Registries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerregistryregistriesregistrynameregeneratecredential-post-openapi.md
- name: Azure Container Registry API
  x-api-slug: azure-container-registry-api
  description: Azure Container Registry allows you to store images for all types of
    container deployments including DC/OS, Docker Swarm, Kubernetes, and Azure services
    such as App Service, Batch, Service Fabric, and others. Your DevOps team can manage
    the configuration of apps isolated from the configuration of the hosting environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-manage-containers.png
  humanURL: https://azure.microsoft.com/en-us/services/container-registry/
  baseURL: ://management.azure.com//
  tags: Containers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/containers/master/_listings/azure-container-registry/openapi.md
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
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---