---
name: Alpha Vantage
x-slug: alpha-vantage
description: Composed of a tight-knit community of researchers, engineers, and business
  professionals, Alpha Vantage Inc. is a leading provider of free APIs for realtime
  and historical data on stocks, physical currencies, and digital/crypto currencies.
  Our success is driven by rigorous research, cutting edge technology, and a disciplined
  focus on democratizing access to data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2018-01-22 at 4.52.35 PM.png
x-kinRank: "8"
x-alexaRank: "160846"
tags: Alpha Vantage
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/apis.md
specificationVersion: "0.14"
apis:
- name: Alpha Vantage Intraday Time Series
  x-api-slug: alpha-vantage
  description: This API returns intraday time series (timestamp, open, high, low,
    close, volume) of the equity specified, updated realtime.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=TIME_SERIES_INTRADAY
  tags: Market Data, Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiontime-series-intraday-get-openapi.md
- name: Alpha Vantage Daily Time Series Adjusted
  x-api-slug: alpha-vantage
  description: This API returns daily time series (date, daily open, daily high, daily
    low, daily close, daily volume, daily adjusted close, and split/dividend events)
    of the equity specified, covering up to 20 years of historical data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=TIME_SERIES_DAILY_ADJUSTED
  tags: Market Data, Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiontime-series-daily-adjusted-get-openapi.md
- name: Alpha Vantage Weekly Time Series
  x-api-slug: alpha-vantage
  description: This API returns weekly time series (last trading day of each week,
    weekly open, weekly high, weekly low, weekly close, weekly volume) of the equity
    specified, covering up to 20 years of historical data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=TIME_SERIES_WEEKLY
  tags: Market Data, Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiontime-series-weekly-get-openapi.md
- name: Alpha Vantage Daily Time Series
  x-api-slug: alpha-vantage
  description: This API returns daily time series (date, daily open, daily high, daily
    low, daily close, daily volume) of the equity specified, covering up to 20 years
    of historical data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=TIME_SERIES_DAILY
  tags: Market Data, Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiontime-series-daily-get-openapi.md
- name: Alpha Vantage Monthly Time Series
  x-api-slug: alpha-vantage
  description: This API returns monthly time series (last trading day of each month,
    monthly open, monthly high, monthly low, monthly close, monthly volume) of the
    equity specified, covering up to 20 years of historical data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=TIME_SERIES_MONTHLY
  tags: Market Data, Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiontime-series-monthly-get-openapi.md
- name: Alpha Vantage Monthly Time Series Adjusted
  x-api-slug: alpha-vantage
  description: This API returns monthly adjusted time series (last trading day of
    each month, monthly open, monthly high, monthly low, monthly close, monthly adjusted
    close, monthly volume, monthly dividend) of the equity specified, covering up
    to 20 years of historical data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=TIME_SERIES_MONTHLY_ADJUSTED
  tags: Market Data, Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiontime-series-monthly-adjusted-get-openapi.md
- name: Alpha Vantage Batch Stock Quotes
  x-api-slug: alpha-vantage
  description: The batch stock quotes API enables the querying of multiple stock quotes
    with a single API request, updated realtime. It may serve as a lightweight alternative
    to our core stock time series APIs above (which have richer content but are symbol-specific).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=BATCH_STOCK_QUOTES
  tags: Market Data,Time Series, Stock Quotes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionbatch-stock-quotes-get-openapi.md
- name: Alpha Vantage Currency Exchange Rates
  x-api-slug: alpha-vantage
  description: Realtime currency exchange rates for physical and digital currencies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=CURRENCY_EXCHANGE_RATE
  tags: Currency, Exchange Rates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctioncurrency-exchange-rate-get-openapi.md
- name: Alpha Vantage Digital Currencies Intraday
  x-api-slug: alpha-vantage
  description: This API returns the realtime intraday time series (in 5-minute intervals)
    for any digital currency (e.g., BTC) traded on a specific market (e.g., CNY/Chinese
    Yuan). Prices and volumes are quoted in both the market-specific currency and
    USD.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=DIGITAL_CURRENCY_INTRADAY
  tags: Market Data,Digital Currencies,Intraday,Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiondigital-currency-intraday-get-openapi.md
- name: Alpha Vantage Digital Currencies Daily
  x-api-slug: alpha-vantage
  description: This API returns the daily historical time series for a digital currency
    (e.g., BTC) traded on a specific market (e.g., CNY/Chinese Yuan), refreshed daily
    at midnight (UTC). Prices and volumes are quoted in both the market-specific currency
    and USD.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=DIGITAL_CURRENCY_DAILY
  tags: Market Data,Digital Currencies,Daily,Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiondigital-currency-daily-get-openapi.md
- name: Alpha Vantage Digital Currencies Weekly
  x-api-slug: alpha-vantage
  description: This API returns the weekly historical time series for a digital currency
    (e.g., BTC) traded on a specific market (e.g., CNY/Chinese Yuan), refreshed daily
    at midnight (UTC). Prices and volumes are quoted in both the market-specific currency
    and USD.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=DIGITAL_CURRENCY_WEEKLY
  tags: Market Data,Digital Currencies,Weekly,Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiondigital-currency-weekly-get-openapi.md
