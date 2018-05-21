---
name: Amadeus
x-slug: amadeus
description: Amadeus travel technology helps businesses connect to the global travel
  ecosystem, manage operations more effectively and serve travellers better than ever
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
x-kinRank: "8"
x-alexaRank: "4309"
tags: Autocomplete
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/amadeus/apis.md
specificationVersion: "0.14"
apis:
- name: Amadeus Get Airports Autocomplete
  x-api-slug: amadeus
  description: "Using the term parameter and given the start of any word in an airport's
    official name, a city name, or the start of an IATA code, this API provides the
    full name and IATA location code of the city or airport, for use in flight searches.
    Only major cities and civilian airports with several commercial flights per week
    are included by default. The response provides up to 20 possible matches, sorted
    by importance, in a JQuery UI Autocomplete compatible format. This sample implementation
    using JQuery UI may help. This API uses data from the OpenTravelData project.\n
    \nBy only using the country parameter, this API is also able to find all the IATA
    location codes associated with a country. Both term and country parameters can
    be used together to filter the results accordingly.          \n\nThe value returned
    is the IATA location code. The label returned is always in UTF-8 format, with
    the airport official name (which is often in the native language), in the format
    of English City Name (if not already included in the airport name)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2//airports/autocomplete
  tags: Airlines, Airports, Autocomplete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/amadeus/airportsautocomplete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/amadeus/airportsautocomplete-get-openapi.md
- name: Amadeus Get Rail Stations Autocomplete
  x-api-slug: amadeus
  description: |-
    Given the start of any word in a rail station's official name, as a term, this API provides the full name and rail station ID of a rail station for use in searches. The response provides an array of up to 20 possible matches, sorted by passenger traffic, in a JQuery Autocomplete compatible format.

    The value returned is the UIC station code. The label returned is always in UTF-8 format, with the station's official name (which is often in the native language). Agglomeration station codes may also be returned.

    Note that only French and Italian rail stations are supported by the Rail Station Autocomplete API
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2//rail-stations/autocomplete
  tags: Rail, Stations, Autocomplete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/amadeus/railstationsautocomplete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/amadeus/railstationsautocomplete-get-openapi.md
- name: Amadeus
  x-api-slug: amadeus
  description: Amadeus travel technology helps businesses connect to the global travel
    ecosystem, manage operations more effectively and serve travellers better than
    ever
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28139-sandbox-amadeus-com.jpg
  humanURL: https://amadeus.com
  baseURL: https://api.sandbox.amadeus.com//v1.2
  tags: Autocomplete
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/amadeus/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/amadeus
- type: x-documentation
  url: https://sandbox.amadeus.com/api-catalog
- type: x-github
  url: https://github.com/AmadeusITGroup
- type: x-privacy-policy
  url: http://www.amadeus.com/web/amadeus/en_1A-corporate/Amadeus-Home/Amadeus_IT_Group_SA-Legal-notices-2014/1319560218660-Page-AMAD_Detail_PopUp_Ppal?assetid=1319607040997&assettype=DataProtection_C
- type: x-sandbox
  url: https://sandbox.amadeus.com
- type: x-twitter
  url: https://twitter.com/amadeusinnov
- type: x-website
  url: https://amadeus.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---