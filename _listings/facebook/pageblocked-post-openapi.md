---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Post Page Blocked
  description: Blocks a user (or users) from posting content to the page
  version: 1.0.0
host: graph.facebook.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{page}/blocked:
    get:
      summary: Get Page Blocked
      description: A list of the users blocked from the page.
      operationId: getPageBlocked
      x-api-path-slug: pageblocked-get
      parameters:
      - in: path
        name: page
        description: Represents the ID of the page object
      responses:
        200:
          description: OK
      tags:
      - Page
      - Blocked
    post:
      summary: Post Page Blocked
      description: Blocks a user (or users) from posting content to the page
      operationId: postPageBlocked
      x-api-path-slug: pageblocked-post
      parameters:
      - in: path
        name: page
        description: Represents the ID of the page object
      - in: query
        name: uids
        description: Comma-separated list of the user IDs you wish to block
      responses:
        200:
          description: OK
      tags:
      - Page
      - Blocked
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