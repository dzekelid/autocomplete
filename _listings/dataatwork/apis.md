---
name: DataAtWork
x-slug: dataatwork
description: ""
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2016-10-12 at 11.19.25 PM.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Autocomplete
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/dataatwork/apis.md
specificationVersion: "0.14"
apis:
- name: Open Skills API Job Title Autocomplete
  x-api-slug: open-skills-api
  description: Retrieves the names, descriptions, and UUIDs of all job titles matching
    a given search criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2016-10-12 at 11.19.25 PM.png
  humanURL: http://www.dataatwork.org/
  baseURL: ://api.dataatwork.org//v1//jobs/autocomplete
  tags: Job, Title, Autocomplete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/dataatwork/jobsautocomplete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/dataatwork/jobsautocomplete-get-openapi.md
- name: Open Skills API Skill Name Autocomplete
  x-api-slug: open-skills-api
  description: Retrieves the names, descriptions, and UUIDs of all skills matching
    a given search criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2016-10-12 at 11.19.25 PM.png
  humanURL: http://www.dataatwork.org/
  baseURL: ://api.dataatwork.org//v1//skills/autocomplete
  tags: Skill, Name, Autocomplete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/dataatwork/skillsautocomplete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/dataatwork/skillsautocomplete-get-openapi.md
- name: Open Skills API
  x-api-slug: open-skills-api
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2016-10-12 at 11.19.25 PM.png
  humanURL: http://www.dataatwork.org/
  baseURL: ://api.dataatwork.org//v1
  tags: Autocomplete
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autocomplete/master/_listings/dataatwork/openapi.md
x-common:
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