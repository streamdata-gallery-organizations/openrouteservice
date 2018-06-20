{
  "info": {
    "name": "AP Content API Get Item",
    "_postman_id": "b6b6eef3-6a42-4604-bf85-e410369949ee",
    "description": "Get items.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Item",
      "item": [
        {
          "id": "16d193e2-57ab-4ece-92b7-c044ae71d889",
          "name": "getItem",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ap.org",
              "path": [
                "v2",
                "item/:id/"
              ],
              "query": [
                {
                  "key": "apiKey",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4374923d-5e47-471b-85b4-573a0f9421bd"
            }
          ]
        }
      ]
    }
  ]
}