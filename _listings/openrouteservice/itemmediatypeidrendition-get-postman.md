{
  "info": {
    "name": "AP Content API Get Item Mediatype Rendition",
    "_postman_id": "01d1d279-98bd-4eb0-9e3a-21a9297ca448",
    "description": "Pulls item media",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Item",
      "item": [
        {
          "id": "90c4faa2-a74e-4dad-a0b8-0ee69650cd12",
          "name": "getItemMediatypeRendition",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ap.org",
              "path": [
                "v2",
                "item/:mediaType/:id/:rendition"
              ],
              "query": [
                {
                  "key": "apiKey",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "filename",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaType",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "rendition",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Pulls item media"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b906528-fe11-48ca-bce4-aae0f44a96fe"
            }
          ]
        }
      ]
    }
  ]
}