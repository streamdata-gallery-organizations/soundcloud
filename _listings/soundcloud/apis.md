---
name: SoundCloud
x-slug: soundcloud
description: SoundCloud is a music and podcast streaming platform that lets you listen
  to millions of songs from around the world, or upload your own. Start listening
  now!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
x-kinRank: "9"
x-alexaRank: "114"
tags: SoundCloud
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/apis.md
specificationVersion: "0.14"
apis:
- name: Sound Cloud Get Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.json
  tags: Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracks-json-get-openapi.md
- name: Sound Cloud Post Tracks
  x-api-slug: sound-cloud
  description: Uploads a track
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.json
  tags: Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracks-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracks-json-post-openapi.md
- name: Sound Cloud Get Tracks Track
  x-api-slug: sound-cloud
  description: Returns a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Tracks,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-json-get-openapi.md
- name: Sound Cloud Put Tracks Track
  x-api-slug: sound-cloud
  description: Updates a given track
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Tracks,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-json-put-openapi.md
- name: Sound Cloud Delete Tracks Track
  x-api-slug: sound-cloud
  description: Deletes a given track
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Tracks,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-json-delete-openapi.md
- name: Sound Cloud Get Tracks Track Comments
  x-api-slug: sound-cloud
  description: Returns comments of a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.json
  tags: Tracks,Track,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcomments-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcomments-json-get-openapi.md
- name: Sound Cloud Post Tracks Track Comments
  x-api-slug: sound-cloud
  description: Posts a comments to a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.json
  tags: Tracks,Track,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcomments-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcomments-json-post-openapi.md
- name: Sound Cloud Get Tracks Track Permissions
  x-api-slug: sound-cloud
  description: Returns all users with permission for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.json
  tags: Tracks,Track,Permissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissions-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissions-json-get-openapi.md
- name: Sound Cloud Put Tracks Track Permissions
  x-api-slug: sound-cloud
  description: Updates the list of permitted users for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.json
  tags: Tracks,Track,Permissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissions-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissions-json-put-openapi.md
- name: Sound Cloud Get Tracks Track Secret Token
  x-api-slug: sound-cloud
  description: Returns the secret token for a track by track id. This resource can
    only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.json
  tags: Tracks,Track,Secret,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettoken-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettoken-json-get-openapi.md
- name: Sound Cloud Put Tracks Track Secret Token
  x-api-slug: sound-cloud
  description: |-
    Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
              the server and returned. This resource can only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.json
  tags: Tracks,Track,Secret,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettoken-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettoken-json-put-openapi.md
- name: Sound Cloud Get Users
  x-api-slug: sound-cloud
  description: Returns a collection of users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users.json
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/users-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/users-json-get-openapi.md
- name: Sound Cloud Get Users
  x-api-slug: sound-cloud
  description: Returns a user by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}.json
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-id-json-get-openapi.md
- name: Sound Cloud Get Users Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/tracks.json
  tags: Users,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idtracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idtracks-json-get-openapi.md
- name: Sound Cloud Get Users Comments
  x-api-slug: sound-cloud
  description: Returns a collection of comments made by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/comments.json
  tags: Users,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idcomments-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idcomments-json-get-openapi.md
- name: Sound Cloud Get Users Followings
  x-api-slug: sound-cloud
  description: Returns a collection of users the user with user id is following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings.json
  tags: Users,Followings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowings-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowings-json-get-openapi.md
- name: Sound Cloud Get Users Followings Contact
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is in the givens user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.json
  tags: Users,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-json-get-openapi.md
- name: Sound Cloud Put Users Followings Contact
  x-api-slug: sound-cloud
  description: Adds the user with the id contact_id to the givens user's list of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.json
  tags: Users,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-json-put-openapi.md
- name: Sound Cloud Delete Users Followings Contact
  x-api-slug: sound-cloud
  description: Removes the user with the id contact_id from the givens user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.json
  tags: Users,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-json-delete-openapi.md
- name: Sound Cloud Get Users Followers
  x-api-slug: sound-cloud
  description: Returns a collection of users who follow the user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followers.json
  tags: Users,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowers-json-get-openapi.md
- name: Sound Cloud Get Users Followers Contact
  x-api-slug: sound-cloud
  description: Checks if the user with contact_id is a follower of the given user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followers/{contact_id}.json
  tags: Users,Followers,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowerscontact-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowerscontact-id-json-get-openapi.md
