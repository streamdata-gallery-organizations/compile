{
  "info": {
    "name": "Compile Get SEC Filings",
    "_postman_id": "30476f28-202e-4670-870e-bd3b0ac9c589",
    "description": "Get sec filings.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Detail",
      "item": [
        {
          "id": "a5468e94-d049-422a-9ee0-9bf6e97d9f28",
          "name": "DetailByOrgIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "v1.compileapi.com",
              "path": [
                "organization",
                "detail/:org_id/"
              ],
              "variable": [
                {
                  "id": "org_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "apikey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get detail."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41a3f0a6-1ee7-40c3-ae18-3deb929f8d19"
            }
          ]
        }
      ]
    },
    {
      "name": "SEC",
      "item": [
        {
          "id": "0decf7ba-57a9-4a0d-a279-c8724007baf9",
          "name": "FilingsByOrgIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "v1.compileapi.com",
              "path": [
                "organization",
                "filings/:org_id/"
              ],
              "variable": [
                {
                  "id": "org_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "apikey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get sec filings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "369f3bbd-97c2-461f-955b-6996ce29ca2a"
            }
          ]
        }
      ]
    }
  ]
}