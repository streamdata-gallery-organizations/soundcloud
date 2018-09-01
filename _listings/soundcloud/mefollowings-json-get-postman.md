{
  "info": {
    "name": "Sound Cloud Get Me Followings",
    "_postman_id": "da17f3ca-0d79-4e78-b322-02449d23753d",
    "description": "Returns a collection of users the logged-in user is following",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "747c6e8e-2333-40eb-91e9-3682885bc3b0",
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
              "id": "23df21f0-fba1-4f7b-b310-fbd734dea51b"
            }
          ]
        },
        {
          "id": "3a5379d5-1620-4bee-9a45-04314cf75a76",
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
              "id": "bb280867-dca7-4ce9-bd37-d20b0e11608c"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "f615a60a-706a-4f2f-a25e-35d35e51b0f0",
          "name": "getUsersUserComments.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/comments.json"
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
            "description": "Returns a collection of comments made by user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c98f61ae-2e0b-4ed6-bf51-8a286e2defb3"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "43a0568f-8966-4242-afed-7a343ff642ea",
          "name": "getMe.json",
          "request": {
            "url": "http://api.soundcloud.com/me.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04de2b9f-2562-4d9b-a9eb-bb105458bc52"
            }
          ]
        },
        {
          "id": "85588013-f41b-4d77-980d-db41c7698df7",
          "name": "putMe.json",
          "request": {
            "url": "http://api.soundcloud.com/me.json",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03b081a6-fe6c-4335-813c-a3e9c6ebd7c0"
            }
          ]
        },
        {
          "id": "d0292c10-e29f-47cb-ac94-98f8d5a9332a",
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
              "id": "52ebc206-2102-4842-a58c-8456af610922"
            }
          ]
        },
        {
          "id": "1a88cc9b-72d8-4d87-a17f-97123183dd70",
          "name": "getMeComments.json",
          "request": {
            "url": "http://api.soundcloud.com/me/comments.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of comments made by logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13699380-5901-4d5d-9055-a03a0976bfa3"
            }
          ]
        },
        {
          "id": "d9197dd1-afaf-47ed-af33-658ed9e0847d",
          "name": "getMeFollowings.json",
          "request": {
            "url": "http://api.soundcloud.com/me/followings.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of users the logged-in user is following"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9aff63ce-c622-4ef2-8f4d-2ce67d4e7311"
            }
          ]
        }
      ]
    }
  ]
}