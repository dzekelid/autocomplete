swagger: "2.0"
x-collection-name: DataAtWork
x-complete: 1
info:
  title: Open Skills API
  description: a-complete-and-standard-data-store-for-canonical-and-emerging-skills-knowledge-abilities-tools-technolgies-and-how-they-relate-to-jobs-
  contact:
    name: Work Data Initiative
    url: http://www.dataatwork.org
  version: "1.0"
host: api.dataatwork.org
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /jobs/autocomplete:
    get:
      summary: Job Title Autocomplete
      description: Retrieves the names, descriptions, and UUIDs of all job titles
        matching a given search criteria.
      operationId: retrieves-the-names-descriptions-and-uuids-of-all-job-titles-matching-a-given-search-criteria
      x-api-path-slug: jobsautocomplete-get
      parameters:
      - in: query
        name: begins_with
        description: Find job titles beginning with the given text fragment
      - in: query
        name: contains
        description: Find job titles containing the given text fragment
      - in: query
        name: ends_with
        description: Find job titles ending with the given text fragment
      responses:
        200:
          description: OK
      tags:
      - Job
      - Title
      - Autocomplete
  /skills/autocomplete:
    get:
      summary: Skill Name Autocomplete
      description: Retrieves the names, descriptions, and UUIDs of all skills matching
        a given search criteria.
      operationId: retrieves-the-names-descriptions-and-uuids-of-all-skills-matching-a-given-search-criteria
      x-api-path-slug: skillsautocomplete-get
      parameters:
      - in: query
        name: begins_with
        description: Find skill names beginning with the given text fragment
      - in: query
        name: contains
        description: Find skill names containing the given text fragment
      - in: query
        name: ends_with
        description: Find skill names ending with the given text fragment
      responses:
        200:
          description: OK
      tags:
      - Skill
      - Name
      - Autocomplete