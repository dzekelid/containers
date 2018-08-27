{
  "info": {
    "name": "Azure Data Lake Analytics API Storage Accounts Get Storage Container",
    "_postman_id": "62dd14d7-3e3a-438d-99c6-77da50cf9a63",
    "description": "Gets the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "containers",
      "item": [
        {
          "id": "57785bd8-173d-4858-b968-119aa41803fc",
          "name": "StorageAccounts_GetStorageContainer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.DataLakeAnalytics/accounts/:accountName/StorageAccounts/:storageAccountName/Containers/:containerName"
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
                  "id": "containerName",
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
            "description": "Gets the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5296d940-adb2-44bc-b784-29f62d516d9f"
            }
          ]
        }
      ]
    }
  ]
}