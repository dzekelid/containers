{
  "info": {
    "name": "Azure Container Registry API Registries List By Resource Group",
    "_postman_id": "fa4431f8-ea8d-45d0-904d-7443a63c234e",
    "description": "Lists all the container registries under the specified resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "containers",
      "item": [
        {
          "id": "af280744-1b40-4530-9040-84d013b3b27e",
          "name": "Registries_ListByResourceGroup",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ContainerRegistry/registries"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all the container registries under the specified resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "467ce1c1-d65b-4c1e-93df-abd73fee6f30"
            }
          ]
        }
      ]
    }
  ]
}