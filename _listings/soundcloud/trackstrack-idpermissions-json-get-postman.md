{
  "info": {
    "name": "Sound Cloud Get Tracks Track Permissions",
    "_postman_id": "a5e5bf13-29c6-43e7-b99b-e5fdc0953772",
    "description": "Returns all users with permission for a track by track id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "5a242d16-e0c1-48f1-a4d7-11c63aa8f51b",
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
              "id": "8e76ec9b-8d6c-4e8f-a095-77cd161c2bb6"
            }
          ]
        }
      ]
    }
  ]
}