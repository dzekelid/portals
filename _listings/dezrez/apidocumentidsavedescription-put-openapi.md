---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Save the document description. Used for the image caption for the
    portals.
  version: 1.0.0
  description: Save the document description. used for the image caption for the portals..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/document/{id}/savedescription:
    put:
      summary: Save the document description. Used for the image caption for the portals.
      description: Save the document description. used for the image caption for the
        portals..
      operationId: Document_SaveDescriptionByidBydescription
      x-api-path-slug: apidocumentidsavedescription-put
      parameters:
      - in: query
        name: description
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Document
      - Description
      - ""
      - Usedthe
      - Image
      - Captionthe
      - Portals
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