- name: Sound Cloud Get Users Favorites
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites.json
  tags: Users,Favorites
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavorites-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavorites-json-get-openapi.md
- name: Sound Cloud Put Users Favorites Track
  x-api-slug: sound-cloud
  description: Adds the given track to the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.json
  tags: Users,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-id-json-put-openapi.md
- name: Sound Cloud Delete Users Favorites Track
  x-api-slug: sound-cloud
  description: Deletes the given track from the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.json
  tags: Users,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-id-json-delete-openapi.md
- name: Sound Cloud Get Users Groups
  x-api-slug: sound-cloud
  description: Returns a collection of groups joined by user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/groups.json
  tags: Users,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idgroups-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idgroups-json-get-openapi.md
- name: Sound Cloud Get Users Playlists
  x-api-slug: sound-cloud
  description: Returns a collection of playlists created by user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/playlists.json
  tags: Users,Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idplaylists-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idplaylists-json-get-openapi.md
- name: Sound Cloud Get Me
  x-api-slug: sound-cloud
  description: Returns the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.json
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/me-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/me-json-get-openapi.md
- name: Sound Cloud Put Me
  x-api-slug: sound-cloud
  description: Updates the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.json
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/me-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/me-json-put-openapi.md
- name: Sound Cloud Get Me Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/tracks.json
  tags: Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/metracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/metracks-json-get-openapi.md
- name: Sound Cloud Get Me Comments
  x-api-slug: sound-cloud
  description: Returns a collection of comments made by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/comments.json
  tags: Me,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mecomments-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mecomments-json-get-openapi.md
- name: Sound Cloud Get Me Followings
  x-api-slug: sound-cloud
  description: Returns a collection of users the logged-in user is following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings.json
  tags: Me,Followings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowings-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowings-json-get-openapi.md
- name: Sound Cloud Get Me Followings Contact
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is in the logged-in user's
    list of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Me,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-json-get-openapi.md
- name: Sound Cloud Put Me Followings Contact
  x-api-slug: sound-cloud
  description: Adds the user with the id contact_id to the logged-in user's list of
    contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Me,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-json-put-openapi.md
- name: Sound Cloud Delete Me Followings Contact
  x-api-slug: sound-cloud
  description: Deletes the user with the id contact_id from the logged-in user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Me,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-json-delete-openapi.md
- name: Sound Cloud Get Me Followers
  x-api-slug: sound-cloud
  description: Returns a collection of users who follow the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers.json
  tags: Me,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowers-json-get-openapi.md
- name: Sound Cloud Get Me Followers Contact
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is a follower of the logged-in
    user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers/{contact_id}.json
  tags: Me,Followers,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowerscontact-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowerscontact-id-json-get-openapi.md
- name: Sound Cloud Get Me Favorites
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites.json
  tags: Me,Favorites
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavorites-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavorites-json-get-openapi.md
- name: Sound Cloud Put Me Favorites Track
  x-api-slug: sound-cloud
  description: Adds the given track to the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.json
  tags: Me,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-id-json-put-openapi.md
- name: Sound Cloud Delete Me Favorites Track
  x-api-slug: sound-cloud
  description: Deletes the given track from the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.json
  tags: Me,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-id-json-delete-openapi.md
- name: Sound Cloud Get Me Groups
  x-api-slug: sound-cloud
  description: Returns a collection of groups joined by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/groups.json
  tags: Me,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/megroups-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/megroups-json-get-openapi.md
- name: Sound Cloud Get Me Playlists
  x-api-slug: sound-cloud
  description: Returns a collection of playlists created by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/playlists.json
  tags: Me,Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/meplaylists-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/meplaylists-json-get-openapi.md
- name: Sound Cloud Get Playlists
  x-api-slug: sound-cloud
  description: Returns a collection of playlists
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////playlists.json
  tags: Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlists-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlists-json-get-openapi.md
- name: Sound Cloud Get Playlists Playlist
  x-api-slug: sound-cloud
  description: Returns a playlist by playlist id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////playlists/{playlist_id}.json
  tags: Playlists,Playlist
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlistsplaylist-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlistsplaylist-id-json-get-openapi.md
- name: Sound Cloud Get Groups
  x-api-slug: sound-cloud
  description: Returns a collection of groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups.json
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groups-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groups-json-get-openapi.md
- name: Sound Cloud Get Groups
  x-api-slug: sound-cloud
  description: Returns a group by group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}.json
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-id-json-get-openapi.md
- name: Sound Cloud Get Groups Users
  x-api-slug: sound-cloud
  description: Returns a combined collection of moderators, members and contributors
    of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/users.json
  tags: Groups,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idusers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idusers-json-get-openapi.md
