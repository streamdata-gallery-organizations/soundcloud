---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 0
info:
  title: SoundCloud Update My Favorite Track
  description: Adds the given track to the logged-in user's list of favorites.
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
  /tracks/{track_id}/comments.json:
    get:
      summary: Get Track Comment
      description: Returns comments of a track by track id
      operationId: tracks.track_id.comments.json.get
      x-api-path-slug: trackstrack-idcommentsjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
      - Comments
    post:
      summary: Add Track Comment
      description: Posts a comments to a track by track id
      operationId: tracks.track_id.comments.json.post
      x-api-path-slug: trackstrack-idcommentsjson-post
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
      - Comments
  /tracks/{track_id}/permissions.json:
    get:
      summary: Get Track Permissions
      description: Returns all users with permission for a track by track id
      operationId: tracks.track_id.permissions.json.get
      x-api-path-slug: trackstrack-idpermissionsjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
      - Permissions
    put:
      summary: Update Track Permissions
      description: Updates the list of permitted users for a track by track id
      operationId: tracks.track_id.permissions.json.put
      x-api-path-slug: trackstrack-idpermissionsjson-put
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
      - Permissions
  /tracks/{track_id}/secret-token.json:
    get:
      summary: Get Track Secret Token
      description: Returns the secret token for a track by track id. This resource
        can only be used by the track owner.
      operationId: tracks.track_id.secret_token.json.get
      x-api-path-slug: trackstrack-idsecrettokenjson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
      - Tokens
    put:
      summary: Update Track Secret Token
      description: |-
        Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
                  the server and returned. This resource can only be used by the track owner.
      operationId: tracks.track_id.secret_token.json.put
      x-api-path-slug: trackstrack-idsecrettokenjson-put
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
      - Tokens
  /users.json:
    get:
      summary: Get Users
      description: Returns a collection of users
      operationId: users.json.get
      x-api-path-slug: usersjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
  /users/{user_id}.json:
    get:
      summary: Get User
      description: Returns a user by user id
      operationId: users.user_id.json.get
      x-api-path-slug: usersuser-idjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
  /users/{user_id}/tracks.json:
    get:
      summary: Get User Tracks
      description: Returns a collection of tracks uploaded by user id
      operationId: users.user_id.tracks.json.get
      x-api-path-slug: usersuser-idtracksjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Tracks
  /users/{user_id}/comments.json:
    get:
      summary: Get User Comments
      description: Returns a collection of comments made by user id
      operationId: users.user_id.comments.json.get
      x-api-path-slug: usersuser-idcommentsjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Comments
  /users/{user_id}/followings.json:
    get:
      summary: Get User Followings
      description: Returns a collection of users the user with user id is following
      operationId: users.user_id.followings.json.get
      x-api-path-slug: usersuser-idfollowingsjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Followers
  /users/{user_id}/followings/{contact_id}.json:
    get:
      summary: Get User Following
      description: Checks if the user with the id contact_id is in the givens user's
        list of contacts.
      operationId: users.user_id.followings.contact_id.json.get
      x-api-path-slug: usersuser-idfollowingscontact-idjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Followers
    put:
      summary: Update User Following
      description: Adds the user with the id contact_id to the givens user's list
        of contacts.
      operationId: users.user_id.followings.contact_id.json.put
      x-api-path-slug: usersuser-idfollowingscontact-idjson-put
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Followers
    delete:
      summary: Delete User Following
      description: Removes the user with the id contact_id from the givens user's
        list of contacts.
      operationId: users.user_id.followings.contact_id.json.delete
      x-api-path-slug: usersuser-idfollowingscontact-idjson-delete
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Followers
  /users/{user_id}/followers.json:
    get:
      summary: Get User Followers
      description: Returns a collection of users who follow the user with user id
      operationId: users.user_id.followers.json.get
      x-api-path-slug: usersuser-idfollowersjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Followers
  /users/{user_id}/followers/{contact_id}.json:
    get:
      summary: Get User Follower
      description: Checks if the user with contact_id is a follower of the given user.
      operationId: users.user_id.followers.contact_id.json.get
      x-api-path-slug: usersuser-idfollowerscontact-idjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Followers
  /users/{user_id}/favorites.json:
    get:
      summary: Get User Favorites
      description: Returns a collection of tracks favorited by the user with user
        id
      operationId: users.user_id.favorites.json.get
      x-api-path-slug: usersuser-idfavoritesjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Favorites
  /users/{user_id}/favorites/{track_id}.json:
    put:
      summary: Update User Favorite
      description: Adds the given track to the given user's list of favorites.
      operationId: users.user_id.favorites.track_id.json.put
      x-api-path-slug: usersuser-idfavoritestrack-idjson-put
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
      - Favorites
    delete:
      summary: Delete User Favorite
      description: Deletes the given track from the given user's list of favorites.
      operationId: users.user_id.favorites.track_id.json.delete
      x-api-path-slug: usersuser-idfavoritestrack-idjson-delete
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Tracks
      - Favorites
  /users/{user_id}/groups.json:
    get:
      summary: Get User Group
      description: Returns a collection of groups joined by user with user id
      operationId: users.user_id.groups.json.get
      x-api-path-slug: usersuser-idgroupsjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Groups
  /users/{user_id}/playlists.json:
    get:
      summary: Get User Playlists
      description: Returns a collection of playlists created by user with user id
      operationId: users.user_id.playlists.json.get
      x-api-path-slug: usersuser-idplaylistsjson-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Users
      - Playlists
  /me.json:
    get:
      summary: Get Me
      description: Returns the logged-in user
      operationId: me.json.get
      x-api-path-slug: mejson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
    put:
      summary: Update Me
      description: Updates the logged-in user
      operationId: me.json.put
      x-api-path-slug: mejson-put
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
  /me/tracks.json:
    get:
      summary: Get My Tracks
      description: Returns a collection of tracks uploaded by logged-in user
      operationId: me.tracks.json.get
      x-api-path-slug: metracksjson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Tracks
  /me/comments.json:
    get:
      summary: Get My Comments
      description: Returns a collection of comments made by logged-in user
      operationId: me.comments.json.get
      x-api-path-slug: mecommentsjson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Comments
  /me/followings.json:
    get:
      summary: Get My Followings
      description: Returns a collection of users the logged-in user is following
      operationId: me.followings.json.get
      x-api-path-slug: mefollowingsjson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Favorites
      - Tracks
  /me/followings/{contact_id}.json:
    get:
      summary: Get My Following
      description: Checks if the user with the id contact_id is in the logged-in user's
        list of contacts.
      operationId: me.followings.contact_id.json.get
      x-api-path-slug: mefollowingscontact-idjson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Favorites
      - Tracks
    put:
      summary: Update My Following
      description: Adds the user with the id contact_id to the logged-in user's list
        of contacts.
      operationId: me.followings.contact_id.json.put
      x-api-path-slug: mefollowingscontact-idjson-put
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Favorites
      - Tracks
    delete:
      summary: Delete My Following
      description: Deletes the user with the id contact_id from the logged-in user's
        list of contacts.
      operationId: me.followings.contact_id.json.delete
      x-api-path-slug: mefollowingscontact-idjson-delete
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Favorites
      - Tracks
  /me/followers.json:
    get:
      summary: Get My Followers
      description: Returns a collection of users who follow the logged-in user
      operationId: me.followers.json.get
      x-api-path-slug: mefollowersjson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Followers
  /me/followers/{contact_id}.json:
    get:
      summary: Get My Follower
      description: Checks if the user with the id contact_id is a follower of the
        logged-in user
      operationId: me.followers.contact_id.json.get
      x-api-path-slug: mefollowerscontact-idjson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Favorites
      - Tracks
  /me/favorites.json:
    get:
      summary: Get My Favorites
      description: Returns a collection of tracks favorited by the logged-in user
      operationId: me.favorites.json.get
      x-api-path-slug: mefavoritesjson-get
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Favorites
  /me/favorites/{track_id}.json:
    put:
      summary: Update My Favorite Track
      description: Adds the given track to the logged-in user's list of favorites.
      operationId: me.favorites.track_id.json.put
      x-api-path-slug: mefavoritestrack-idjson-put
      responses:
        200:
          description: OK
      tags:
      - Audio
      - Me
      - Favorites
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