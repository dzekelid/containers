{
  "info": {
    "name": "Azure Container Registry API Registries Get",
    "_postman_id": "4c9ff809-e18a-4d80-a769-8ad4f72450dc",
    "description": "Gets the properties of the specified container registry.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "containers",
      "item": [
        {
          "id": "293d4120-ac8e-4ce6-b2af-568e25d11ccc",
          "name": "Registries_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ContainerRegistry/registries/:registryName"
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the properties of the specified container registry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a864e7cd-f60f-47a6-8da0-9e56cfd9271e"
            }
          ]
        }
      ]
    }
  ]
}