---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 0
info:
  title: Azure Data Lake Analytics API Storage Accounts List Storage Containers
  description: Lists the Azure Storage containers, if any, associated with the specified
    Data Lake Analytics and Azure Storage account combination. The response includes
    a link to the next page of results, if any.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}/Containers/{containerName}
  : get:
      summary: Storage Accounts Get Storage Container
      description: Gets the specified Azure Storage container associated with the
        given Data Lake Analytics and Azure Storage accounts.
      operationId: StorageAccounts_GetStorageContainer
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainername-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account for which to retrieve
          blob container
      - in: path
        name: containerName
        description: The name of the Azure storage container to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure storage account from which to retrieve
          the blob container
      responses:
        200:
          description: OK
      tags:
      - Containers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}/Containers
  : get:
      summary: Storage Accounts List Storage Containers
      description: Lists the Azure Storage containers, if any, associated with the
        specified Data Lake Analytics and Azure Storage account combination. The response
        includes a link to the next page of results, if any.
      operationId: StorageAccounts_ListStorageContainers
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainers-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account for which to list
          Azure Storage blob containers
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure storage account from which to list blob
          containers
      responses:
        200:
          description: OK
      tags:
      - Stage Account Stage Containers
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