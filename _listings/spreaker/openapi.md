swagger: "2.0"
x-collection-name: Spreaker
x-complete: 1
info:
  title: Spreaker API
  version: v1
host: api.spreaker.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/{user_id}/actions:
    get:
      summary: Get User Actions
      description: Retrieves the user actions settings
      operationId: getUserUserActions
      x-api-path-slug: useruser-idactions-get
      parameters:
      - in: query
        name: EPISODE_BROADCAST
        description: The user has published a new episode ( either live or podcast
          )
      - in: query
        name: FACEBOOK
        description: The user wants to share on facebook the specified action
      - in: query
        name: RADIO_FOLLOW
        description: The user starts following a radio
      - in: query
        name: RADIO_MESSAGE
        description: The user has sent a message to a radio
      - in: query
        name: SHOW_FOLLOW
        description: The user starts following a show
      - in: query
        name: SHOW_MESSAGE
        description: The user has sent a message to a show
      - in: query
        name: TWITTER
        description: The user wants to share on twitter the specified action
      - in: query
        name: USER_FOLLOW
        description: The user starts following another user
      - in: query
        name: user_id
        description: The user id
      responses:
        200:
          description: OK
      tags:
      - Podcasts
      - User
      - Actions