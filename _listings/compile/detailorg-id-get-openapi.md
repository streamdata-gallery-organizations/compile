---
swagger: "2.0"
x-collection-name: Compile
x-complete: 0
info:
  title: Compile Get Detail
  description: Get detail.
  version: 1.0.0
host: v1.compileapi.com
basePath: /organization
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /detail/{org_id}/:
    get:
      summary: Get Detail
      description: Get detail.
      operationId: DetailByOrgIdGet
      x-api-path-slug: detailorg-id-get
      parameters:
      - in: header
        name: apikey
      - in: path
        name: org_id
      responses:
        200:
          description: OK
      tags:
      - Detail
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---