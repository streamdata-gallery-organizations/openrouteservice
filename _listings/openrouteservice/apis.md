---
name: OpenRouteService
x-slug: openrouteservice
description: OpenStreetMap is the free wiki world map.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
x-kinRank: "7"
x-alexaRank: "6266"
tags: OpenRouteService
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/apis.md
specificationVersion: "0.14"
apis:
- name: AP Breaking News API - Categories
  x-api-slug: categories-svc-get
  description: Returns a list of available AP Breaking News categories, including
    category IDs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://developerapi.ap.org/v2/
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/categories-svc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/categories-svc-get-openapi.md
- name: AP Breaking News API - Category News
  x-api-slug: categories-svccategoryid-get
  description: Returns the latest content for a specific category. Depending on the
    specified parameters, returns  either the full story for each headline and/or
    the headlines linked to web pages with the full stories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://developerapi.ap.org/v2/
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/categories-svccategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/categories-svccategoryid-get-openapi.md
- name: AP Content API - Get Item
  x-api-slug: itemid-get
  description: Get items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2/
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/itemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/itemid-get-openapi.md
- name: AP Content API - Get Item Mediatype Rendition
  x-api-slug: itemmediatypeidrendition-get
  description: Pulls item media
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2/
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/itemmediatypeidrendition-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/itemmediatypeidrendition-get-openapi.md
- name: AP Content API - Get Search Mediatype
  x-api-slug: searchmediatype-get
  description: Search news
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2/
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/searchmediatype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/searchmediatype-get-openapi.md
- name: AP Metadata Services - Change Log
  x-api-slug: apicm-get
  description: Returns a list of changes to the AP vocabulary terms according to the
    specified criteria.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/apicm-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/apicm-get-openapi.md
- name: AP Metadata Services - Ontology Definition
  x-api-slug: cclass-format-get
  description: Returns the AP ontology definition for the specified AP property or
    class and the specified format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/cclass-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/cclass-format-get-openapi.md
- name: AP Metadata Services - DeprecatedCompany
  x-api-slug: ddeprecatedcompany-format-get
  description: Returns a list of deprecated AP vocabulary terms in the specified format
    for the AP Company authority  or for the other four AP authorities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/ddeprecatedcompany-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/ddeprecatedcompany-format-get-openapi.md
- name: AP Metadata Services - Deprecated Terms
  x-api-slug: ddeprecatedterm-format-get
  description: Returns a list of deprecated AP vocabulary terms in the specified format
    for the AP Company authority  or for the other four AP authorities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/ddeprecatedterm-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/ddeprecatedterm-format-get-openapi.md
- name: AP Metadata Services - Taxonomy Information
  x-api-slug: dauthority-format-get
  description: Returns the taxonomy information for the specified authority and the
    specified format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/dauthority-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/dauthority-format-get-openapi.md
- name: AP Metadata Services - Authority
  x-api-slug: dauthorityguid-format-get
  description: Returns a document for the specified authority and format with the
    AP vocabulary data for the  specified term GUID and the subset of the vocabulary
    located below the specified term.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/dauthorityguid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/dauthorityguid-format-get-openapi.md
- name: AP Metadata Services - Taxonomy Information
  x-api-slug: idguid-format-get
  description: Returns the taxonomy information for the specified GUID of an AP term
    and the specified format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/idguid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/idguid-format-get-openapi.md
- name: AP Metadata Services - Tags
  x-api-slug: tags-post
  description: Returns the set of AP standardized vocabulary terms that apply to the
    submitted news content. The  output can be limited to one or more authorities
    specified in the request; for example, you can choose  to apply only AP Organization,
    AP Subject and AP Geography tags to the submitted content, but not  AP Person
    or AP Company.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://cv.ap.org//
  tags: Bicycle, Routes, Directions, Technology, SaaS, Routes, Routes, General Data,
    Relative Data, Service API, Locations, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/openrouteservice/master/_listings/openrouteservice/tags-post-openapi.md
x-common:
- type: x-website
  url: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
- type: x-api-gallery
  url: http://opendns.api.gallery.streamdata.io
- type: x-api-stack
  url: http://openrouteservice.stack.network
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