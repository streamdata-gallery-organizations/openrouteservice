---
swagger: "2.0"
x-collection-name: OpenRouteService
x-complete: 0
info:
  title: AP Breaking News API Categories
  description: Returns a list of available AP Breaking News categories, including
    category IDs.
  version: v2
host: developerapi.ap.org
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  categories.svc/:
    get:
      summary: Categories
      description: Returns a list of available AP Breaking News categories, including
        category IDs.
      operationId: getCategories.svc
      x-api-path-slug: categories-svc-get
      parameters:
      - in: query
        name: apiKey
        description: API Key
      responses:
        200:
          description: OK
      tags:
      - Categories
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