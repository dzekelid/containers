{
  "info": {
    "name": "Azure Container Registry API Registries List Credentials",
    "_postman_id": "0d0d0299-936b-4475-b47f-385859109bfb",
    "description": "Lists the login credentials for the specified container registry.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "containers",
      "item": [
        {
          "id": "1cd9a6f0-e747-4448-b053-bdf94a41dc8b",
          "name": "Registries_ListCredentials",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ContainerRegistry/registries/:registryName/listCredentials"
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
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "registryName",
                  "value": "registryName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the login credentials for the specified container registry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f65934db-fc31-42ed-98da-7fcdb6759d5e"
            }
          ]
        }
      ]
    }
  ]
}