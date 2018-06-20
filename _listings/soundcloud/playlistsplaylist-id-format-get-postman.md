{
  "info": {
    "name": "Sound Cloud Get Playlists Playlist . Format",
    "_postman_id": "32f9d552-190c-44f6-a7ea-5707a973930b",
    "description": "Returns a playlist by playlist id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "b14f2e4f-8728-41d1-8a37-97727fb1de8b",
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
              "id": "8aefbb97-e281-4d1f-a8ff-dc8f326adc74"
            }
          ]
        },
        {
          "id": "ca3be808-3a3c-4909-8b1e-28f6aa6b760e",
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
              "id": "8b3ace26-e733-4ce8-838d-80e4093c2e61"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "fb782584-2e83-4819-9dc2-2d8635696649",
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
              "id": "0ad2a6ff-91dd-4a4b-ae37-ee9cf45520b3"
            }
          ]
        },
        {
          "id": "f8d4b6dc-e4bc-4b08-b325-03792c65cb99",
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
              "id": "bfa3eb44-14ad-4975-8933-5ef069c1996e"
            }
          ]
        }
      ]
    },
    {
      "name": "Playlists",
      "item": [
        {
          "id": "3ffbcba9-0143-4e0f-983b-ebb157c23a48",
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
              "id": "fd8d83da-7020-4188-9cb1-740fbd0656dc"
            }
          ]
        },
        {
          "id": "f6e98498-a4d1-448a-8118-bf481ff5e30f",
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
              "id": "f4cd7034-f9e9-4571-8739-c500e5a238d6"
            }
          ]
        },
        {
          "id": "3ea2a135-0464-47da-95e8-08f29a65a3e1",
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
              "id": "9d4d3552-b019-47f0-9c70-0017ae558f78"
            }
          ]
        },
        {
          "id": "67667796-7ed7-4166-b890-de53785ec897",
          "name": "getPlaylistsPlaylist.Format",
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
                  "value": "{}",
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
              "id": "21fa8ba6-457a-47b1-9137-4a385a351215"
            }
          ]
        }
      ]
    }
  ]
}