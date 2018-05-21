---
swagger: "2.0"
x-collection-name: Alpha Vantage
x-complete: 0
info:
  title: Alpha Vantage Intraday Time Series
  description: This API returns intraday time series (timestamp, open, high, low,
    close, volume) of the equity specified, updated realtime.
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
  /query?function=TIME_SERIES_INTRADAY:
    get:
      summary: Intraday Time Series
      description: This API returns intraday time series (timestamp, open, high, low,
        close, volume) of the equity specified, updated realtime.
      operationId: getIntradayTimeSeries
      x-api-path-slug: queryfunctiontime-series-intraday-get
      parameters:
      - in: query
        name: datatype
        description: By default, datatype=json
        type: string
        format: string
      - in: query
        name: interval
        description: The interval for series (1min, 5min, 15min, 30min, 60min)
        type: string
        format: string
      - in: query
        name: outputsize
        description: By default, outputsize=compact
        type: string
        format: string
      - in: query
        name: symbol
        description: The stocker ticker symbol
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Time Series
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