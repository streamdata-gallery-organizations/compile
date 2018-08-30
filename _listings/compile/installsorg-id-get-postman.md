{
  "info": {
    "name": "Compile Get Technology installs",
    "_postman_id": "f4a25cf4-2c5e-46c2-b6c0-8b1b3114b435",
    "description": "Get technology installs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Detail",
      "item": [
        {
          "id": "92dda98e-9ae4-4360-9582-2e7c8bdba39e",
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
              "id": "36eb6853-7f4a-4624-ae0b-2b609d262448"
            }
          ]
        }
      ]
    },
    {
      "name": "SEC",
      "item": [
        {
          "id": "409f7377-1dfd-4fc1-b03e-ba2e9e6172de",
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
              "id": "54e9211c-fac9-476e-86eb-8f271ea67421"
            }
          ]
        }
      ]
    },
    {
      "name": "Feed",
      "item": [
        {
          "id": "018da20e-3f87-485f-9d4b-db6a0189478d",
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
              "id": "427b61f8-074c-49f5-8798-34726717857e"
            }
          ]
        }
      ]
    },
    {
      "name": "Listing",
      "item": [
        {
          "id": "c75749d7-4969-4158-af48-c6af5d49eb55",
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
              "id": "e5b4908a-d68f-4143-afa0-41171b4afa47"
            }
          ]
        }
      ]
    },
    {
      "name": "Alerts",
      "item": [
        {
          "id": "78a1273f-95bb-43f9-bc4f-cf4058b168d2",
          "name": "AlertsByOrgIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "v1.compileapi.com",
              "path": [
                "organization",
                "alerts/:org_id/"
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
            "description": "Get alerts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e6ed4a1-6671-472c-8d57-cb465e098455"
            }
          ]
        }
      ]
    },
    {
      "name": "Technology",
      "item": [
        {
          "id": "72aabc62-b616-453f-ae07-466074937212",
          "name": "InstallsByOrgIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "v1.compileapi.com",
              "path": [
                "organization",
                "installs/:org_id/"
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
            "description": "Get technology installs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ccc5b58-cb74-429b-b01c-322cc548db0e"
            }
          ]
        }
      ]
    }
  ]
}