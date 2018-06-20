{
  "info": {
    "name": "Sound Cloud Get Users Playlists. Format",
    "_postman_id": "b06daedc-ee29-4114-85be-e33440bb391e",
    "description": "Returns a collection of playlists created by user with user id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "5aab584d-9300-485f-b91b-c112ef4512f2",
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
              "id": "66f00f06-f6e4-403c-a2f9-007c17bb8300"
            }
          ]
        },
        {
          "id": "13d1d24f-6eef-478b-90e3-fefc2435e832",
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
              "id": "9d36bc25-6dec-469c-ad83-790a54b27353"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "bb6c91fb-d020-45d5-b3f9-79058d7ac3df",
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
              "id": "8d14fc43-a9fe-4e9a-a1b9-6af1c046882f"
            }
          ]
        }
      ]
    },
    {
      "name": "Playlists",
      "item": [
        {
          "id": "2d7f019e-2a62-4e77-b218-f01ebd26572c",
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
              "id": "70466f49-a6e5-407c-9c57-9960399dbb3a"
            }
          ]
        },
        {
          "id": "3f81eaf9-ec00-4b5e-840e-da62462114a8",
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
              "id": "4470989d-67cc-41de-bfbc-7b4f46e192a5"
            }
          ]
        }
      ]
    }
  ]
}