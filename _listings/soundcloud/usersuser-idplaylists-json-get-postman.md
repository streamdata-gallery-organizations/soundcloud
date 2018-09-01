{
  "info": {
    "name": "Sound Cloud Get Users Playlists",
    "_postman_id": "cee59f11-2ee7-4cba-9690-a5568e9e9077",
    "description": "Returns a collection of playlists created by user with user id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "33aac200-632b-4265-94eb-1f14a24ea52d",
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
              "id": "91657f99-4efa-493d-8128-d2d57937956e"
            }
          ]
        }
      ]
    }
  ]
}