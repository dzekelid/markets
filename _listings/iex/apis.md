---
name: IEX
x-slug: iex
description: IEX, the Investors Exchange, is a fair, simple and transparent stock
  exchange dedicated to investor and issuer protection.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
x-kinRank: "9"
x-alexaRank: "166667"
tags: Markets
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/markets/master/_listings/iex/apis.md
specificationVersion: "0.14"
apis:
- name: IEX Trading API Market
  x-api-slug: iex-trading-api
  description: This endpoint returns near real time traded volume on the markets.
    Market data is captured by the IEX system from approximately 7:45 a.m. to 5:15
    p.m. ET.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
  humanURL: https://iextrading.com
  baseURL: https://api.iextrading.com//1.0//market
  tags: Market Data,Markets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/markets/master/_listings/iex/market-get-openapi.md
- name: IEX Trading API
  x-api-slug: iex-trading-api
  description: IEX, the Investors Exchange, is a fair, simple and transparent stock
    exchange dedicated to investor and issuer protection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28093-iex.jpg
  humanURL: https://iextrading.com
  baseURL: https://api.iextrading.com//1.0
  tags: Markets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/markets/master/_listings/iex/openapi.md
x-common:
- type: x-authentication
  url: https://iextrading.com/developer/docs/#authentication
- type: x-blog
  url: https://medium.com/boxes-and-lines
- type: x-blog-rss
  url: view-source:https://medium.com/feed/boxes-and-lines
- type: x-branding
  url: https://iextrading.com/brand/
- type: x-change-log
  url: https://iextrading.com/developer/docs/#changelog
- type: x-crunchbase
  url: https://crunchbase.com/organization/iex
- type: x-developer
  url: https://iextrading.com/developer/docs/
- type: x-email
  url: sales@iextrading.com
- type: x-email
  url: listings@iextrading.com
- type: x-email
  url: marketops@iextrading.com
- type: x-email
  url: sre@iextrading.com
- type: x-email
  url: marcomms@iextrading.com
- type: x-email
  url: info@iextrading.com
- type: x-email
  url: api@iextrading.com
- type: x-email
  url: legal@iextrading.com
- type: x-email
  url: ventures@iextrading.com
- type: x-faq
  url: https://iextrading.com/faq/
- type: x-github
  url: https://github.com/iexg
- type: x-linkedin
  url: https://www.linkedin.com/company/iex-group-inc-
- type: x-press
  url: https://iextrading.com/about/press/
- type: x-road-map
  url: https://iextrading.com/developer/docs/#roadmap
- type: x-terms-of-service
  url: https://iextrading.com/developer/docs/#terms
- type: x-twitter
  url: https://twitter.com/IEX
- type: x-website
  url: https://iextrading.com
- type: x-websockets
  url: https://iextrading.com/developer/docs/#websockets
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---