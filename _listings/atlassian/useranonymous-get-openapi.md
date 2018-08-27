---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Get anonymous user
  description: "Returns information about how anonymous users are represented, like
    the\nprofile picture and display name.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to access the Confluence site ('Can use' global permission)."
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/anonymous:
    get:
      summary: Get anonymous user
      description: "Returns information about how anonymous users are represented,
        like the\nprofile picture and display name.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to access the Confluence site ('Can use' global permission)."
      operationId: com.atlassian.confluence.plugins.restapi.resources.UserResource.getAnonymousUser_get
      x-api-path-slug: useranonymous-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the user
          toexpand
      responses:
        200:
          description: OK
      tags:
      - Anonymous
      - User
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