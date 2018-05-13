---
name: DataAtWork
description: ""
image: ""
x-kinRank: "8"
x-alexaRank: ""
tags:
- Skills
- Federal Government
- Careers
created: "2018-03-13"
modified: "2018-03-13"
url: https://raw.githubusercontent.com/streamdata-gallery/autocomplete/master/_listings/dataatwork/apis.yaml
specificationVersion: "0.14"
apis:
- name: Open Skills API
  description: ""
  image: ""
  humanURL: ""
  baseURL: ://api.dataatwork.org//v1
  tags: Autocomplete
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery/autocomplete/master/_listings/dataatwork/skills-autocomplete-get.md
- name: Open Skills API Job Title Autocomplete
  description: Retrieves the names, descriptions, and UUIDs of all job titles matching
    a given search criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2016-10-12 at 11.19.25 PM.png
  humanURL: http://www.dataatwork.org/
  baseURL: http:://api.dataatwork.org//v1
  tags: Autocomplete
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/dataatwork/jobs-autocomplete-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/dataatwork/jobs-autocomplete-get-postman.md
x-common:
- type: x-developer
  url: http://api.dataatwork.org/v1/spec/
- type: x-website
  url: http://www.dataatwork.org/
- type: x-developer
  url: http://api.dataatwork.org/v1/spec/
- type: x-website
  url: http://www.dataatwork.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---