- name: Alpha Vantage Digital Currencies Monthly
  x-api-slug: alpha-vantage
  description: This API returns the monthly historical time series for a digital currency
    (e.g., BTC) traded on a specific market (e.g., CNY/Chinese Yuan), refreshed daily
    at midnight (UTC). Prices and volumes are quoted in both the market-specific currency
    and USD.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=DIGITAL_CURRENCY_MONTHLY
  tags: Market Data,Digital Currencies,Monthly,Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctiondigital-currency-monthly-get-openapi.md
- name: Alpha Vantage Simple Moving Average (SMA)
  x-api-slug: alpha-vantage
  description: This API returns the simple moving average (SMA) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=SMA
  tags: Market Data,Simple Moving Average,SMA
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionsma-get-openapi.md
- name: Alpha Vantage Exponential Moving Average (EMA)
  x-api-slug: alpha-vantage
  description: This API returns the exponential moving average (EMA)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=EMA
  tags: Market Data,Exponential Moving Average,EMA
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionema-get-openapi.md
- name: Alpha Vantage Moving Average Convergence / Divergence (MACD)
  x-api-slug: alpha-vantage
  description: This API returns the moving average convergence / divergence (MACD)
    values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=MACD
  tags: Market Data,Moving Average Convergence,MACD
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionmacd-get-openapi.md
- name: Alpha Vantage Stochastic Oscillator (STOCH)
  x-api-slug: alpha-vantage
  description: This API returns the stochastic oscillator (STOCH) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=STOCH
  tags: Market Data,Stochastic Oscillator,STOCH
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionstoch-get-openapi.md
- name: Alpha Vantage Relative Strength Index (RSI)
  x-api-slug: alpha-vantage
  description: This API returns the relative strength index (RSI) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=RSI
  tags: Market Data,Relative Strength Index,RSI
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionrsi-get-openapi.md
- name: Alpha Vantage Average Directional Movement Index (ADX)
  x-api-slug: alpha-vantage
  description: This API returns the average directional movement index (ADX) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=ADX
  tags: Market Data,Average Directional Movement Index,ADX
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionadx-get-openapi.md
- name: Alpha Vantage Commodity Channel Index (CCI)
  x-api-slug: alpha-vantage
  description: This API returns the commodity channel index (CCI) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=CCI
  tags: Market Data,Commodity Channel Index,CCI
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctioncci-get-openapi.md
- name: Alpha Vantage Aroon (AROON)
  x-api-slug: alpha-vantage
  description: This API returns the Aroon (AROON) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=AROON
  tags: Market Data,Aroon,AROON
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionaroon-get-openapi.md
- name: Alpha Vantage Bollinger bands (BBANDS)
  x-api-slug: alpha-vantage
  description: This API returns the Bollinger bands (BBANDS) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=BBANDS
  tags: Market Data,Bollinger bands,BBANDS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionbbands-get-openapi.md
- name: Alpha Vantage Chaikin A/D line (AD)
  x-api-slug: alpha-vantage
  description: This API returns the Chaikin A/D line (AD) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=AD
  tags: Market Data,Chaikin A/D Line,AD)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionad-get-openapi.md
- name: Alpha Vantage Balance Volume (OBV)
  x-api-slug: alpha-vantage
  description: This API returns the on balance volume (OBV) values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=OBV
  tags: Market Data,Balance Volume,OBV
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionobv-get-openapi.md
- name: Alpha Vantage Sector Performance
  x-api-slug: alpha-vantage
  description: This API returns the realtime and historical sector performances calculated
    from S&P500 incumbents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co////query?function=SECTOR
  tags: Market Data,Sector,Performance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/queryfunctionsector-get-openapi.md
- name: Alpha Vantage
  x-api-slug: alpha-vantage
  description: Composed of a tight-knit community of researchers, engineers, and business
    professionals, Alpha Vantage Inc. is a leading provider of free APIs for realtime
    and historical data on stocks, physical currencies, and digital/crypto currencies.
    Our success is driven by rigorous research, cutting edge technology, and a disciplined
    focus on democratizing access to data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2018-01-22 at 4.52.35 PM.png
  humanURL: https://www.alphavantage.co
  baseURL: https://www.alphavantage.co//
  tags: Alpha Vantage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/alpha-vantage/master/_listings/alpha-vantage/openapi.md
x-common:
- type: x-command-line-interface
  url: https://www.npmjs.com/package/alpha-vantage-cli
- type: x-documentation
  url: https://www.alphavantage.co/documentation/
- type: x-forum
  url: https://www.alpha-vantage.community/
- type: x-selfservice-registration
  url: https://www.alphavantage.co/support/#api-key
- type: x-support
  url: https://www.alphavantage.co/support/#support
- type: x-terms-of-service
  url: https://www.alphavantage.co/terms_of_service/
- type: x-website
  url: https://www.alphavantage.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---