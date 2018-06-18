---
swagger: "2.0"
x-collection-name: Apica
x-complete: 1
info:
  title: Messages API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /buckets/{bucketKey}/messages:
    delete:
      summary: Clear a bucket (remove all messages).
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
      summary: Retrieve a list of messages in a bucket
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
      summary: Create a message
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
      summary: Retrieve the details for a single message.
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
---