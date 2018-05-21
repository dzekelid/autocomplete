---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
  description: the-reddit-api-allows-you-to-access-the-user-submitted-and-rated-stories-on-redditcom-it-also-provides-advanced-functionality-including-user-account-information-and-subreddit-moderation
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subreddit_autocomplete:
    get&nbsp;:
      summary: Get Subreddit Autocomplete
      description: |-
        Return a list of subreddits and data for subreddits whose names start
        with &#39;query&#39;.
      operationId: get&nbsp;SubredditAutocomplete
      x-api-path-slug: subreddit-autocomplete-getnbsp
      parameters:
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_profiles
        description: boolean value
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Autocomplete
  /subreddit_autocomplete_v2:
    get&nbsp;:
      summary: Get Subreddit Autocomplete V2
      description: boolean value
      operationId: get&nbsp;SubredditAutocompleteV2
      x-api-path-slug: subreddit-autocomplete-v2-getnbsp
      parameters:
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_profiles
        description: boolean value
        type: string
      - in: query
        name: limit
        description: 'an integer between 1 and 10 (default: 5)'
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Autocomplete
      - V2
---