{
  "info": {
    "name": "Azure Data Lake Analytics API Storage Accounts List Storage Containers",
    "_postman_id": "46305ce3-82c4-4753-8753-be2e0355e911",
    "description": "Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination. The response includes a link to the next page of results, if any.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "stage account stage containers",
      "item": [
        {
          "id": "f40234c1-afad-4190-9ca4-4b0dd3f8d1e1",
          "name": "StorageAccounts_ListStorageContainers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.DataLakeAnalytics/accounts/:accountName/StorageAccounts/:storageAccountName/Containers"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "storageAccountName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f27090d9-db5a-4034-8737-fa04d13b7cf7"
            }
          ]
        }
      ]
    }
  ]
}