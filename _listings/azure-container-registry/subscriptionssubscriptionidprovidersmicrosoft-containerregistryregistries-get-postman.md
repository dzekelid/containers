{
  "info": {
    "name": "Azure Container Registry API Registries List",
    "_postman_id": "15ba2380-551c-4a87-9b5a-6be81334ac3c",
    "description": "Lists all the container registries under the specified subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "containers",
      "item": [
        {
          "id": "af9f1294-0550-4c64-83dd-d6825b196899",
          "name": "Registries_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.ContainerRegistry/registries"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all the container registries under the specified subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c94bb4c7-0778-4264-aaed-45870965398f"
            }
          ]
        }
      ]
    }
  ]
}