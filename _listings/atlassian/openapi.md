swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
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