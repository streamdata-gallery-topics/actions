---
swagger: "2.0"
x-collection-name: Hewlett Packard Enterprise (HPE)
x-complete: 0
info:
  title: HPE OneSphere API Post Zones Actions
  description: Peforms an action to the zone. It requires the **administrator** role.
  termsOfService: http://www.hpe.com/onesphere
  contact:
    name: HPE OneSphere API team
    url: http://www.hpe.com/onesphere
  version: 1.0.0
host: deic02-hpe.hpeonesphere.com
basePath: /rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /deployments/{id}/actions:
    post:
      summary: Post Deployments Actions
      description: Peforms an action to change the state of a deployment. It requires
        any project role, or the **administrator** or **project creator** global role.
      operationId: ActOnDeployment
      x-api-path-slug: deploymentsidactions-post
      parameters:
      - in: body
        name: action
        description: Action to perform
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of deployment to act on
      responses:
        200:
          description: OK
      tags:
      - Deployments
      - Actions
  /zones/{id}/actions:
    post:
      summary: Post Zones Actions
      description: Peforms an action to the zone. It requires the **administrator**
        role.
      operationId: ActOnZone
      x-api-path-slug: zonesidactions-post
      parameters:
      - in: body
        name: action
        description: Action to perform
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of zone to act on
      responses:
        200:
          description: OK
      tags:
      - Zones
      - Actions
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---