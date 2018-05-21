---
name: Xignite
x-slug: xignite
description: Financial market data on-demand. Xignite financial Web services help
  build smarter websites and applications in minutes with zero up-front investment.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
x-kinRank: "9"
x-alexaRank: "383974"
tags: Prices
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/apis.md
specificationVersion: "0.14"
apis:
- name: Xignite Bonds Get Daily Open High Low Close Prices
  x-api-slug: xignite-bonds
  description: Returns daily Open, High, Low, Close (OHLC) prices for the list of
    bonds specified in the input. Daily OHLC data is provided for the most recent
    date for which data is provided by the price source. Each DailyOpenHighLowClosePrice
    object  returned counts as one hit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://bonds.xignite.com/xBonds.json/XigniteBonds//GetDailyOpenHighLowClosePrices
  tags: Daily, Open, High, Low, Close, Prices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/getdailyopenhighlowcloseprices-post-openapi.md
- name: Xignite Bonds Get Yearly High Low Prices
  x-api-slug: xignite-bonds
  description: Returns yearly high, low prices for the list of bonds specified in
    the input, as reported by the price source selected in the input. Each YearlyHighLowPrice
    object returned counts as one hit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://bonds.xignite.com/xBonds.json/XigniteBonds//GetYearlyHighLowPrices
  tags: Yearly, High, Low, Prices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/getyearlyhighlowprices-post-openapi.md
- name: Xignite Bonds
  x-api-slug: xignite-bonds
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://bonds.xignite.com/xBonds.json/XigniteBonds
  tags: Prices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/openapi.md
- name: Xignite Global Historical Get Global Last Closing Prices
  x-api-slug: xignite-global-historical
  description: Returns last closing price for a collection of securities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical//GetGlobalLastClosingPrices
  tags: Global, Last, Closing, Prices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/getgloballastclosingprices-post-openapi.md
- name: Xignite Global Historical
  x-api-slug: xignite-global-historical
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xGlobalHistorical.json/XigniteGlobalHistorical
  tags: Prices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/openapi.md
- name: Xignite Historical Get Last Closing Prices
  x-api-slug: xignite-historical
  description: Returns last closing price for a collection of securities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetLastClosingPrices
  tags: Last, Closing, Prices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/getlastclosingprices-post-openapi.md
- name: Xignite Historical Get Last Closing Prices Adjusted
  x-api-slug: xignite-historical
  description: Returns last closing price for a collection of securities.This include
    the splits and dividends adjusted price
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetLastClosingPricesAdjusted
  tags: Last, Closing, Prices, Adjusted
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/getlastclosingpricesadjusted-post-openapi.md
- name: Xignite Historical Get Last Closing Prices Ordered
  x-api-slug: xignite-historical
  description: Returns last closing price for a collection of securities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetLastClosingPricesOrdered
  tags: Last, Closing, Prices, Ordered
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/getlastclosingpricesordered-post-openapi.md
- name: Xignite Historical Get Last Closing Prices Ordered Adjusted
  x-api-slug: xignite-historical
  description: Returns last closing price for a collection of securities.This include
    the splits and dividends adjusted price
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical//GetLastClosingPricesOrderedAdjusted
  tags: Last, Closing, Prices, Ordered, Adjusted
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/getlastclosingpricesorderedadjusted-post-openapi.md
- name: Xignite Historical
  x-api-slug: xignite-historical
  description: Financial market data on-demand. Xignite financial Web services help
    build smarter websites and applications in minutes with zero up-front investment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/xignite-logo.png
  humanURL: http://www.xignite.com
  baseURL: https://www.xignite.com/xHistorical.json/XigniteHistorical
  tags: Prices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/prices/master/_listings/xignite/openapi.md
x-common:
- type: x-net-sdk
  url: http://xignite.github.io/DotNetSDK/
- type: x-base
  url: http://globalmaster.xignite.com
- type: x-case-studies
  url: https://resources.xignite.com/case-studies
- type: x-case-studies
  url: http://www.xignite.com/market-data/resources/case-studies/
- type: x-blog
  url: https://resources.xignite.com/xignite-blog
- type: x-contact-form
  url: http://www.xignite.com/market-data/contact-us
- type: x-crunchbase
  url: http://www.crunchbase.com/company/xignite
- type: x-crunchbase
  url: https://crunchbase.com/organization/xignite
- type: x-developer
  url: http://www.xignite.com/developers
- type: x-email
  url: support@xignite.com
- type: x-email
  url: accounting@xignite.com
- type: x-email
  url: sales@xignite.com
- type: x-email
  url: marketing@xignite.com
- type: x-email
  url: info@xignite.com
- type: x-email
  url: jobs@xignite.com
- type: x-email
  url: klangstaff@xignite.com
- type: x-faq
  url: http://www.xignite.com/Support/FAQs.aspx
- type: x-getting-started
  url: http://www.xignite.com/Support/GettingStarted.aspx
- type: x-github
  url: https://github.com/Xignite
- type: x-java-sdk
  url: http://xignite.github.io/JavaSDK/
- type: x-privacy
  url: http://www.xignite.com/Documents/PrivacyPolicy.aspx
- type: x-support
  url: http://www.xignite.com/Support/SupportPlans.aspx
- type: x-blog
  url: http://www.xignite.com/market-data/blog/tech/
- type: x-blog-rss
  url: http://www.xignite.com/market-data/feed/
- type: x-terms-of-service
  url: http://www.xignite.com/Policies/SiteUseTerms.aspx
- type: x-twitter
  url: https://twitter.com/xignite
- type: x-videos
  url: http://www.xignite.com/market-data/resources/videos/
- type: x-webinar
  url: http://www.xignite.com/market-data/resources/webinars/
- type: x-webinars
  url: https://resources.xignite.com/webinars
- type: x-website
  url: http://www.xignite.com
- type: x-white-papers
  url: http://www.xignite.com/market-data/resources/white-papers/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---