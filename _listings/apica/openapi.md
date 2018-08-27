swagger: "2.0"
x-collection-name: Apica
x-complete: 1
info:
  title: Scenarios API
  version: 1.0.0
host: api.pingdom.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
basePath: /
paths:
  /buckets/{bucketKey}/messages:
    delete:
      summary: Delete Buckets Messages
      description: Clear a bucket (remove all messages)..
      operationId: deleteBucketsBucketkeyMessages
      x-api-path-slug: bucketsbucketkeymessages-delete
      parameters:
      - in: path
        name: bucketKey
        description: Unique identifier for a bucket
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
      - Messages
    get:
      summary: Get Buckets Messages
      description: Retrieve a list of messages in a bucket.
      operationId: getBucketsBucketkeyMessages
      x-api-path-slug: bucketsbucketkeymessages-get
      parameters:
      - in: query
        name: before
        description: Only return messages before the given Unix timestamp
      - in: path
        name: bucketKey
        description: Unique identifier for a bucket
      - in: query
        name: count
        description: Maxiumum number of messages to return
      - in: query
        name: since
        description: Only return messages after the given Unix timestamp
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
      - Messages
    post:
      summary: Post Buckets Messages
      description: Create a message.
      operationId: postBucketsBucketkeyMessages
      x-api-path-slug: bucketsbucketkeymessages-post
      parameters:
      - in: body
        name: NewMessage
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
      - Messages
  /buckets/{bucketKey}/messages/{messageId}:
    get:
      summary: Get Buckets Messages Messageid
      description: Retrieve the details for a single message..
      operationId: getBucketsBucketkeyMessagesMessage
      x-api-path-slug: bucketsbucketkeymessagesmessageid-get
      parameters:
      - in: path
        name: bucketKey
        description: Unique identifier for a bucket
      - in: query
        name: messageId
        description: The unique identifier for this message
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
      - Messages
      - MessageId