- name: Sound Cloud Get Groups Moderators
  x-api-slug: sound-cloud
  description: Returns a collection of moderators of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/moderators.json
  tags: Groups,Moderators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmoderators-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmoderators-json-get-openapi.md
- name: Sound Cloud Get Groups Members
  x-api-slug: sound-cloud
  description: Returns a collection of members of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/members.json
  tags: Groups,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmembers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmembers-json-get-openapi.md
- name: Sound Cloud Get Groups Contributors
  x-api-slug: sound-cloud
  description: Returns a collection of contributors of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/contributors.json
  tags: Groups,Contributors
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idcontributors-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idcontributors-json-get-openapi.md
- name: Sound Cloud Get Groups Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks contributed to the group with group
    id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/tracks.json
  tags: Groups,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idtracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idtracks-json-get-openapi.md
- name: Sound Cloud Get Comments
  x-api-slug: sound-cloud
  description: Returns a comment by comment id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////comments/{comment_id}.json
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/commentscomment-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/commentscomment-id-json-get-openapi.md
- name: Sound Cloud Get Resolve
  x-api-slug: sound-cloud
  description: Translates a website URI into an API URI
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////resolve.json
  tags: Resolve
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/resolve-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/resolve-json-get-openapi.md
- name: Sound Cloud Get Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.{format}
  tags: Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracks-format-get-openapi.md
- name: Sound Cloud Post Tracks. Format
  x-api-slug: sound-cloud
  description: Post tracks. format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.{format}
  tags: Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracks-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracks-format-post-openapi.md
- name: Sound Cloud Get Tracks Track . Format
  x-api-slug: sound-cloud
  description: Returns a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.{format}
  tags: Tracks,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-format-get-openapi.md
- name: Sound Cloud Put Tracks Track . Format
  x-api-slug: sound-cloud
  description: Put tracks track . format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.{format}
  tags: Tracks,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-format-put-openapi.md
- name: Sound Cloud Delete Tracks Track . Format
  x-api-slug: sound-cloud
  description: Delete tracks track . format.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.{format}
  tags: Tracks,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-id-format-delete-openapi.md
- name: Sound Cloud Get Tracks Track Comments. Format
  x-api-slug: sound-cloud
  description: Returns comments of a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.{format}
  tags: Tracks,Track,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcomments-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcomments-format-get-openapi.md
- name: Sound Cloud Post Tracks Track Comments. Format
  x-api-slug: sound-cloud
  description: Posts a comments to a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.{format}
  tags: Tracks,Track,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcomments-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcomments-format-post-openapi.md
- name: Sound Cloud Get Tracks Track Permissions. Format
  x-api-slug: sound-cloud
  description: Returns all users with permission for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.{format}
  tags: Tracks,Track,Permissions,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissions-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissions-format-get-openapi.md
- name: Sound Cloud Put Tracks Track Permissions. Format
  x-api-slug: sound-cloud
  description: Updates the list of permitted users for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.{format}
  tags: Tracks,Track,Permissions,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissions-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissions-format-put-openapi.md
- name: Sound Cloud Get Tracks Track Secret Token. Format
  x-api-slug: sound-cloud
  description: Returns the secret token for a track by track id. This resource can
    only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.{format}
  tags: Tracks,Track,Secret,Token,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettoken-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettoken-format-get-openapi.md
- name: Sound Cloud Put Tracks Track Secret Token. Format
  x-api-slug: sound-cloud
  description: |-
    Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
                        the server and returned. This resource can only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.{format}
  tags: Tracks,Track,Secret,Token,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettoken-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettoken-format-put-openapi.md
- name: Sound Cloud Get Users. Format
  x-api-slug: sound-cloud
  description: Returns a collection of users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users.{format}
  tags: Users,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/users-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/users-format-get-openapi.md
- name: Sound Cloud Get Users . Format
  x-api-slug: sound-cloud
  description: Returns a user by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}.{format}
  tags: Users,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-id-format-get-openapi.md
- name: Sound Cloud Get Users Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/tracks.{format}
  tags: Users,Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idtracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idtracks-format-get-openapi.md
- name: Sound Cloud Get Users Comments. Format
  x-api-slug: sound-cloud
  description: Returns a collection of comments made by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/comments.{format}
  tags: Users,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idcomments-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idcomments-format-get-openapi.md
- name: Sound Cloud Get Users Followings. Format
  x-api-slug: sound-cloud
  description: Returns a collection of users the user with user id is following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings.{format}
  tags: Users,Followings,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowings-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowings-format-get-openapi.md
