---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 0
info:
  title: Big Oven Given a query, return recipe titles starting with query. Query must
    be at least 3 chars in length.
  description: Given a query, return recipe titles starting with query. query must
    be at least 3 chars in length..
  termsOfService: Please see our [terms of service](http://api2.bigoven.com/web/documentation/termsofuse
  version: partner
host: api2.bigoven.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /recipe/autocomplete:
    get:
      summary: Given a query, return recipe titles starting with query. Query must
        be at least 3 chars in length.
      description: Given a query, return recipe titles starting with query. query
        must be at least 3 chars in length..
      operationId: Recipe_AutoComplete
      x-api-path-slug: recipeautocomplete-get
      parameters:
      - in: query
        name: limit
      - in: query
        name: query
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
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