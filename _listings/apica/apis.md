---
name: Apica
x-slug: apica
description: Apica???s performance testing and monitoring solutions provide critical
  peak performance data and 24/7 monitoring of applications and sites around the world.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
x-kinRank: "7"
x-alexaRank: "827487"
tags: Buckets
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/apica/apis.md
specificationVersion: "0.14"
apis:
- name: Messages API Clear a bucket (remove all messages).
  x-api-slug: messages-api
  description: Clear a bucket (remove all messages)..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///buckets/{bucketKey}/messages
  tags: Buckets,BucketKey,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/apica/bucketsbucketkeymessages-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/apica/bucketsbucketkeymessages-delete-openapi.md
- name: Messages API Retrieve a list of messages in a bucket
  x-api-slug: messages-api
  description: Retrieve a list of messages in a bucket.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///buckets/{bucketKey}/messages
  tags: Buckets,BucketKey,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/apica/bucketsbucketkeymessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/apica/bucketsbucketkeymessages-get-openapi.md
- name: Messages API Create a message
  x-api-slug: messages-api
  description: Create a message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///buckets/{bucketKey}/messages
  tags: Buckets,BucketKey,Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/apica/bucketsbucketkeymessages-post-openapi.md
- name: Messages API Retrieve the details for a single message.
  x-api-slug: messages-api
  description: Retrieve the details for a single message..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///buckets/{bucketKey}/messages/{messageId}
  tags: Buckets,BucketKey,Messages,MessageId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/apica/bucketsbucketkeymessagesmessageid-get-openapi.md
- name: Messages API
  x-api-slug: messages-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Buckets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/buckets/master/_listings/apica/openapi.md
x-common:
- type: x-blog
  url: https://www.apicasystem.com/blog/
- type: x-blog-rss
  url: https://www.apicasystem.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/apica
- type: x-developer
  url: http://api-wpm.apicasystem.com/v3/help
- type: x-documentation
  url: https://api-wpm.apicasystem.com/v3/Help
- type: x-email
  url: sales@apicasystems.com
- type: x-email
  url: swesales@apicasystems.com
- type: x-email
  url: support@apicasystems.com
- type: x-email
  url: operations@apicasystem.com
- type: x-github
  url: https://github.com/ApicaSystem
- type: x-twitter
  url: https://twitter.com/apicasystems
- type: x-website
  url: https://www.apicasystem.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---