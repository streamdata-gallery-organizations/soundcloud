{
  "info": {
    "name": "Sound Cloud Get Me Playlists. Format",
    "_postman_id": "56c01d86-e50c-4ded-9374-fdb49726fa48",
    "description": "Returns a collection of playlists created by the logged-in user",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "da850608-96fb-4b9b-8f04-f55fdbbfbade",
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
              "id": "865d21bd-63e9-4b65-a1c4-7c44d9b904c2"
            }
          ]
        },
        {
          "id": "5fada0a9-0078-4a35-9e7e-71bd398df879",
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
              "id": "cc67f71e-8daa-455e-8ed2-10f6b882fa24"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "58c4c71b-739c-4861-b262-f39491ef10b8",
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
              "id": "68661cac-6726-4273-90fd-f26a634fe278"
            }
          ]
        },
        {
          "id": "858c6e1f-6e27-485b-8cdd-f78f35cf6eb1",
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
              "id": "ee4c1319-e502-43e3-a56a-3f4581ae1b8e"
            }
          ]
        }
      ]
    },
    {
      "name": "Playlists",
      "item": [
        {
          "id": "48c843e5-784e-49a5-ac57-b1f615b15e80",
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
              "id": "62cedc8e-733c-41f5-a4ee-c0c02e2a779b"
            }
          ]
        },
        {
          "id": "b334a49b-dae7-4c92-9afb-834ae3adf7ae",
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
              "id": "b7744fa9-263a-49c7-bc2f-63848b17e81f"
            }
          ]
        }
      ]
    }
  ]
}