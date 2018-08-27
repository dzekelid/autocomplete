swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/autocomplete:
    get:
      summary: Autocomplete users
      description: |-
        Get a list of users for the purpose of autocompleting based on the provided search term. Specify a combination of `team_id` and `channel_id` to filter results further.
        ##### Permissions
        Requires an active session and `view_team` and `read_channel` on any teams or channels used to filter the results further.
      operationId: get-a-list-of-users-for-the-purpose-of-autocompleting-based-on-the-provided-search-term-specify-a-co
      x-api-path-slug: usersautocomplete-get
      parameters:
      - in: query
        name: channel_id
        description: Channel ID
      - in: query
        name: name
        description: Username, nickname first name or last name
      - in: query
        name: team_id
        description: Team ID
      responses:
        200:
          description: OK
      tags:
      - Autocomplete
      - Users
  /teams/{team_id}/channels/autocomplete:
    get:
      summary: Autocomplete channels
      description: |-
        Autocomplete public channels on a team based on the search term provided in the request URL.

        __Minimum server version__: 4.7

        ##### Permissions
        Must have the `list_team_channels` permission.
      operationId: autocomplete-public-channels-on-a-team-based-on-the-search-term-provided-in-the-request-url-minimum-
      x-api-path-slug: teamsteam-idchannelsautocomplete-get
      parameters:
      - in: query
        name: name
        description: Name or display name
      - in: path
        name: team_id
        description: Team GUID
      responses:
        200:
          description: OK
      tags:
      - Autocomplete
      - Channels
  /emoji/autocomplete:
    get:
      summary: Autocomplete custom emoji
      description: |-
        Get a list of custom emoji with names starting with or matching the provided name. Returns a maximum of 100 results.
        ##### Permissions
        Must be authenticated.

        __Minimum server version__: 4.7
      operationId: get-a-list-of-custom-emoji-with-names-starting-with-or-matching-the-provided-name-returns-a-maximum-
      x-api-path-slug: emojiautocomplete-get
      parameters:
      - in: query
        name: name
        description: The emoji name to search
      responses:
        200:
          description: OK
      tags:
      - Autocomplete
      - Custom
      - Emoji
  /teams/{team_id}/commands/autocomplete:
    get:
      summary: List autocomplete commands
      description: |-
        List autocomplete commands in the team.
        ##### Permissions
        `view_team` for the team.
      operationId: list-autocomplete-commands-in-the-team-permissionsview-team-for-the-team
      x-api-path-slug: teamsteam-idcommandsautocomplete-get
      parameters:
      - in: path
        name: team_id
        description: Team GUID
      responses:
        200:
          description: OK
      tags:
      - List
      - Autocomplete
      - Commands