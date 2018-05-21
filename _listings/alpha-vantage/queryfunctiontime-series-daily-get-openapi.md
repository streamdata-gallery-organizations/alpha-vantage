---
swagger: "2.0"
x-collection-name: Alpha Vantage
x-complete: 0
info:
  title: Alpha Vantage Daily Time Series
  description: This API returns daily time series (date, daily open, daily high, daily
    low, daily close, daily volume) of the equity specified, covering up to 20 years
    of historical data.
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
  /query?function=TIME_SERIES_DAILY_ADJUSTED:
    get:
      summary: Daily Time Series Adjusted
      description: This API returns daily time series (date, daily open, daily high,
        daily low, daily close, daily volume, daily adjusted close, and split/dividend
        events) of the equity specified, covering up to 20 years of historical data.
      operationId: getDailyTimeSeriesAdjusted
      x-api-path-slug: queryfunctiontime-series-daily-adjusted-get
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
      - Market Data
      - Time Series
  /query?function=TIME_SERIES_WEEKLY:
    get:
      summary: Weekly Time Series
      description: This API returns weekly time series (last trading day of each week,
        weekly open, weekly high, weekly low, weekly close, weekly volume) of the
        equity specified, covering up to 20 years of historical data.
      operationId: getWeeklyTimeSeries
      x-api-path-slug: queryfunctiontime-series-weekly-get
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
      - Market Data
      - Time Series
  /query?function=TIME_SERIES_DAILY:
    get:
      summary: Daily Time Series
      description: This API returns daily time series (date, daily open, daily high,
        daily low, daily close, daily volume) of the equity specified, covering up
        to 20 years of historical data.
      operationId: getDailyTimeSeries
      x-api-path-slug: queryfunctiontime-series-daily-get
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