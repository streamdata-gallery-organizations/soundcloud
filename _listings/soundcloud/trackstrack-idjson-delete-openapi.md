---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 0
info:
  title: SoundCloud Delete Track
  description: Deletes a given track
  version: 1.0.0
host: api.soundcloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tracks.json:
    get:
      summary: Get Tracks
      description: Returns a collection of tracks
      operationId: tracks.json.get
      x-api-path-slug: tracksjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
    post:
      summary: Update Tracks
      description: Uploads a track
      operationId: tracks.json.post
      x-api-path-slug: tracksjson-post
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
  /tracks/{track_id}.json:
    get:
      summary: Get Track
      description: Returns a track by track id
      operationId: tracks.track_id.json.get
      x-api-path-slug: trackstrack-idjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
    put:
      summary: Update Track
      description: Updates a given track
      operationId: tracks.track_id.json.put
      x-api-path-slug: trackstrack-idjson-put
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
    delete:
      summary: Delete Track
      description: Deletes a given track
      operationId: tracks.track_id.json.delete
      x-api-path-slug: trackstrack-idjson-delete
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
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