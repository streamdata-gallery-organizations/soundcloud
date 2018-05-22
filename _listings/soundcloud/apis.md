---
name: SoundCloud
x-slug: soundcloud
description: SoundCloud is a global online audio distribution platform based in Berlin,
  Germany, that enables its users to upload, record, promote, and share their originally-created
  sounds. According to the company&rsquo;s data, in December 2014, the service attracts
  more than 175 million unique monthly listeners, while content creators upload about
  12 hours worth of audio every minute.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: SoundCloud
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/apis.md
specificationVersion: "0.14"
apis:
- name: SoundCloud Get Tracks
  x-api-slug: soundcloud
  description: Returns a collection of tracks
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.json
  tags: Audio,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracksjson-get-openapi.md
- name: SoundCloud Update Tracks
  x-api-slug: soundcloud
  description: Uploads a track
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks.json
  tags: Audio,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracksjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/tracksjson-post-openapi.md
- name: SoundCloud Get Track
  x-api-slug: soundcloud
  description: Returns a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Audio,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idjson-get-openapi.md
- name: SoundCloud Update Track
  x-api-slug: soundcloud
  description: Updates a given track
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Audio,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idjson-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idjson-put-openapi.md
- name: SoundCloud Delete Track
  x-api-slug: soundcloud
  description: Deletes a given track
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}.json
  tags: Audio,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idjson-delete-openapi.md
- name: SoundCloud Get Track Comment
  x-api-slug: soundcloud
  description: Returns comments of a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.json
  tags: Audio,Tracks,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcommentsjson-get-openapi.md
- name: SoundCloud Add Track Comment
  x-api-slug: soundcloud
  description: Posts a comments to a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.json
  tags: Audio,Tracks,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idcommentsjson-post-openapi.md
- name: SoundCloud Get Track Permissions
  x-api-slug: soundcloud
  description: Returns all users with permission for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.json
  tags: Audio,Tracks,Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissionsjson-get-openapi.md
- name: SoundCloud Update Track Permissions
  x-api-slug: soundcloud
  description: Updates the list of permitted users for a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/permissions.json
  tags: Audio,Tracks,Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idpermissionsjson-put-openapi.md
- name: SoundCloud Get Track Secret Token
  x-api-slug: soundcloud
  description: Returns the secret token for a track by track id. This resource can
    only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.json
  tags: Audio,Tracks,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettokenjson-get-openapi.md
- name: SoundCloud Update Track Secret Token
  x-api-slug: soundcloud
  description: |-
    Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on
              the server and returned. This resource can only be used by the track owner.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/secret-token.json
  tags: Audio,Tracks,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/trackstrack-idsecrettokenjson-put-openapi.md
- name: SoundCloud Get Users
  x-api-slug: soundcloud
  description: Returns a collection of users
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users.json
  tags: Audio,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersjson-get-openapi.md
- name: SoundCloud Get User
  x-api-slug: soundcloud
  description: Returns a user by user id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}.json
  tags: Audio,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idjson-get-openapi.md
- name: SoundCloud Get User Tracks
  x-api-slug: soundcloud
  description: Returns a collection of tracks uploaded by user id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/tracks.json
  tags: Audio,Users,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idtracksjson-get-openapi.md
- name: SoundCloud Get User Comments
  x-api-slug: soundcloud
  description: Returns a collection of comments made by user id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/comments.json
  tags: Audio,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idcommentsjson-get-openapi.md
- name: SoundCloud Get User Followings
  x-api-slug: soundcloud
  description: Returns a collection of users the user with user id is following
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings.json
  tags: Audio,Users,Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingsjson-get-openapi.md
- name: SoundCloud Get User Following
  x-api-slug: soundcloud
  description: Checks if the user with the id contact_id is in the givens user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.json
  tags: Audio,Users,Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-idjson-get-openapi.md
