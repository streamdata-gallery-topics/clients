---
swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 0
info:
  title: IDX Broker Get Partners Clients
  description: A list of clients available to a given partner. The list of clients
    can be filtered by GET values.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /partners/clients:
    get:
      summary: Get Partners Clients
      description: A list of clients available to a given partner. The list of clients
        can be filtered by GET values.
      operationId: PartnersClientsGet
      x-api-path-slug: partnersclients-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Partners
      - Clients
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