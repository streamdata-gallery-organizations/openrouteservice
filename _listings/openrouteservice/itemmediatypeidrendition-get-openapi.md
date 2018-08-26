---
swagger: "2.0"
x-collection-name: OpenRouteService
x-complete: 0
info:
  title: AP Content API Get Item Mediatype Rendition
  description: Pulls item media
  version: v2
host: api.ap.org
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  item/{id}/:
    get:
      summary: Get Item
      description: Get items.
      operationId: getItem
      x-api-path-slug: itemid-get
      parameters:
      - in: query
        name: apiKey
        description: API Key
      - in: query
        name: format
        description: The format of the returned content item data
      - in: query
        name: id
        description: The GUID of a content item (not case-sensitive)
      responses:
        200:
          description: OK
      tags:
      - Item
  item/{mediaType}/{id}/{rendition}:
    get:
      summary: Get Item Mediatype Rendition
      description: Pulls item media
      operationId: getItemMediatypeRendition
      x-api-path-slug: itemmediatypeidrendition-get
      parameters:
      - in: query
        name: apiKey
        description: API key
      - in: query
        name: filename
        description: The filename for the downloaded content item rendition, in the
          format
      - in: query
        name: id
        description: The GUID of a content item (not case-sensitive)
      - in: query
        name: mediaType
        description: The content media type
      - in: query
        name: rendition
        description: The content item rendition
      responses:
        200:
          description: OK
      tags:
      - Item
      - Mediatype
      - Rendition
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