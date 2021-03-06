swagger: "2.0"
x-collection-name: Compile
x-complete: 1
info:
  title: Compile API v1
  description: full-documentation-available-at-httpsv1-compileapi-comdocs
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
  /filings/{org_id}/:
    get:
      summary: Get SEC Filings
      description: Get sec filings.
      operationId: FilingsByOrgIdGet
      x-api-path-slug: filingsorg-id-get
      parameters:
      - in: header
        name: apikey
      - in: path
        name: org_id
      responses:
        200:
          description: OK
      tags:
      - SEC
      - Filings
  /feed/:
    get:
      summary: Get Feed
      description: Get feed.
      operationId: FeedGet
      x-api-path-slug: feed-get
      parameters:
      - in: header
        name: apikey
      responses:
        200:
          description: OK
      tags:
      - Feed
  /organizations/:
    get:
      summary: Get Listing
      description: Get listing.
      operationId: OrganizationsGet
      x-api-path-slug: organizations-get
      parameters:
      - in: header
        name: apikey
      responses:
        200:
          description: OK
      tags:
      - Listing
  /alerts/{org_id}/:
    get:
      summary: Get Alerts
      description: Get alerts.
      operationId: AlertsByOrgIdGet
      x-api-path-slug: alertsorg-id-get
      parameters:
      - in: header
        name: apikey
      - in: path
        name: org_id
      responses:
        200:
          description: OK
      tags:
      - Alerts
  /installs/{org_id}/:
    get:
      summary: Get Technology installs
      description: Get technology installs.
      operationId: InstallsByOrgIdGet
      x-api-path-slug: installsorg-id-get
      parameters:
      - in: header
        name: apikey
      - in: path
        name: org_id
      responses:
        200:
          description: OK
      tags:
      - Technology
      - Installs