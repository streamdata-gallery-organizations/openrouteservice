---
swagger: "2.0"
x-collection-name: OpenRouteService
x-complete: 1
info:
  title: AP Metadata Services
  description: add-value-to-your-news-content-with-apu2019s-industryleading-metadata--accurate-comprehensive-richly-detailed-data-designed-specifically-for-use-by-news-publishers--ap-metadata-services-is-a-new-set-of-apis-that-gives-you-direct-access-to-the-same-metadata-system-that-supports-apu2019s-awardwinning-global-news-operation-
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
  c/{class}.{format}:
    get:
      summary: Ontology Definition
      description: Returns the AP ontology definition for the specified AP property
        or class and the specified format.
      operationId: getCClass.Format
      x-api-path-slug: cclass-format-get
      parameters:
      - in: query
        name: apikey
        description: API Key
      - in: path
        name: class
        description: The name of an AP property or class
      - in: path
        name: format
        description: The format of the returned AP ontology data
      responses:
        200:
          description: OK
      tags:
      - Ontology
      - Definition
  d/DeprecatedCompany.{format}:
    get:
      summary: DeprecatedCompany
      description: Returns a list of deprecated AP vocabulary terms in the specified
        format for the AP Company authority  or for the other four AP authorities.
      operationId: getDDeprecatedcompany.Format
      x-api-path-slug: ddeprecatedcompany-format-get
      parameters:
      - in: query
        name: apiKey
        description: API Key
      - in: path
        name: format
        description: The format of the returned taxonomy data (RDF/XML, RDF/TTL or  NewsML-G2)
      responses:
        200:
          description: OK
      tags:
      - DeprecatedCompany
  d/DeprecatedTerm.{format}:
    get:
      summary: Deprecated Terms
      description: Returns a list of deprecated AP vocabulary terms in the specified
        format for the AP Company authority  or for the other four AP authorities.
      operationId: getDDeprecatedterm.Format
      x-api-path-slug: ddeprecatedterm-format-get
      parameters:
      - in: query
        name: apiKey
        description: API Key
      - in: path
        name: format
        description: The format of the returned taxonomy data (RDF/XML, RDF/TTL or  NewsML-G2)
      responses:
        200:
          description: OK
      tags:
      - Deprecated
      - Terms
  d/{authority}.{format}:
    get:
      summary: Taxonomy Information
      description: Returns the taxonomy information for the specified authority and
        the specified format.
      operationId: getDAuthority.Format
      x-api-path-slug: dauthority-format-get
      parameters:
      - in: query
        name: apikey
        description: API Key
      - in: path
        name: authority
        description: The name of a classification authority (not case-sensitive)
      - in: path
        name: format
        description: The format of the returned taxonomy data
      responses:
        200:
          description: OK
      tags:
      - Taxonomy
      - Information
  d/{authority}/{GUID}.{format}:
    get:
      summary: Authority
      description: Returns a document for the specified authority and format with
        the AP vocabulary data for the  specified term GUID and the subset of the
        vocabulary located below the specified term.
      operationId: getDAuthorityGu.Format
      x-api-path-slug: dauthorityguid-format-get
      parameters:
      - in: query
        name: apikey
        description: API Key
      - in: path
        name: authority
        description: The name of a classification authority (not case-sensitive)
      - in: path
        name: format
        description: The format of the returned taxonomy data
      - in: path
        name: GUID
        description: The GUID of an AP term below which the returned taxonomy data  subset
          is located in the AP taxonomy hierarchy
      responses:
        200:
          description: OK
      tags:
      - Authority
  id/{GUID}.{format}:
    get:
      summary: Taxonomy Information
      description: Returns the taxonomy information for the specified GUID of an AP
        term and the specified format.
      operationId: getGu.Format
      x-api-path-slug: idguid-format-get
      parameters:
      - in: query
        name: apiKey
        description: API Key
      - in: path
        name: format
        description: The format of the returned taxonomy data
      - in: path
        name: GUID
        description: The GUID of an AP term (not case-sensitive)
      responses:
        200:
          description: OK
      tags:
      - Taxonomy
      - Information
  Tags/:
    post:
      summary: Tags
      description: Returns the set of AP standardized vocabulary terms that apply
        to the submitted news content. The  output can be limited to one or more authorities
        specified in the request; for example, you can choose  to apply only AP Organization,
        AP Subject and AP Geography tags to the submitted content, but not  AP Person
        or AP Company.
      operationId: postTags
      x-api-path-slug: tags-post
      parameters:
      - in: query
        name: apiKey
        description: API Key
      - in: body
        name: story
        description: URL-encoded content  submitted for tagging
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Tags
---