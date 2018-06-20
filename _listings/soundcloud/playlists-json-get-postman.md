{
  "info": {
    "name": "Sound Cloud Get Playlists",
    "_postman_id": "3b6ef2e3-9866-4d79-b913-6239b5865830",
    "description": "Returns a collection of playlists",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "e9a8822b-1f3d-4fbb-ac03-12ec8434d57f",
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
              "id": "d98dd115-5bf9-42ec-bde9-e19cc16b3f93"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "2dca3b8f-c097-4d52-95cd-ad17831eb902",
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
              "id": "92d8dea8-24d3-4f79-bae4-4725d9501f29"
            }
          ]
        }
      ]
    },
    {
      "name": "Playlists",
      "item": [
        {
          "id": "6a86306d-7b7d-4a91-b3e8-b082898ee854",
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
              "id": "9772f2d6-3c2d-4a1e-8b27-3c37bbe25020"
            }
          ]
        }
      ]
    }
  ]
}