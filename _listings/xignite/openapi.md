---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Logos
  description: this-web-service-provides-company-logo-images
  version: 1.0.0
host: www.xignite.com
basePath: xLogos.json/XigniteLogos
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListMarkets:
    post:
      summary: List Markets
      description: List markets which have avalilable logos.
      operationId: postListmarkets
      x-api-path-slug: listmarkets-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Markets
---