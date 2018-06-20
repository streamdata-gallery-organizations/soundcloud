{
  "info": {
    "name": "Sound Cloud Get Tracks. Format",
    "_postman_id": "e1a1b3ab-87ef-48d0-ae52-f12ab10c2419",
    "description": "Returns a collection of tracks",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "f613e272-4506-4e09-a584-c43b6b959837",
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
              "id": "dd9fcf47-9256-4501-820e-bfa9faa625fa"
            }
          ]
        },
        {
          "id": "34e0f2e5-c99f-4704-b088-8a42e32ceb19",
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
              "id": "f679cdc0-243d-416a-8947-5217c9b002f4"
            }
          ]
        },
        {
          "id": "d817c818-b826-4bde-b6f9-bf7270b89f0c",
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
              "id": "a4381bef-bbcb-4af5-a899-a43aef9acb25"
            }
          ]
        },
        {
          "id": "007b3a1d-109f-405d-9747-7ca6107c0337",
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
              "id": "6b8b0b47-f3a1-4d2d-860f-7ec1f455f54f"
            }
          ]
        },
        {
          "id": "1b206b14-ce1f-476b-8a33-85341861126a",
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
              "id": "11980d50-32cf-4e39-8e4f-a545c5af56e0"
            }
          ]
        },
        {
          "id": "9a3f6ea1-e049-494f-969c-2d05edc8b26a",
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
              "id": "56eced87-f583-4ebb-b24a-277b6c3e060f"
            }
          ]
        },
        {
          "id": "63c8f90b-a4a3-4e17-ab53-9d9933ba05c1",
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
              "id": "18bbcf29-1f34-4acd-96bf-07d8914e4293"
            }
          ]
        },
        {
          "id": "5ffacc09-a723-4e36-866b-f2f2d3641395",
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
              "id": "186737be-ba14-45ef-bb5f-dd0b008e9366"
            }
          ]
        },
        {
          "id": "5ba6697a-7a66-429f-b032-db1757787d9c",
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
              "id": "d1dfeb73-1afa-4b54-b291-a39bb01eaaff"
            }
          ]
        },
        {
          "id": "65845bc0-1358-423b-8417-85d5e1189cf6",
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
              "id": "065b81aa-6bec-4f90-846a-014e73952bd5"
            }
          ]
        },
        {
          "id": "5020ecda-6bf5-4128-9b10-00ac58fb7f17",
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
              "id": "0fe9eddb-5cc8-4839-a0bd-bec845afc02e"
            }
          ]
        },
        {
          "id": "a4c07ca0-585a-4218-8a1c-6e27174cca53",
          "name": "getTracks.Format",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json?bpm-from=%7B%7D&bpm-to=%7B%7D&consumer_key=%7B%7D&created_at-from=%7B%7D&created_at-to=%7B%7D&duration-from=%7B%7D&duration-to=%7B%7D&filter=%7B%7D&ids=%7B%7D&order=%7B%7D&q=%7B%7D&tags=%7B%7D",
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
              "id": "1eee96e7-84d2-497f-8d78-e2c366d0f1a0"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "8fd6ec61-0aba-43b4-9c9d-f0fb3e2eab05",
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
              "id": "59725964-94a8-4b16-88af-b32eaf22a0d8"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "681bfef6-da27-46df-9b90-0c638806b570",
          "name": "getMeTracks.json",
          "request": {
            "url": "http://api.soundcloud.com/me/tracks.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks uploaded by logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0778452-56ea-412b-a90f-62e44ac582b5"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "d0b44d0f-89da-4dbb-89db-84cc59bd3357",
          "name": "getGroupsGroupTracks.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "groups/:group_id/tracks.json"
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
                  "id": "group_id",
                  "value": "group_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks contributed to the group with group id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f871d560-ec18-456d-bb7a-75e27d167677"
            }
          ]
        }
      ]
    }
  ]
}