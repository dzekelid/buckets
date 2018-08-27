---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Set Usage Export Bucket
  description: Enables the usage export feature and sets the usage export bucket where
    reports are stored. If you provide an empty request body using this method, the
    usage export feature will be disabled.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/setUsageExportBucket:
    post:
      summary: Set Usage Export Bucket
      description: Enables the usage export feature and sets the usage export bucket
        where reports are stored. If you provide an empty request body using this
        method, the usage export feature will be disabled.
      operationId: compute.projects.setUsageExportBucket
      x-api-path-slug: projectsetusageexportbucket-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Bucket
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