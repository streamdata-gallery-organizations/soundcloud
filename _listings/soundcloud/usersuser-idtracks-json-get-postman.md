{
  "info": {
    "name": "Sound Cloud Get Users Tracks",
    "_postman_id": "56dcff08-7a8c-4695-9b85-7722c1e80632",
    "description": "Returns a collection of tracks uploaded by user id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "fd8b2c68-de98-4083-865e-87ddc34a93ba",
          "name": "getTracks.json",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json?consumer_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "890d213e-de38-4960-89fa-8a32d19b5e2b"
            }
          ]
        },
        {
          "id": "064eda0d-fdaa-403b-86d3-07ebf2151bd4",
          "name": "postTracks.json",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Uploads a track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af913c87-3620-45d2-b842-95af813b1ce1"
            }
          ]
        },
        {
          "id": "646cc5d3-2090-4c45-96e5-c9243b216e8d",
          "name": "getTracksTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
              ],
              "query": [
                {
                  "key": "consumer_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50998abc-13f0-4a3d-ba3d-a3df596117dd"
            }
          ]
        },
        {
          "id": "fbeb8d94-d703-40ac-89b5-8d78b36128f9",
          "name": "putTracksTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a given track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fab12d27-c277-4f0a-ac06-8a1951bc8aca"
            }
          ]
        },
        {
          "id": "6de9b816-df71-4ccb-8754-2bb19f849ad8",
          "name": "deleteTracksTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a given track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05c257f2-4fdb-4794-9d1d-9732958bc626"
            }
          ]
        },
        {
          "id": "3aaf46f1-39f5-4622-a5ab-9b0c5b3f435d",
          "name": "getTracksTrackComments.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/comments.json"
              ],
              "query": [
                {
                  "key": "consumer_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns comments of a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "891899a4-b995-4278-90fb-988367add7a9"
            }
          ]
        },
        {
          "id": "dd5f67ba-1090-4736-8f2d-b15d3f605292",
          "name": "postTracksTrackComments.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/comments.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Posts a comments to a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43233dd6-1961-421e-9997-0c22dc7c98bc"
            }
          ]
        },
        {
          "id": "82a1417a-4d3c-4e3a-bbd8-b232f1561e2b",
          "name": "getTracksTrackPermissions.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/permissions.json"
              ],
              "query": [
                {
                  "key": "consumer_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all users with permission for a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cab7593-d973-499e-8aa6-fb0f3748655b"
            }
          ]
        },
        {
          "id": "b236d715-8741-4c36-9aed-6d5527e4d671",
          "name": "putTracksTrackPermissions.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/permissions.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the list of permitted users for a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fd4230d-6ca6-4e1c-88d3-edc64d3c6f76"
            }
          ]
        },
        {
          "id": "0860d139-218e-4dd1-9a92-4350588bbfb1",
          "name": "getTracksTrackSecretToken.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/secret-token.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the secret token for a track by track id. This resource can only be used by the track owner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "975a2a61-ee1f-40e3-8d86-9b0580121c82"
            }
          ]
        },
        {
          "id": "c640f1fe-5bad-446a-acb9-8e10aedcfbcc",
          "name": "putTracksTrackSecretToken.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id/secret-token.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the secret token for a track by track id. The secret token can not be specified but will be randomly chosen on\n          the server and returned. This resource can only be used by the track owner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef4231b2-099c-4c0c-b4a3-820dfee64c76"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "f436acca-665b-4fca-98ef-ab040ba19825",
          "name": "getUsersUserTracks.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/tracks.json"
              ],
              "query": [
                {
                  "key": "consumer_key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "user_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks uploaded by user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09675f77-28a8-47c5-84a5-23cef0b9ba40"
            }
          ]
        }
      ]
    }
  ]
}