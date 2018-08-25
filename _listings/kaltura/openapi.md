---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 1
info:
  title: Kaltura VPaaS
  description: building-video-experiences-consists-of-ingesting-media-files-playing-back-videos-and-reviewing-usage-and-engagement-analytics--in-between-there-is-a-world-of-nuances-required-for-your-unique-usecase-and-application--kaltura-vpaas-is-built-on-the-principles-of-atomic-services-sdks-and-tools-that-allow-you-full-control-and-flexibility-over-every-element-and-process-in-your-medias-life-cycle-
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/baseentry/action/anonymousRank:
    get:
      summary: Get Service Baseentry Action Anonymousrank
      description: Anonymously rank an entry, no validation is done on duplicate rankings.
      operationId: baseEntry.anonymousRank
      x-api-path-slug: servicebaseentryactionanonymousrank-get
      parameters:
      - in: query
        name: entryId
      - in: query
        name: No Name
      - in: query
        name: rank
      responses:
        200:
          description: OK
      tags:
      - Service
      - Baseentry
      - Action
      - AnonymousRank
---