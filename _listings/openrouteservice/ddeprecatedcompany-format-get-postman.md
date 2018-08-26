{
  "info": {
    "name": "AP Metadata Services DeprecatedCompany",
    "_postman_id": "bf42f2c9-dff5-4cc8-8e2a-f3e45584da5e",
    "description": "Returns a list of deprecated AP vocabulary terms in the specified format for the AP Company authority  or for the other four AP authorities.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Change",
      "item": [
        {
          "id": "c83ec911-aa6b-4502-b0c1-b363aecfd742",
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
              "id": "5e6b1608-fbac-4a32-b2e4-3a10ac14a414"
            }
          ]
        }
      ]
    },
    {
      "name": "Ontology",
      "item": [
        {
          "id": "e96c83d7-dde7-4912-b47b-c32e1dd34687",
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
              "id": "03095ee9-5226-4b11-bef3-d8f3506e8e96"
            }
          ]
        }
      ]
    },
    {
      "name": "DeprecatedCompany",
      "item": [
        {
          "id": "5eafe3e6-33cb-4cbc-afdd-70109b856c56",
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
              "id": "0127b3e4-2ae9-4e50-b813-c46b53ceab65"
            }
          ]
        }
      ]
    }
  ]
}