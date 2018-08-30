{
  "info": {
    "name": "Compile Get Listing",
    "_postman_id": "7e1245bf-d990-485c-a512-babd4d4f61b6",
    "description": "Get listing.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Detail",
      "item": [
        {
          "id": "f5e6e204-9573-430a-b397-d932ed436146",
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
              "id": "f0f09ba3-cf28-40ce-9e8b-76e31452dbc0"
            }
          ]
        }
      ]
    },
    {
      "name": "SEC",
      "item": [
        {
          "id": "676e00b4-3466-48cc-83d3-5c6e66949335",
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
              "id": "37eb2561-ed1f-4d65-801c-c0f7e429aa17"
            }
          ]
        }
      ]
    },
    {
      "name": "Feed",
      "item": [
        {
          "id": "6bd91ce1-a202-44ab-a50a-f4e10ac27e52",
          "name": "FeedGet",
          "request": {
            "url": "http://v1.compileapi.com/organization/feed/",
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
            "description": "Get feed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2611b8a3-a2c0-4e9b-b8ae-9e51dc7dc87c"
            }
          ]
        }
      ]
    },
    {
      "name": "Listing",
      "item": [
        {
          "id": "29939226-fc1d-4085-a908-eb21439cf850",
          "name": "OrganizationsGet",
          "request": {
            "url": "http://v1.compileapi.com/organization/organizations/",
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
            "description": "Get listing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be47b35a-35b3-4a7a-83d8-3e5f246dbdf2"
            }
          ]
        }
      ]
    }
  ]
}