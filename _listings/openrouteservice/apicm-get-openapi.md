---
swagger: "2.0"
x-collection-name: OpenRouteService
x-complete: 0
info:
  title: AP Metadata Services Change Log
  description: Returns a list of changes to the AP vocabulary terms according to the
    specified criteria.
  version: v1
host: cv.ap.org
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  api/cm/:
    get:
      summary: Change Log
      description: Returns a list of changes to the AP vocabulary terms according
        to the specified criteria.
      operationId: getApiCm
      x-api-path-slug: apicm-get
      parameters:
      - in: query
        name: apiKey
        description: API Key
      - in: query
        name: authority
        description: authority
      - in: query
        name: enddate
        description: This parameter can be used in conjunction with the startdate
          parameter to  specify a date range
      - in: query
        name: format
        description: 'Specifies the output format: comma-separated values (CSV) or
          XML'
      - in: query
        name: lastversion
        description: Returns all change logs since (but not including) the specified
          version  number, in the format {AuthorityVersion}
      - in: query
        name: startdate
        description: eturns all change logs since (and including) the specified date
      - in: query
        name: version
        description: Returns the change log for the specified version number, in the
          format  {AuthorityVersion}
      responses:
        200:
          description: OK
      tags:
      - Change
      - Log
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