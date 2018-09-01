{
  "info": {
    "name": "Sound Cloud Get Playlists. Format",
    "_postman_id": "a9f3e5c9-1ebc-4e95-bc0b-1edad2e5efc3",
    "description": "Returns a collection of playlists",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "602d3666-d6d1-400d-a077-e638d6e220e7",
          "name": "getUsersUserPlaylists.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/playlists.json"
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
            "description": "Returns a collection of playlists created by user with user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3012c91-0a84-44cc-b9d1-27fb55a25ee7"
            }
          ]
        },
        {
          "id": "59674810-4a77-4223-95b5-09394fbdab6b",
          "name": "getUsersUserPlaylists.Format",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "users/:user_id/playlists.json"
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
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of playlists created by user with user id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4c99702-d26f-4d6a-a097-388c08d841a3"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "7e43e980-a593-4d74-a34e-075dab9ecd88",
          "name": "getMePlaylists.json",
          "request": {
            "url": "http://api.soundcloud.com/me/playlists.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of playlists created by the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c6587c6-ab3d-4f72-9d65-b2a5f0c2d32b"
            }
          ]
        },
        {
          "id": "fde90430-edf1-4db8-95ff-b2d06fb981b0",
          "name": "getMePlaylists.Format",
          "request": {
            "url": "http://api.soundcloud.com/me/playlists.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of playlists created by the logged-in user"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7b9fd39-efb0-4ba8-b928-db6693b0dcc9"
            }
          ]
        }
      ]
    },
    {
      "name": "Playlists",
      "item": [
        {
          "id": "6fc2e561-964a-4e9d-b3ca-eae3748a1df3",
          "name": "getPlaylists.json",
          "request": {
            "url": "http://api.soundcloud.com/playlists.json?consumer_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of playlists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd0fc9b4-1776-4778-b66a-411840cc2699"
            }
          ]
        },
        {
          "id": "50474ace-b75c-42eb-8834-ad97cb492b9e",
          "name": "getPlaylistsPlaylist.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "playlists/:playlist_id.json"
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
                  "id": "playlist_id",
                  "value": "playlist_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a playlist by playlist id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "640e3616-a656-4427-831f-5f4a30e388c4"
            }
          ]
        },
        {
          "id": "2f9b851d-9eed-4218-a069-bb83845ec095",
          "name": "getPlaylists.Format",
          "request": {
            "url": "http://api.soundcloud.com/playlists.json?consumer_key=%7B%7D&filter=%7B%7D&q=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of playlists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87430ddb-80d5-4dcc-b650-14635bf1a7a3"
            }
          ]
        }
      ]
    }
  ]
}