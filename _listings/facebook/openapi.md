swagger: "2.0"
x-collection-name: Facebook
x-complete: 1
info:
  title: Facebook
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
    delete:
      summary: Delete Page Blocked
      description: Unblocks a user (or users) for the page
      operationId: deletePageBlocked
      x-api-path-slug: pageblocked-delete
      parameters:
      - in: path
        name: page
        description: Represents the ID of the page object
      - in: query
        name: uids
        description: Comma-separated list of the user IDs you wish to unblock
      responses:
        200:
          description: OK
      tags:
      - Page
      - Blocked
  /{page}/blocked/{user}:
    get:
      summary: Get Page Blocked User
      description: Checks if a user is blocked from the page
      operationId: getPageBlockedUser
      x-api-path-slug: pageblockeduser-get
      parameters:
      - in: path
        name: page
        description: Represents the ID of the page object
      - in: path
        name: user
        description: Represents the ID of a user
      responses:
        200:
          description: OK
      tags:
      - Page
      - Blocked
      - User