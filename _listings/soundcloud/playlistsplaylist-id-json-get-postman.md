{
  "info": {
    "name": "Sound Cloud Get Playlists Playlist",
    "_postman_id": "7e9a967c-a8dd-4a0b-9aa0-9429225f638e",
    "description": "Returns a playlist by playlist id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "44b8a562-16e2-4f3a-be8b-c786975c6944",
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
              "id": "82433f0e-4be5-44c0-bd8e-9bf777662cb9"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "34778ec3-4047-490a-8d21-d33ce7594c97",
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
              "id": "fc2c4533-44ad-4737-a82b-40f90e02d36b"
            }
          ]
        }
      ]
    },
    {
      "name": "Playlists",
      "item": [
        {
          "id": "12a4b644-4bbd-4ce3-bda5-baf8e3f36cb6",
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
              "id": "c4374f18-a321-4bee-8ccf-b1592319317e"
            }
          ]
        },
        {
          "id": "df257bf3-b424-4cf8-8a1d-ad5e0568b414",
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
              "id": "472b1489-d46a-4edf-b5b5-b6894c807767"
            }
          ]
        }
      ]
    }
  ]
}