---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 0
info:
  title: Sound Cloud Get Users Followings
  description: Returns a collection of users the user with user id is following
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
      operationId: getTracks.json
      x-api-path-slug: tracks-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
    post:
      summary: Post Tracks
      description: Uploads a track
      operationId: postTracks.json
      x-api-path-slug: tracks-json-post
      responses:
        200:
          description: OK
      tags:
      - Tracks
  /tracks/{track_id}.json:
    get:
      summary: Get Tracks Track
      description: Returns a track by track id
      operationId: getTracksTrack.json
      x-api-path-slug: trackstrack-id-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
    put:
      summary: Put Tracks Track
      description: Updates a given track
      operationId: putTracksTrack.json
      x-api-path-slug: trackstrack-id-json-put
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
    delete:
      summary: Delete Tracks Track
      description: Deletes a given track
      operationId: deleteTracksTrack.json
      x-api-path-slug: trackstrack-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
  /tracks/{track_id}/comments.json:
    get:
      summary: Get Tracks Track Comments
      description: Returns comments of a track by track id
      operationId: getTracksTrackComments.json
      x-api-path-slug: trackstrack-idcomments-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
    post:
      summary: Post Tracks Track Comments
      description: Posts a comments to a track by track id
      operationId: postTracksTrackComments.json
      x-api-path-slug: trackstrack-idcomments-json-post
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
  /tracks/{track_id}/permissions.json:
    get:
      summary: Get Tracks Track Permissions
      description: Returns all users with permission for a track by track id
      operationId: getTracksTrackPermissions.json
      x-api-path-slug: trackstrack-idpermissions-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Permissions
    put:
      summary: Put Tracks Track Permissions
      description: Updates the list of permitted users for a track by track id
      operationId: putTracksTrackPermissions.json
      x-api-path-slug: trackstrack-idpermissions-json-put
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Permissions
  /tracks/{track_id}/secret-token.json:
    get:
      summary: Get Tracks Track Secret Token
      description: Returns the secret token for a track by track id. This resource
        can only be used by the track owner.
      operationId: getTracksTrackSecretToken.json
      x-api-path-slug: trackstrack-idsecrettoken-json-get
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Secret
      - Token
    put:
      summary: Put Tracks Track Secret Token
      description: |-
        Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
                  the server and returned. This resource can only be used by the track owner.
      operationId: putTracksTrackSecretToken.json
      x-api-path-slug: trackstrack-idsecrettoken-json-put
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Secret
      - Token
  /users.json:
    get:
      summary: Get Users
      description: Returns a collection of users
      operationId: getUsers.json
      x-api-path-slug: users-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
  /users/{user_id}.json:
    get:
      summary: Get Users
      description: Returns a user by user id
      operationId: getUsersUser.json
      x-api-path-slug: usersuser-id-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
  /users/{user_id}/tracks.json:
    get:
      summary: Get Users Tracks
      description: Returns a collection of tracks uploaded by user id
      operationId: getUsersUserTracks.json
      x-api-path-slug: usersuser-idtracks-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Tracks
  /users/{user_id}/comments.json:
    get:
      summary: Get Users Comments
      description: Returns a collection of comments made by user id
      operationId: getUsersUserComments.json
      x-api-path-slug: usersuser-idcomments-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Comments
  /users/{user_id}/followings.json:
    get:
      summary: Get Users Followings
      description: Returns a collection of users the user with user id is following
      operationId: getUsersUserFollowings.json
      x-api-path-slug: usersuser-idfollowings-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followings
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