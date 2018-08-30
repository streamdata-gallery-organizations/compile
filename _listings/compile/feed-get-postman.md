{
  "info": {
    "name": "Compile Get Feed",
    "_postman_id": "6bd6f84e-a9ca-4a7c-81d2-cbe04cb4beb3",
    "description": "Get feed.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Detail",
      "item": [
        {
          "id": "a1d70847-3385-4404-b60f-eba59929ca77",
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
              "id": "7107a06b-36c4-4e3f-9f5f-9fcad9beb01d"
            }
          ]
        }
      ]
    },
    {
      "name": "SEC",
      "item": [
        {
          "id": "c66e7193-5052-47f9-b978-00c8e20c339a",
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
              "id": "32d4aecd-7c95-4739-9f65-cefb097139c1"
            }
          ]
        }
      ]
    },
    {
      "name": "Feed",
      "item": [
        {
          "id": "a7a92900-5758-4236-a14b-47c1fa7a2a62",
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
              "id": "dc277cd3-ac80-449a-9f32-254fc2266cde"
            }
          ]
        }
      ]
    }
  ]
}