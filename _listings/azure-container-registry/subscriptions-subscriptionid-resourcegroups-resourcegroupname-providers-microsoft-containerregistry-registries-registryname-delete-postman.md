{
  "info": {
    "name": "Azure Container Registry API Registries Delete",
    "_postman_id": "03c4fca9-3c3a-4f5f-a354-e2f41f65a63b",
    "description": "Deletes a container registry.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "containers",
      "item": [
        {
          "id": "47d1583c-bd84-464f-bf76-297326acf854",
          "name": "Registries_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a container registry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31678c67-7e8c-4cb3-8356-46a095b99c1d"
            }
          ]
        }
      ]
    }
  ]
}