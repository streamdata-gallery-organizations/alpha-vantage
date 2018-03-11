---
swagger: "2.0"
info:
  title: Alpha Vantage
  description: 'Alpha Vantage APIs are grouped into four categories: (1) Stock Time
    Series Data, (2) Physical and Digital/Crypto Currencies (e.g., Bitcoin), (3) Stock
    Technical Indicators, and (4) Sector Performances. All APIs are realtime: the
    latest data points are derived from the current trading day. '
  version: 1.0.0
host: www.alphavantage.co
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /query?function=TIME_SERIES_WEEKLY:
    get:
      summary: Weekly Time Series
      description: This API returns weekly time series (last trading day of each week,
        weekly open, weekly high, weekly low, weekly close, weekly volume) of the
        equity specified, covering up to 20 years of historical data
      operationId: getWeeklyTimeSeries
      parameters:
      - in: query
        name: symbol
        description: The stocker ticker symbol
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - market data
      - time series
definitions: []
x-collection-name: Alpha Vantage
x-streamrank:
  polling_total_time_average: ~
  polling_size_download_average: ~
  streaming_total_time_average: ~
  streaming_size_download_average: ~
  change_yes: ~
  change_no: ~
  time_percentage: ~
  size_percentage: ~
  change_percentage: ~
  last_run: ~
  days_run: ~
  minute_run: ~
---