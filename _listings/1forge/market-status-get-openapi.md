---
swagger: "2.0"
x-collection-name: 1Forge
x-complete: 0
info:
  title: 1Forge Financial Market Status API
  description: Checks to see if a financial market is open or not.
  version: 1.0.0
host: forex.1forge.com
basePath: 1.0.3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /market_status:
    get:
      summary: Financial Market Status API
      description: Checks to see if a financial market is open or not.
      operationId: marketStatus
      x-api-path-slug: market-status-get
      parameters:
      - in: query
        name: api_key
        description: The api key
        type: string
        format: string
      - in: query
        name: format
        description: The format to return
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Markets
      - Status
x-streamrank:
  polling_total_time_average: "0.59"
  polling_size_download_average: "160.57"
  streaming_total_time_average: "0.41"
  streaming_size_download_average: "86.03"
  change_yes: "6"
  change_no: "1786"
  time_percentage: "30"
  size_percentage: "46"
  change_percentage: "0"
  last_run: "2018-02-20"
  days_run: "1"
  minute_run: "0"
---