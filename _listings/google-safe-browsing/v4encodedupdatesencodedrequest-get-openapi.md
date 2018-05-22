---
swagger: "2.0"
x-collection-name: Google Safe Browsing
x-complete: 0
info:
  title: Google Safe Browsing API Encoded Updates
  description: Encoded Updates
  contact:
    name: Google
    url: https://google.com
  version: v4
host: safebrowsing.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v4/encodedFullHashes/{encodedRequest}:
    get:
      summary: Encode Full Hashes
      description: Encode Full Hashes
      operationId: safebrowsing.encodedFullHashes.get
      x-api-path-slug: v4encodedfullhashesencodedrequest-get
      parameters:
      - in: query
        name: clientId
        description: A client ID that (hopefully) uniquely identifies the client implementationof
          the Safe Browsing API
      - in: query
        name: clientVersion
        description: The version of the client implementation
      - in: path
        name: encodedRequest
        description: A serialized FindFullHashesRequest proto
      responses:
        200:
          description: OK
      tags:
      - Hash
  /v4/encodedUpdates/{encodedRequest}:
    get:
      summary: Encoded Updates
      description: Encoded Updates
      operationId: safebrowsing.encodedUpdates.get
      x-api-path-slug: v4encodedupdatesencodedrequest-get
      parameters:
      - in: query
        name: clientId
        description: A client ID that uniquely identifies the client implementation
          of the SafeBrowsing API
      - in: query
        name: clientVersion
        description: The version of the client implementation
      - in: path
        name: encodedRequest
        description: A serialized FetchThreatListUpdatesRequest proto
      responses:
        200:
          description: OK
      tags:
      - Updates
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