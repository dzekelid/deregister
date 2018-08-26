---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli Deregister a Device
  description: Deregister a device.
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/821374c0-d6d8-11e3-9c1a-0800200c9a66:
    delete:
      summary: Deregister a Device
      description: Deregister a device.
      operationId: Devices821374c0D6d811e39c1a0800200c9a66Delete
      x-api-path-slug: devices821374c0d6d811e39c1a0800200c9a66-delete
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Device
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