- name: SoundCloud Update User Following
  x-api-slug: soundcloud
  description: Adds the user with the id contact_id to the givens user's list of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.json
  tags: Audio,Users,Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-idjson-put-openapi.md
- name: SoundCloud Delete User Following
  x-api-slug: soundcloud
  description: Removes the user with the id contact_id from the givens user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followings/{contact_id}.json
  tags: Audio,Users,Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowingscontact-idjson-delete-openapi.md
- name: SoundCloud Get User Followers
  x-api-slug: soundcloud
  description: Returns a collection of users who follow the user with user id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followers.json
  tags: Audio,Users,Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowersjson-get-openapi.md
- name: SoundCloud Get User Follower
  x-api-slug: soundcloud
  description: Checks if the user with contact_id is a follower of the given user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/followers/{contact_id}.json
  tags: Audio,Users,Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfollowerscontact-idjson-get-openapi.md
- name: SoundCloud Get User Favorites
  x-api-slug: soundcloud
  description: Returns a collection of tracks favorited by the user with user id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites.json
  tags: Audio,Favorites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritesjson-get-openapi.md
- name: SoundCloud Update User Favorite
  x-api-slug: soundcloud
  description: Adds the given track to the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.json
  tags: Audio,Tracks,Favorites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-idjson-put-openapi.md
- name: SoundCloud Delete User Favorite
  x-api-slug: soundcloud
  description: Deletes the given track from the given user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/favorites/{track_id}.json
  tags: Audio,Tracks,Favorites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idfavoritestrack-idjson-delete-openapi.md
- name: SoundCloud Get User Group
  x-api-slug: soundcloud
  description: Returns a collection of groups joined by user with user id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/groups.json
  tags: Audio,Users,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idgroupsjson-get-openapi.md
- name: SoundCloud Get User Playlists
  x-api-slug: soundcloud
  description: Returns a collection of playlists created by user with user id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/playlists.json
  tags: Audio,Users,Playlists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/usersuser-idplaylistsjson-get-openapi.md
- name: SoundCloud Get Me
  x-api-slug: soundcloud
  description: Returns the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.json
  tags: Audio,Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mejson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mejson-get-openapi.md
- name: SoundCloud Update Me
  x-api-slug: soundcloud
  description: Updates the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.json
  tags: Audio,Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mejson-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mejson-put-openapi.md
- name: SoundCloud Get My Tracks
  x-api-slug: soundcloud
  description: Returns a collection of tracks uploaded by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/tracks.json
  tags: Audio,Me,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/metracksjson-get-openapi.md
- name: SoundCloud Get My Comments
  x-api-slug: soundcloud
  description: Returns a collection of comments made by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/comments.json
  tags: Audio,Me,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mecommentsjson-get-openapi.md
- name: SoundCloud Get My Followings
  x-api-slug: soundcloud
  description: Returns a collection of users the logged-in user is following
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings.json
  tags: Audio,Me,Favorites,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingsjson-get-openapi.md
- name: SoundCloud Get My Following
  x-api-slug: soundcloud
  description: Checks if the user with the id contact_id is in the logged-in user's
    list of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Audio,Me,Favorites,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-idjson-get-openapi.md
- name: SoundCloud Update My Following
  x-api-slug: soundcloud
  description: Adds the user with the id contact_id to the logged-in user's list of
    contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Audio,Me,Favorites,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-idjson-put-openapi.md
- name: SoundCloud Delete My Following
  x-api-slug: soundcloud
  description: Deletes the user with the id contact_id from the logged-in user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Audio,Me,Favorites,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowingscontact-idjson-delete-openapi.md
- name: SoundCloud Get My Followers
  x-api-slug: soundcloud
  description: Returns a collection of users who follow the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers.json
  tags: Audio,Me,Followers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowersjson-get-openapi.md
- name: SoundCloud Get My Follower
  x-api-slug: soundcloud
  description: Checks if the user with the id contact_id is a follower of the logged-in
    user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers/{contact_id}.json
  tags: Audio,Me,Favorites,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefollowerscontact-idjson-get-openapi.md
