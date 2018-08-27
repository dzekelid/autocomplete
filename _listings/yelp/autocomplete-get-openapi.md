---
swagger: "2.0"
x-collection-name: Yelp
x-complete: 0
info:
  title: Yelp Get Autocomplete
  description: Get autocomplete.
  version: 1.0.0
host: api.yelp.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /autocomplete:
    get:
      summary: Get Autocomplete
      description: Get autocomplete.
      operationId: getAutocomplete
      x-api-path-slug: autocomplete-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: text
      responses:
        200:
          description: OK
      tags:
      - Autocomplete
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