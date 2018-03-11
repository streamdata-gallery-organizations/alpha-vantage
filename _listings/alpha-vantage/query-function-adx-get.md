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
  /query?function=ADX:
    get:
      summary: Average Directional Movement Index (ADX)
      description: This API returns the average directional movement index (ADX) values
      operationId: getAverageDirectionalMovementIndex
      parameters:
      - in: query
        name: interval
        description: Time interval between two consecutive data points in the time
          series
        type: string
        format: string
      - in: query
        name: symbol
        description: The name of the equity of your choice
        type: string
        format: string
      - in: query
        name: time_period
        description: Number of data points used to calculate each moving average value
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - market data
      - average directional movement index
      - adx
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