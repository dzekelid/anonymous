---
name: Starred
x-slug: starred
description: 'Better feedback for everyone, on a human scale. At Starred we like to
  work smart: working smarter to build great software, and working with smart companies
  who listen. As the feedback solution which puts the respondent first, we&rsquo;re
  empowering conversations between companies and their customers and employees. What&rsquo;s
  more, we equip them with the actionable insights they need to make better decisions
  and boost loyalty. With leading lights like Deliveroo, Heineken and Spotify already
  working with us to bring feedback to life, the road ahead for better feedback is
  looking good.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/starred-logo.png
x-kinRank: "7"
x-alexaRank: "916588"
tags: Anonymous
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/anonymous/master/_listings/starred/apis.md
specificationVersion: "0.14"
apis:
- name: Starred API - Anonymous Invitation Link
  x-api-slug: invitationlinksanonymous-post
  description: "Generate a link to a Starred survey form of your choice. \nGenerate
    from 1 up to, and including 100 anonymous links. (Anonymous is for when the recipient's
    email is not known)\n\n**Request Parameters**\n\n| Parameter | Required | Description
    |\n| ------ | ------ | ------ |\n| `form` | Required | ID of the form that will
    be sent out |\n| `fromUserEmail` | Required | Email address of the sender |\n|
    `amount` | Optional | Amount of invitation links desired. (Defaults to 1) |\n|
    `tags` | Optional | Any number of invitation tags can be listed. It is in key
    - value format, e.g. tag1=tag1 |"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/starred-logo.png
  humanURL: https://www.starred.com
  baseURL: https://example.com//
  tags: SaaS, Technology, internet, Relative Data, Service API, Feedback, Stars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/anonymous/master/_listings/starred/invitationlinksanonymous-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/anonymous/master/_listings/starred/invitationlinksanonymous-post-openapi.md
x-common:
- type: x-github
  url: https://github.com/starred-com
- type: x-twitter
  url: https://twitter.com/starred_com
- type: x-api-gallery
  url: http://standard.chartered.api.gallery.streamdata.io
- type: x-api-stack
  url: http://starred.stack.network
- type: x-blog
  url: https://www.starred.com/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/starred
- type: x-email
  url: support@starred.com
- type: x-email
  url: legal@starred.com
- type: x-integrations
  url: https://www.starred.com/integrations/
- type: x-pricing
  url: https://www.starred.com/#
- type: x-website
  url: https://www.starred.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---