- name: Sound Cloud Get Users Followings Contact . Format
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is in the givens user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.{format}
  tags: Users,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-format-get-openapi.md
- name: Sound Cloud Put Users Followings Contact . Format
  x-api-slug: sound-cloud
  description: Adds the user with the id contact_id to the givens user's list of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.{format}
  tags: Users,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-format-put-openapi.md
- name: Sound Cloud Delete Users Followings Contact . Format
  x-api-slug: sound-cloud
  description: Removes the user with the id contact_id from the givens user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.{format}
  tags: Users,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-id-format-delete-openapi.md
- name: Sound Cloud Get Users Followers. Format
  x-api-slug: sound-cloud
  description: Returns a collection of users who follow the user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followers.{format}
  tags: Users,Followers,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowers-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowers-format-get-openapi.md
- name: Sound Cloud Get Users Followers Contact . Format
  x-api-slug: sound-cloud
  description: Checks if the user with contact_id is a follower of the given user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followers/{contact_id}.{format}
  tags: Users,Followers,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowerscontact-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowerscontact-id-format-get-openapi.md
- name: Sound Cloud Get Users Favorites. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites.{format}
  tags: Users,Favorites,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavorites-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavorites-format-get-openapi.md
- name: Sound Cloud Put Users Favorites Track . Format
  x-api-slug: sound-cloud
  description: Adds the given track to the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.{format}
  tags: Users,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-id-format-put-openapi.md
- name: Sound Cloud Delete Users Favorites Track . Format
  x-api-slug: sound-cloud
  description: Deletes the given track from the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.{format}
  tags: Users,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-id-format-delete-openapi.md
- name: Sound Cloud Get Users Groups. Format
  x-api-slug: sound-cloud
  description: Returns a collection of groups joined by user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/groups.{format}
  tags: Users,Groups,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idgroups-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idgroups-format-get-openapi.md
- name: Sound Cloud Get Users Playlists. Format
  x-api-slug: sound-cloud
  description: Returns a collection of playlists created by user with user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/playlists.{format}
  tags: Users,Playlists,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idplaylists-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idplaylists-format-get-openapi.md
- name: Sound Cloud Get Me. Format
  x-api-slug: sound-cloud
  description: Returns the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.{format}
  tags: Me,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/me-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/me-format-get-openapi.md
- name: Sound Cloud Put Me. Format
  x-api-slug: sound-cloud
  description: Updates the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.{format}
  tags: Me,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/me-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/me-format-put-openapi.md
- name: Sound Cloud Get Me Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/tracks.{format}
  tags: Me,Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/metracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/metracks-format-get-openapi.md
- name: Sound Cloud Get Me Comments. Format
  x-api-slug: sound-cloud
  description: Returns a collection of comments made by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/comments.{format}
  tags: Me,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mecomments-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mecomments-format-get-openapi.md
- name: Sound Cloud Get Me Followings. Format
  x-api-slug: sound-cloud
  description: Returns a collection of users the logged-in user is following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings.{format}
  tags: Me,Followings,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowings-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowings-format-get-openapi.md
- name: Sound Cloud Get Me Followings Contact . Format
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is in the logged-in user's
    list of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.{format}
  tags: Me,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-format-get-openapi.md
- name: Sound Cloud Put Me Followings Contact . Format
  x-api-slug: sound-cloud
  description: Adds the user with the id contact_id to the logged-in user's list of
    contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.{format}
  tags: Me,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-format-put-openapi.md
- name: Sound Cloud Delete Me Followings Contact . Format
  x-api-slug: sound-cloud
  description: Deletes the user with the id contact_id from the logged-in user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.{format}
  tags: Me,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-id-format-delete-openapi.md
- name: Sound Cloud Get Me Followers. Format
  x-api-slug: sound-cloud
  description: Returns a collection of users who follow the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers.{format}
  tags: Me,Followers,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowers-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowers-format-get-openapi.md
- name: Sound Cloud Get Me Followers Contact . Format
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is a follower of the logged-in
    user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers/{contact_id}.{format}
  tags: Me,Followers,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowerscontact-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowerscontact-id-format-get-openapi.md
- name: Sound Cloud Get Me Favorites. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites.{format}
  tags: Me,Favorites,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavorites-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavorites-format-get-openapi.md
- name: Sound Cloud Put Me Favorites Track . Format
  x-api-slug: sound-cloud
  description: Adds the given track to the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.{format}
  tags: Me,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-id-format-put-openapi.md
