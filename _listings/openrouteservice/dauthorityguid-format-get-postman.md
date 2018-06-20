{
  "info": {
    "name": "AP Metadata Services Authority",
    "_postman_id": "25ad68c5-1231-470e-a1e1-9f61258c6c81",
    "description": "Returns a document for the specified authority and format with the AP vocabulary data for the  specified term GUID and the subset of the vocabulary located below the specified term.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Change",
      "item": [
        {
          "id": "26d3adc1-ac13-4637-897c-766c2ae39293",
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
              "id": "98a98c0b-6ea0-4ede-a2cf-2f2243c2bd91"
            }
          ]
        }
      ]
    },
    {
      "name": "Ontology",
      "item": [
        {
          "id": "04e48e82-6f21-4101-acb7-e3128dd55b6c",
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
              "id": "f0838a17-787c-4f06-9a2a-bc5c6f3493bc"
            }
          ]
        }
      ]
    },
    {
      "name": "DeprecatedCompany",
      "item": [
        {
          "id": "340ab68d-3e29-49cc-bf2d-f59f914e53ca",
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
              "id": "221daab6-2ac5-46ff-bedf-670e010ec511"
            }
          ]
        }
      ]
    },
    {
      "name": "Deprecated",
      "item": [
        {
          "id": "6460dae0-bf71-420b-a98a-071b8173d817",
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
              "id": "4d36e792-5812-4703-8a24-5403c108f6be"
            }
          ]
        }
      ]
    },
    {
      "name": "Taxonomy",
      "item": [
        {
          "id": "221d6a08-c9c1-4bc0-a4af-52f337c49954",
          "name": "getDAuthority.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "cv.ap.org",
              "path": [
                "d/:authority.json"
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
                  "id": "authority",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the taxonomy information for the specified authority and the specified format."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e42ab322-5fd6-4255-83c9-7652c2bea277"
            }
          ]
        }
      ]
    },
    {
      "name": "Authority",
      "item": [
        {
          "id": "120b84d5-7f1b-4d2a-94e1-b2c2961f2ee7",
          "name": "getDAuthorityGu.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "cv.ap.org",
              "path": [
                "d/:authority/:GUID.json"
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
                  "id": "authority",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "GUID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a document for the specified authority and format with the AP vocabulary data for the  specified term GUID and the subset of the vocabulary located below the specified term."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b83dc8d0-4202-447b-9e1f-dc8ef6ee2ca9"
            }
          ]
        }
      ]
    }
  ]
}