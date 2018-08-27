swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/todo/canceltasks:
    put:
      summary: Cancel a single or multiple tasks from a to-do bucket
      description: Cancel a single or multiple tasks from a to-do bucket.
      operationId: DefaultToDo_CancelTasksBycancelTasksCommandData
      x-api-path-slug: apitodocanceltasks-put
      parameters:
      - in: body
        name: cancelTasksCommandData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Single
      - Multiple
      - Tasks
      - From
      - To-do
      - Bucket