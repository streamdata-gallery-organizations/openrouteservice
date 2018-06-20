{
  "info": {
    "name": "AP Metadata Services Change Log",
    "_postman_id": "ab935c85-6fc9-41fd-86f9-91568f457360",
    "description": "Returns a list of changes to the AP vocabulary terms according to the specified criteria.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Change",
      "item": [
        {
          "id": "c3c16403-69b2-46d8-bbef-91daced7ce99",
          "name": "getApiCm",
          "request": {
            "url": "http://cv.ap.org/api/cm/?apiKey=%7B%7D&authority=%7B%7D&enddate=%7B%7D&format=%7B%7D&lastversion=%7B%7D&startdate=%7B%7D&version=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of changes to the AP vocabulary terms according to the specified criteria."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d8629c4-85e5-470e-842c-4673cd570cca"
            }
          ]
        }
      ]
    }
  ]
}