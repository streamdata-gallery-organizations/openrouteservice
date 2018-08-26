{
  "info": {
    "name": "AP Breaking News API Categories",
    "_postman_id": "fea490f4-aba6-4cc0-a231-9f2d5ddc571c",
    "description": "Returns a list of available AP Breaking News categories, including category IDs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Categories",
      "item": [
        {
          "id": "da8b0cb7-ad9a-4b93-aea1-bf3d9c45581d",
          "name": "getCategories.svc",
          "request": {
            "url": "http://developerapi.ap.org/v2/categories.svc/?apiKey=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of available AP Breaking News categories, including category IDs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85469301-0776-4033-8e5c-945f7c293dbe"
            }
          ]
        }
      ]
    }
  ]
}