- name: SoundCloud Get My Favorites
  x-api-slug: soundcloud
  description: Returns a collection of tracks favorited by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites.json
  tags: Audio,Me,Favorites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritesjson-get-openapi.md
- name: SoundCloud Update My Favorite Track
  x-api-slug: soundcloud
  description: Adds the given track to the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.json
  tags: Audio,Me,Favorites,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-idjson-put-openapi.md
- name: SoundCloud Get My Favorite Track
  x-api-slug: soundcloud
  description: Deletes the given track from the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.json
  tags: Audio,Me,Favorites,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/mefavoritestrack-idjson-delete-openapi.md
- name: SoundCloud Get My Groups
  x-api-slug: soundcloud
  description: Returns a collection of groups joined by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/groups.json
  tags: Audio,Me,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/megroupsjson-get-openapi.md
- name: SoundCloud Get My Playlists
  x-api-slug: soundcloud
  description: Returns a collection of playlists created by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/playlists.json
  tags: Audio,Me,Playlists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/meplaylistsjson-get-openapi.md
- name: SoundCloud Get Playlists
  x-api-slug: soundcloud
  description: Returns a collection of playlists
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////playlists.json
  tags: Audio,Playlists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlistsjson-get-openapi.md
- name: SoundCloud Get Playlist
  x-api-slug: soundcloud
  description: Returns a playlist by playlist id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////playlists/{playlist_id}.json
  tags: Audio,Playlists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/playlistsplaylist-idjson-get-openapi.md
- name: SoundCloud Get Groups
  x-api-slug: soundcloud
  description: Returns a collection of groups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups.json
  tags: Audio,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsjson-get-openapi.md
- name: SoundCloud Get Group
  x-api-slug: soundcloud
  description: Returns a group by group id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}.json
  tags: Audio,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idjson-get-openapi.md
- name: SoundCloud Get Group Users
  x-api-slug: soundcloud
  description: Returns a combined collection of moderators, members and contributors
    of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/users.json
  tags: Audio,Groups,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idusersjson-get-openapi.md
- name: SoundCloud Get Group Moderators
  x-api-slug: soundcloud
  description: Returns a collection of moderators of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/moderators.json
  tags: Audio,Groups,Moderators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmoderatorsjson-get-openapi.md
- name: SoundCloud Get Group Members
  x-api-slug: soundcloud
  description: Returns a collection of members of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/members.json
  tags: Audio,Groups,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idmembersjson-get-openapi.md
- name: SoundCloud Get Group Contributors
  x-api-slug: soundcloud
  description: Returns a collection of contributors of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/contributors.json
  tags: Audio,Groups,Contributors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idcontributorsjson-get-openapi.md
- name: SoundCloud Get Group Tracks
  x-api-slug: soundcloud
  description: Returns a collection of tracks contributed to the group with group
    id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/tracks.json
  tags: Audio,Groups,Tracks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/groupsgroup-idtracksjson-get-openapi.md
- name: SoundCloud Get Comments
  x-api-slug: soundcloud
  description: Returns a comment by comment id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////comments/{comment_id}.json
  tags: Audio,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/commentscomment-idjson-get-openapi.md
- name: SoundCloud Get Resolve
  x-api-slug: soundcloud
  description: Translates a website URI into an API URI
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////resolve.json
  tags: Audio,Resolve
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/soundcloud/master/_listings/soundcloud/resolvejson-get-openapi.md
- name: SoundCloud
  x-api-slug: soundcloud
  description: SoundCloud is a global online audio distribution platform based in
    Berlin, Germany, that enables its users to upload, record, promote, and share
    their originally-created sounds. According to the company&rsquo;s data, in December
    2014, the service attracts more than 175 million unique monthly listeners, while
    content creators upload about 12 hours worth of audio every minute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Soundcloud-logo.jpg
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
- type: x-website
  url: http://soundcloud.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---