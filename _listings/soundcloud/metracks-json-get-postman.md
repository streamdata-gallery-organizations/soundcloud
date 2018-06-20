{
  "info": {
    "name": "Sound Cloud Get Me Tracks",
    "_postman_id": "a3056de4-de05-42bf-8d26-174f6f5b40b3",
    "description": "Returns a collection of tracks uploaded by logged-in user",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "db68c61e-af2f-4697-9849-cfae854e0935",
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
              "id": "00f6217f-5178-49dc-953a-9ee02c0e47f5"
            }
          ]
        },
        {
          "id": "b101e5d9-8ed8-4b7d-bb8b-dd8b36ff5280",
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
              "id": "d8a020f8-b99e-4fa0-b848-24761693b8ef"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "5545bb23-5b50-4205-bf87-5d95f2b7efdb",
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
              "id": "5b08456b-10c5-4703-8c37-64cb6486ef2e"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "17b10896-20b1-4b89-9d14-4a5ce1c5f60b",
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
              "id": "f10507a0-b2fb-4847-adfd-f704405c5410"
            }
          ]
        },
        {
          "id": "66ba16b6-1a5b-4a5e-9ffb-ed07bc3e1d1a",
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
              "id": "4137f1e1-8e02-42de-ab91-0ea14adbc9e3"
            }
          ]
        },
        {
          "id": "43553cc6-c7ed-432c-83fd-b081c6cfa701",
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
              "id": "ff07c838-81ea-41c9-a7a3-6f906eba1922"
            }
          ]
        }
      ]
    }
  ]
}