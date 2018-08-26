---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 1
info:
  title: Compute Engine
  description: creates-and-runs-virtual-machines-on-google-cloud-platform-
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
---