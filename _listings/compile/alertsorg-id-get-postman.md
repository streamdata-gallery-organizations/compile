{
  "info": {
    "name": "Compile Get Alerts",
    "_postman_id": "f3bb1462-7a4c-4608-8643-b781b305bb1d",
    "description": "Get alerts.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Detail",
      "item": [
        {
          "id": "00ff47ed-b611-4fe1-b63d-469659e789e5",
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
              "id": "65c343b4-a166-4cf2-8f3f-04ed27cb9508"
            }
          ]
        }
      ]
    },
    {
      "name": "SEC",
      "item": [
        {
          "id": "25f948a8-df20-434c-bcbe-98c04b155417",
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
              "id": "8da3db04-4fc7-4b40-a2a5-3f4a8c88dcd3"
            }
          ]
        }
      ]
    },
    {
      "name": "Feed",
      "item": [
        {
          "id": "10b06514-6d58-455c-8811-a165cf5851ff",
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
              "id": "f9d96ead-0832-4b23-8ad3-0f9d56e1f912"
            }
          ]
        }
      ]
    },
    {
      "name": "Listing",
      "item": [
        {
          "id": "d00fd06e-98dc-48a8-be2c-079a35b93b26",
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
              "id": "660217c2-b99d-4ac0-baac-7ace1bda51ab"
            }
          ]
        }
      ]
    },
    {
      "name": "Alerts",
      "item": [
        {
          "id": "32b6c9bf-8bcb-4253-8768-25f1c44bd427",
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
              "id": "e5ff9a5e-8544-4dd1-b9ce-b6798c181953"
            }
          ]
        }
      ]
    }
  ]
}