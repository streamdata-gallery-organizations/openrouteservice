{
  "info": {
    "name": "AP Metadata Services Deprecated Terms",
    "_postman_id": "d99833f6-d8a8-4afe-856d-ee9568735e20",
    "description": "Returns a list of deprecated AP vocabulary terms in the specified format for the AP Company authority  or for the other four AP authorities.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Change",
      "item": [
        {
          "id": "e25e7eed-6123-4f07-998c-46eb0ed4e4c8",
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
              "id": "bc52822b-1e36-4ea4-b8e9-58258e2b83d6"
            }
          ]
        }
      ]
    },
    {
      "name": "Ontology",
      "item": [
        {
          "id": "2e4d9c96-49b6-46da-990f-a7d90b71161d",
          "name": "getCClass.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "cv.ap.org",
              "path": [
                "c/:class.json"
              ],
              "query": [
                {
                  "key": "apikey",
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
                  "id": "class",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the AP ontology definition for the specified AP property or class and the specified format."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b00f66d-e093-4a02-9d36-e101ea6578c6"
            }
          ]
        }
      ]
    },
    {
      "name": "DeprecatedCompany",
      "item": [
        {
          "id": "f49b4534-146b-4e15-a810-a495b851158f",
          "name": "getDDeprecatedcompany.Format",
          "request": {
            "url": "http://cv.ap.org/d/DeprecatedCompany.json?apiKey=%7B%7D&format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of deprecated AP vocabulary terms in the specified format for the AP Company authority  or for the other four AP authorities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc39413d-be95-4460-88b3-6f22938b6340"
            }
          ]
        }
      ]
    },
    {
      "name": "Deprecated",
      "item": [
        {
          "id": "e6fa4e9e-9f32-4c6f-ac52-f54ac187c898",
          "name": "getDDeprecatedterm.Format",
          "request": {
            "url": "http://cv.ap.org/d/DeprecatedTerm.json?apiKey=%7B%7D&format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of deprecated AP vocabulary terms in the specified format for the AP Company authority  or for the other four AP authorities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "750cebc6-6899-432e-95f1-dab8c3e9cad4"
            }
          ]
        }
      ]
    }
  ]
}