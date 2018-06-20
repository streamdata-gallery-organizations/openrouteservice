---
name: OpenRouteService
x-slug: openrouteservice
description: OpenStreetMap is the free wiki world map.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
x-kinRank: "7"
x-alexaRank: "6266"
tags: OpenRouteService
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/apis.md
specificationVersion: "0.14"
apis:
- name: AP Breaking News API Categories
  x-api-slug: ap-breaking-news-api
  description: Returns a list of available AP Breaking News categories, including
    category IDs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://developerapi.ap.org/v2//categories.svc/
  tags: Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/categories-svc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/categories-svc-get-openapi.md
- name: AP Breaking News API Category News
  x-api-slug: ap-breaking-news-api
  description: Returns the latest content for a specific category. Depending on the
    specified parameters, returns  either the full story for each headline and/or
    the headlines linked to web pages with the full stories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://developerapi.ap.org/v2//categories.svc/{categoryID}/
  tags: Category,News
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/categories-svccategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/categories-svccategoryid-get-openapi.md
- name: AP Breaking News API
  x-api-slug: ap-breaking-news-api
  description: OpenStreetMap is the free wiki world map.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://developerapi.ap.org/v2/
  tags: OpenRouteService
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/openapi.md
- name: AP Content API Get Item
  x-api-slug: ap-content-api
  description: Get items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2//item/{id}/
  tags: Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/itemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/itemid-get-openapi.md
- name: AP Content API Get Item Mediatype Rendition
  x-api-slug: ap-content-api
  description: Pulls item media
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2//item/{mediaType}/{id}/{rendition}
  tags: Item,Mediatype,Rendition
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/itemmediatypeidrendition-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/itemmediatypeidrendition-get-openapi.md
- name: AP Content API Get Search Mediatype
  x-api-slug: ap-content-api
  description: Search news
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2//search/{mediaType}
  tags: Search,Mediatype
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/searchmediatype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/searchmediatype-get-openapi.md
- name: AP Content API
  x-api-slug: ap-content-api
  description: OpenStreetMap is the free wiki world map.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2/
  tags: OpenRouteService
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/openapi.md
- name: AP Metadata Services Change Log
  x-api-slug: ap-metadata-services
  description: Returns a list of changes to the AP vocabulary terms according to the
    specified criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org///api/cm/
  tags: Change,Log
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/apicm-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/apicm-get-openapi.md
- name: AP Metadata Services Ontology Definition
  x-api-slug: ap-metadata-services
  description: Returns the AP ontology definition for the specified AP property or
    class and the specified format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org///c/{class}.{format}
  tags: Ontology,Definition
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/cclass-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/cclass-format-get-openapi.md
- name: AP Metadata Services DeprecatedCompany
  x-api-slug: ap-metadata-services
  description: Returns a list of deprecated AP vocabulary terms in the specified format
    for the AP Company authority  or for the other four AP authorities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org///d/DeprecatedCompany.{format}
  tags: DeprecatedCompany
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/ddeprecatedcompany-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/ddeprecatedcompany-format-get-openapi.md
- name: AP Metadata Services Deprecated Terms
  x-api-slug: ap-metadata-services
  description: Returns a list of deprecated AP vocabulary terms in the specified format
    for the AP Company authority  or for the other four AP authorities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org///d/DeprecatedTerm.{format}
  tags: Deprecated,Terms
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/ddeprecatedterm-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/ddeprecatedterm-format-get-openapi.md
- name: AP Metadata Services Taxonomy Information
  x-api-slug: ap-metadata-services
  description: Returns the taxonomy information for the specified authority and the
    specified format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org///d/{authority}.{format}
  tags: Taxonomy,Information
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/dauthority-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/dauthority-format-get-openapi.md
- name: AP Metadata Services Authority
  x-api-slug: ap-metadata-services
  description: Returns a document for the specified authority and format with the
    AP vocabulary data for the  specified term GUID and the subset of the vocabulary
    located below the specified term.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org///d/{authority}/{GUID}.{format}
  tags: Authority
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/dauthorityguid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/dauthorityguid-format-get-openapi.md
- name: AP Metadata Services Taxonomy Information
  x-api-slug: ap-metadata-services
  description: Returns the taxonomy information for the specified GUID of an AP term
    and the specified format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org///id/{GUID}.{format}
  tags: Taxonomy,Information
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/idguid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/idguid-format-get-openapi.md
- name: AP Metadata Services Tags
  x-api-slug: ap-metadata-services
  description: Returns the set of AP standardized vocabulary terms that apply to the
    submitted news content. The  output can be limited to one or more authorities
    specified in the request; for example, you can choose  to apply only AP Organization,
    AP Subject and AP Geography tags to the submitted content, but not  AP Person
    or AP Company.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org///Tags/
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/tags-post-openapi.md
- name: AP Metadata Services
  x-api-slug: ap-metadata-services
  description: OpenStreetMap is the free wiki world map.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: OpenRouteService
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/openapi.md
x-common:
- type: x-website
  url: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
- type: x-crunchbase
  url: https://crunchbase.com/organization/openstreetmap-3
- type: x-developer
  url: https://developer.ap.org/
- type: x-website
  url: http://ap.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---