- name: Sound Cloud Delete Me Favorites Track . Format
  x-api-slug: sound-cloud
  description: Deletes the given track from the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.{format}
  tags: Me,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-id-format-delete-openapi.md
- name: Sound Cloud Get Me Groups. Format
  x-api-slug: sound-cloud
  description: Returns a collection of groups joined by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/groups.{format}
  tags: Me,Groups,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/megroups-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/megroups-format-get-openapi.md
- name: Sound Cloud Get Me Playlists. Format
  x-api-slug: sound-cloud
  description: Returns a collection of playlists created by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/playlists.{format}
  tags: Me,Playlists,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/meplaylists-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/meplaylists-format-get-openapi.md
- name: Sound Cloud Get Playlists. Format
  x-api-slug: sound-cloud
  description: Returns a collection of playlists
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////playlists.{format}
  tags: Playlists,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlists-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlists-format-get-openapi.md
- name: Sound Cloud Get Playlists Playlist . Format
  x-api-slug: sound-cloud
  description: Returns a playlist by playlist id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////playlists/{playlist_id}.{format}
  tags: Playlists,Playlist,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlistsplaylist-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlistsplaylist-id-format-get-openapi.md
- name: Sound Cloud Get Groups. Format
  x-api-slug: sound-cloud
  description: Returns a collection of groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups.{format}
  tags: Groups,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groups-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groups-format-get-openapi.md
- name: Sound Cloud Get Groups . Format
  x-api-slug: sound-cloud
  description: Returns a group by group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}.{format}
  tags: Groups,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-id-format-get-openapi.md
- name: Sound Cloud Get Groups Users. Format
  x-api-slug: sound-cloud
  description: Returns a combined collection of moderators, members and contributors
    of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/users.{format}
  tags: Groups,Users,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idusers-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idusers-format-get-openapi.md
- name: Sound Cloud Get Groups Moderators. Format
  x-api-slug: sound-cloud
  description: Returns a collection of moderators of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/moderators.{format}
  tags: Groups,Moderators,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmoderators-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmoderators-format-get-openapi.md
- name: Sound Cloud Get Groups Members. Format
  x-api-slug: sound-cloud
  description: Returns a collection of members of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/members.{format}
  tags: Groups,Members,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmembers-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmembers-format-get-openapi.md
- name: Sound Cloud Get Groups Contributors. Format
  x-api-slug: sound-cloud
  description: Returns a collection of contributors of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/contributors.{format}
  tags: Groups,Contributors,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idcontributors-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idcontributors-format-get-openapi.md
- name: Sound Cloud Get Groups Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks contributed to the group with group
    id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/tracks.{format}
  tags: Groups,Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idtracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idtracks-format-get-openapi.md
- name: Sound Cloud Get Comments . Format
  x-api-slug: sound-cloud
  description: Returns a comment by comment id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////comments/{comment_id}.{format}
  tags: Comments,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/commentscomment-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/commentscomment-id-format-get-openapi.md
- name: Sound Cloud Get Resolve. Format
  x-api-slug: sound-cloud
  description: Translates a website URI into an API URI
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////resolve.{format}
  tags: Resolve,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/resolve-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/resolve-format-get-openapi.md
- name: Sound Cloud
  x-api-slug: sound-cloud
  description: SoundCloud is a music and podcast streaming platform that lets you
    listen to millions of songs from around the world, or upload your own. Start listening
    now!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com//
  tags: SoundCloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/openapi.md
x-common:
- type: x-base
  url: https://api.soundcloud.com
- type: x-blog
  url: http://blog.soundcloud.com
- type: x-blog-rss
  url: http://blog.soundcloud.com/feed/
- type: x-console
  url: https://developers.soundcloud.com/console
- type: x-crunchbase
  url: https://crunchbase.com/organization/soundcloud
- type: x-crunchbase
  url: http://www.crunchbase.com/company/soundcloud
- type: x-developer
  url: http://developers.soundcloud.com
- type: x-github
  url: https://github.com/soundcloud
- type: x-pricing
  url: https://on.soundcloud.com/
- type: x-privacy
  url: https://soundcloud.com/pages/privacy
- type: x-support
  url: https://soundcloud.com/imprint
- type: x-terms-of-service
  url: https://soundcloud.com/terms-of-use
- type: x-twitter
  url: https://twitter.com/soundcloudapi
- type: x-twitter
  url: https://twitter.com/SoundCloud
- type: x-website
  url: http://soundcloud.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---