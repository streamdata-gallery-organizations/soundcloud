{
  "info": {
    "name": "Sound Cloud Put Tracks Track",
    "_postman_id": "a8283010-4959-4ae6-b24c-72926c42c4e5",
    "description": "Updates a given track",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tracks",
      "item": [
        {
          "id": "41d31723-a89e-4878-bd7b-287a612c4891",
          "name": "getTracks.json",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json?consumer_key=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of tracks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5d46349-06fd-4b07-92fc-34ac673fb869"
            }
          ]
        },
        {
          "id": "7f73a477-f485-4c67-9cb8-f0f06e31da87",
          "name": "postTracks.json",
          "request": {
            "url": "http://api.soundcloud.com/tracks.json",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Uploads a track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cab62fe9-e2e6-4f5c-86aa-9f62598c063b"
            }
          ]
        },
        {
          "id": "94a20a8c-d89d-49fb-9775-7e117b1ed15d",
          "name": "getTracksTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
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
            "description": "Returns a track by track id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea511645-5a23-4a2b-be3d-446c27a22707"
            }
          ]
        },
        {
          "id": "39ccf250-ea40-402e-b3f1-53313b9d3647",
          "name": "putTracksTrack.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.soundcloud.com",
              "path": [
                "tracks/:track_id.json"
              ],
              "variable": [
                {
                  "id": "track_id",
                  "value": "track_id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a given track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6881f30-bcc3-4c4b-bc51-80c0f53f2881"
            }
          ]
        }
      ]
    }
  ]
}