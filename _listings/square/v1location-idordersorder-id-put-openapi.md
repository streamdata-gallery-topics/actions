---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: 'Square Connect API Updates the details of an online store order. Every update
    you perform on an order corresponds to one of three actions:'
  description: 'Updates the details of an online store order. Every update you perform
    on an order corresponds to one of three actions:'
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{location_id}/orders/{order_id}:
    put:
      summary: 'Updates the details of an online store order. Every update you perform
        on an order corresponds to one of three actions:'
      description: 'Updates the details of an online store order. Every update you
        perform on an order corresponds to one of three actions:'
      operationId: UpdateOrder
      x-api-path-slug: v1location-idordersorder-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the orders associated location
      - in: path
        name: order_id
        description: The orders Square-issued ID
      responses:
        200:
          description: OK
      tags:
      - S
      - Details
      - Of
      - Online
      - Store
      - Order
      - ""
      - Every
      - Update
      - You
      - Perform
      - "On"
      - Order
      - Corresponds
      - To
      - Of
      - Three
      - 'Actions:'
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