---
swagger: "2.0"
x-collection-name: IEX
x-complete: 1
info:
  title: IEX
  description: the-iex-api-is-a-set-of-services-designed-for-developers-and-engineers--it-can-be-used-to-build-highquality-apps-and-services--were-always-working-to-improve-the-iex-api--please-check-back-for-enhancements-and-improvements-
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
        description: Parameter is optional Value can only be csv When parameter is
          not present, format defaults to JSON
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Markets
---