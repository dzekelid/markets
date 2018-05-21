---
swagger: "2.0"
x-collection-name: IEX
x-complete: 0
info:
  title: IEX Trading API Market
  description: This endpoint returns near real time traded volume on the markets.
    Market data is captured by the IEX system from approximately 7:45 a.m. to 5:15
    p.m. ET.
  termsOfService: https://iextrading.com/api-terms/
  version: 1.0.0
host: api.iextrading.com
basePath: /1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /market:
    get:
      summary: Market
      description: This endpoint returns near real time traded volume on the markets.
        Market data is captured by the IEX system from approximately 7:45 a.m. to
        5:15 p.m. ET.
      operationId: market
      x-api-path-slug: market-get
      parameters:
      - in: query
        name: format
        description: ' Parameter is optional Value can only be csv When parameter
          is not present, format defaults to JSON'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Markets
x-streamrank:
  polling_total_time_average: "0.15"
  polling_size_download_average: "2233"
  streaming_total_time_average: "0.08"
  streaming_size_download_average: "1116.8"
  change_yes: "2"
  change_no: "3747"
  time_percentage: "45"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-02-19"
  days_run: "3"
  minute_run: "0"
---